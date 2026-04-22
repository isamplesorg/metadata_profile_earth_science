# Vocabulary extensions for EarthScience material samples.

## Vocabulary documents
This repository hosts the four extension vocabularies for use with iSamples metadata describing Earth Science material samples: Rock_Sediment, Mineral_Group, material sample object type, and sampled feature role. The authoritative source files are rdf SKOS vocabularies serialized using Turtle syntax. These are in the **vocabulary** folder. The **docs** folder contains Markdown and HTML presentations of the vocabulary content.

### Rendered documentation
The rendered vocabulary pages are published at:
**<http://isamples.org/metadata_profile_earth_science/>** (also reachable via `https://isamplesorg.github.io/metadata_profile_earth_science/`, which 301-redirects there). The landing page is generated from [`docs/readme.md`](docs/readme.md).

| Vocabulary | Source `.ttl` | Concept scheme CURIE | Rendered HTML |
|---|---|---|---|
| Mineral group | [`earthenv_material_extension_mineral_group.ttl`](vocabulary/earthenv_material_extension_mineral_group.ttl) | `ming:mineralgroupvocabulary` | [HTML](http://isamples.org/metadata_profile_earth_science/earthenv_material_extension_mineral_group.html) |
| Rock / sediment | [`earthenv_material_extension_rock_sediment.ttl`](vocabulary/earthenv_material_extension_rock_sediment.ttl) | `rksd:rocksedimentvocabulary` | [HTML](http://isamples.org/metadata_profile_earth_science/earthenv_material_extension_rock_sediment.html) |
| Sampled feature role | [`earthenv_sampled_feature_role.ttl`](vocabulary/earthenv_sampled_feature_role.ttl) | `essampledfeatrole:sfrolevocabulary` | [HTML](http://isamples.org/metadata_profile_earth_science/earthenv_sampled_feature_role.html) |
| Material sample object type | [`earthenv_materialsampleobject_type.ttl`](vocabulary/earthenv_materialsampleobject_type.ttl) | `esmat:essampletype` | [HTML](http://isamples.org/metadata_profile_earth_science/earthenv_materialsampleobject_type.html) |

##  Vocabulary presentation template

This repository hosts python code and github actions to support maintenance and presentation of vocabularies represented using the SKOS RDF vocabulary, serialized using Turtle. It includes a github action configuration that will update files representing the vocabulary in Markdown and HTML format. The SKOS representation of the vocabularies in the Vocabulary folder are considered the canonical versions; changes to the vocabulary should be made in the SKOS files; updates (pushes) to the vocabulary will trigger a Github action update the Markdown and HTML representations. The HTML representation is published via Github pages from the content in the docs folder.

The code and workflow here were developed by Dave Vieglais for the [iSamples project](https://isamplesorg.github.io/) to support not only the generation of the github.io pages, but more general methods for accessing the vocabularies via SPARQL queries. The vocabulary access functionality is implemented by the navocab.py in the tools/navocab directory in the repository.   

The code and actions are set up assuming the file structure in this template, with content as follows:
The root of the repo contains:
- a readme.md file (this file), which in a deployed version of this template should replace this section of the readme with a description of the vocabularies that are hosted in the repository
- Dockerfile. file containing instructions for building a Docker container with the code that converts the SKOS turtle files to Markdown and HTML representations
- License. License for use of the artifacts in the repository. This template is Licensed with the Apache 2.0 license
- action.yml. Configuration file for the Github actions that automate updates to the Markdown and HTML files when the repository is updated
  
Subdirectories are:
- .github: This directory contains two subdirectories.
  - actions: contains python code that executes the  **Process vocabularies** action
  - workflows: contains yaml files defining the workflows executed by a github action. IN the template there is only one configuration file 'process_vocab.yml
- Cache:  contains an SQLAlchemy database vocabularies.db with is loaded with the vocabularies specified in the process_vocab.yml file. It is populated from the turtle files when the **Process vocabularies** action is run.
- Docs: This directory will contain Markdown and HTML files representing the vocabularies targeted in the **Process vocabularies** action after the action is run
- Tools: This directory contains python code.
  - vocab.py. code that loads the cache/vocabularies.db database when the **Process vocabularies** action is run
  - vocab2mdCache.py
  - runVocabTools.py
  - requirements.txt
  - tests: contains code for testing the system, created by Dave Vieglais. This code has not been tested to work with the updates made to create this template repo, but is included for future use.
  - navocab: contains navocab.py, which implements methods for accessing the SKOS vocabularies that are cached in the cache/vocabularies.db SQLAlchemy database. Only the database initialization and loading functions from this program are used for generating the Markdown and HTML representations. 
- Vocabulary: contains SKOS vocabularies serialized using the turtle format.

### Implementation: 
#### Vocabulary github action

The `action.yml` (which is required to be located at the root of the repository) defines the action inputs and outputs.  

The action is run as a Docker image, and the image is built according to the instructions in the `Dockerfile` (which is also in the root of the repository, due to Docker's requirement that all things built into the image be located in the same directory).

The code in this repository is designed to read a vocabulary serialized using SKOS RDF/Turtle. The source turtle files, with file extension '.ttl', are expected to reside in the vocabulary directory in the repository.

#### The processing pattern: 

When you run the action **Process vocabularies**, it looks at /action.yml (github does this w/o any asking-- you just have to know it happens); this configuration file provides some metadata about the action, defines the input variables (not their values), and the process that the action runs, in this case Docker to build a container defined by /Dockerfile. GitHub is responsible for converting the action parameters defined in action.yml and  assigned values in process_vocab.yml into environment variables that are accessible to the python code that executes in the Docker container.
-- action.yml triggers deploying a Docker container defined by Dockerfile 
-- Dockerfile builds a Docker container, copying these files from the host repository:
  1) the source ttl files directory from /vocabulary,  
  2) the /tools folder with vocab.py and vocab2md.py,
  3) .github/actions/github_action_main.py, and 
  4) /Makefile. The make file has rules that can be used on invocation, including 

github_action_main.py is set as the entrypoint for the container. Its input arguments are passed as environmental variables. Action.yml defines the variables, process_vocab_yml specifies values for the inputs. These are the input arguments:
  1) 'command' (values are 'doc' or 'uijson') and
  2) 'path' environmental variables (which are defined in action.yml, and assigned values in integration.yml )
  3) 'inputttl' a list of the turtle files in the vocabulary directory that are to be processed. The file names are passed without the .ttl file extension; these file names will be used to name the output Markdown and HTML files with appropriate extensions.
  4) 'inputvocaburi' a list of the URIs for the root ConceptScheme in each input file, using the prefixes from those files. Assumption is that only one ConceptScheme is defined in each file. The output is constructed as a tree (or set of trees) with a skos:topConcept term as the root of the tree. The order of the URIs must correspond to the order of the file names in inputttl.  

When the workflow is run, the docker container gets spun up. The container configuration in /Dockerfile copies the cache, docs, tools and vocabulary directories into the container, installs python module dependencies using apt-get and pip, downloads the package for installing Quarto, and installs Quarto.  Quarto is used to process the Markdown files to generate HTML. Dockerfile defines .github/actions/github_action_main.py as the entrypoint to execute when the container is built. 

The entrypoint script github_action_main.py is executed.  This python executes vocab.py inside the container using subprocess.run call. Vocab.py loads the vocabularies listed in the `inputttl` variable into the cache\vocabularies.db database. Based on the `command` input:
- uijson: runs vocab.py as a subprocess in the container to generate json file representing each vocabulary in `inputtl` that can be used to support other functions (e.g. a different user interface)
- docs: runs vocab2mdCacheV2.py to generate Markdown files, and then runs Quarto to generate HTML from the Markdown files. Both of these are run as subprocesses in the container.

All output is placed in the \docs directory.

Finally, the `deploy ...` steps in the workflow defined by .github/workflows/process_vocab.yml copy the output from the docs directory to the docs directory in the host github, and the cache directory with updated vocabularies.db into the cache directory on the host.
 
### Python code
- vocab.py: loads vocabs into the SQLAlchemy database vocabularies.db
- vocab2mdCacheV2.py: reads a vocab specified by a root (skos:ConceptScheme) URI from the vocabularies.db database and generates Markdown and HTML or JSON depending on the 'command' input parameter
- runVocabtools.py: a version of github_action_main.py set up to run offline in an IDE environment for testing

### Github configuration
- Options: fork this repository, or create a new repository using the template. If you fork the repository it might be easier to sync with updates to the code made in the template repository.
- enable github actions
- enable github pages, based on the docs directory and main branch.  HTML pages can be viewed in a browser at https://{yourOrgName}.github.io/{theNAMEyouGiveTheForkedRepo}/{vocabFileName}.html

#### SKOS vocabulary conventions 
The code assumes the root of the repository is a skos:ConceptScheme, and that there is a skos:prefLabel for the ConceptScheme.  The uri for the conceptScheme must use a CURIE with the prefix defined in the prefix section of the skos file. The terms in teh vocabualary must all be skos:Concept, with a skos:prefLabel. The top concepts in the vocabulary must be identified with a skos:topConceptOf assertion. Hierarchy must be represented with skos:broader predicates link a term with its parent term (or terms).rdfs:comment or skos:definition will be used as term definitions. Other predicates that are recognized: skos:altLabel, rdfs:seeAlso, dublin core terms (dct:) source, dct:modified, skos:historyNote. Other predicates with the vocabulary as subject will not be shown in the output.

#### Testing
There is a test file at `.github/workflows/integration.yml`, which can be run manually using the workflow dispatch option.  It contains the necessary instruction to check out the repository and run it as a GitHub action.

### Entry Point
The Docker entrypoint of the action is the python file located at `.github/actions/vocabularies/github_action_main.py`.  GitHub is responsible for converting the action parameters into environment variables that the script interprets.
