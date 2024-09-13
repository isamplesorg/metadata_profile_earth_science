---
comment: | 
  WARNING: This file is generated. Any edits will be lost!
format:
  html:
    ascii: true
    toc: true
    toc-depth: 4
    number-sections: true
    anchor-sections: false
    number-depth: 8
execute:
  echo: false
---

[]{#EarthandEnvironmentalScienceextension-Materialsampletype}

# **Concept scheme:** Earth and Environmental Science extension -  Material sample type

Vocabulary last modified:  2024-07-15

subtitle: 
  This concept scheme contains skos concepts for categorizing kinds of Earth Material sample types, extending the iSamples Material Sample Object Type vocabulary. Defintions from SESAR, ODM2, wikipedia, ESS-DIVE, and other sources; sources are cited with each term.

Namespace: 
[`https://w3id.org/isample/earthenv/esmaterialsample/essampletype`](https://w3id.org/isample/earthenv/esmaterialsample/essampletype)

**History**

* 2023-07-07 SMR add solid material sample and broader relations from classes it subsumes.
* 2023-07-27 SMR modify base specimen type vocabulary, add 'Non biologic solid object' to replace 'solid material sample', change broader relations in this vocab to use that as parent class where appropriate. 'Solid material sample' is too closely linked to material type, created confusion. Intention is a specimen category for solid objects that are not biologic. Obviously there is some overlap with Research specimens.
* 2024-07-15 SMR fix import to base vocabulary on renamed material_sample_type vocabulary, change from specimentypevocabulary to materialsampleobjecttype/conceptscheme

- [Analytical preparation](#analyticalpreparation)
    - [Cell culture](#cellculture)
    - [Dissolved chemical fraction](#dissolvedchemicalfraction)
        - [Eluate](#eluate)
    - [FIB lamella](#fiblamella)
    - [Glass slide smear](#glassslidesmear)
    - [Individual solid cube](#individualsolidcube)
    - [Magnetic fraction](#magneticfraction)
    - [Mechanical fraction](#mechanicalfraction)
    - [Mineral separate](#mineralseparate)
        - [Magnetic fraction](#magneticfraction)
        - [Non-magnetic fraction](#nonmagneticfraction)
    - [Sectioned specimen](#mountedsection)
        - [Thick section](#thicksection)
        - [Thin section](#thinsection)
            - [Polished thin section](#polishedthinsection)
        - [Ultra thin section](#ultrathinsection)
    - [Non-magnetic fraction](#nonmagneticfraction)
    - [Peel](#peel)
    - [Prepared powder](#preparedpowder)
        - [Prepared rock powder](#preparedrockpowder)
    - [Pressed pellet](#pressedpellet)
    - [Residual material](#residualmaterial)
    - [Slab](#slab)

- [Bundle biome aggregation](#bundlebiomeaggregation)
    - [Cell culture](#cellculture)

- [Fluid in container](#fluidincontainer)
    - [Direct fluid sample](#directfluidsample)
    - [Dissolved chemical fraction](#dissolvedchemicalfraction)
        - [Eluate](#eluate)
    - [Processed fluid sample](#processedfluidsample)
        - [Filtrate](#filtrate)

- [Generic aggregation](#genericaggregation)
    - [Boxed core](#boxedcore)
    - [Composite sample](#compositesample)
        - [Chip Channel Sample](#chipchannelsample)
        - [High Grade Sample](#highgradesample)
        - [Site composite sample](#sitecompositesample)
    - [Core catcher](#corecatcher)
    - [Cuttings](#cuttings)
    - [Dredge](#dredge)
    - [Material captured in filter](#materialcapturedinfilter)
    - [Mechanical fraction](#mechanicalfraction)
    - [Mineral separate](#mineralseparate)
        - [Magnetic fraction](#magneticfraction)
        - [Non-magnetic fraction](#nonmagneticfraction)
    - [Natural aggregate specimen](#naturalaggregate)
    - [Prepared powder](#preparedpowder)
        - [Prepared rock powder](#preparedrockpowder)
    - [TEM grid](#temgrid)
    - [Trawl](#trawl)

- [Other solid object](#othersolidobject)
    - [Dust wipe](#dustwipe)
    - [Glass slide smear](#glassslidesmear)
    - [Peel](#peel)

- [Solid material sample](#solidmaterialsample)
    - [Core](#core)
    - [Core half round](#corehalfround)
    - [Core peice](#corepeice)
    - [Core quarter round](#corequarterround)
    - [Core section](#coresection)
    - [Core subpeice](#coresubpeice)
    - [FIB lamella](#fiblamella)
    - [Individual solid cube](#individualsolidcube)
    - [Individual solid cylinder](#individualsolidcylinder)
    - [Meteorite](#meteorite)
    - [Mineral specimen](#mineralspecimen)
    - [Sectioned specimen](#mountedsection)
        - [Thick section](#thicksection)
        - [Thin section](#thinsection)
            - [Polished thin section](#polishedthinsection)
        - [Ultra thin section](#ultrathinsection)
    - [Pressed pellet](#pressedpellet)
    - [Rock hand sample](#rockhandsample)
    - [Slab](#slab)
    - [U-channel sample](#uchannelsample)
    - [Atom probe tip](#atomprobetip)
    - [Chip](#chip)
    - [Microtome slice](#microtomeslice)
    - [Mounted specimen](#mountedspecimen)
        - [Polished mounted specimen](#polishedmountedspecimen)
    - [Particle](#particle)

**Concepts**

[]{#analyticalpreparation}

##  Analytical preparation
- Specimen is a product of processing required for some observation
procedure, e.g. thin section, XRF bead, SEM stub, rock powder. If
identified separately, this should have a ‘parent’ link to the
original sample
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/analyticalpreparation


[]{#cellculture}

###  Cell culture
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`bundlebiomeaggregation`](#bundlebiomeaggregation)
- a collection of cells are grown under controlled conditions,
generally outside of their natural environment
- **Source:**
https://en.wikipedia.org/wiki/Cell_culture
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/cellculture


[]{#dissolvedchemicalfraction}

###  Dissolved chemical fraction
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`fluidincontainer`](#fluidincontainer)
- A fluid concentrating some constituent of interest from a parent
sample. The dissolved constituent is actually the sample material of
interest.
- **Source:**

- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/dissolvedchemicalfraction


[]{#eluate}

####  Eluate
- Child of:
 [`dissolvedchemicalfraction`](#dissolvedchemicalfraction)
- The fluid product that contains the analyte of interest washed from
a chromatography column
- **Source:**
OSIRIS-Rex Sample types, 
https://en.wikipedia.org/wiki/Elution, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.6-Liquids-and-Washes, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/eluate


[]{#fiblamella}

###  FIB lamella
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- very thin sheet of solid material milled from a larger sample using
a focused ion beam. Used for TEM analysis.
- **Source:**
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.5-FIB-sections%2C-microtome-slices%2C-atom-probe-tips%2C-TEM-grids, 
this vocabulary, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/fiblamella


[]{#glassslidesmear}

###  Glass slide smear
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`othersolidobject`](#othersolidobject)
- sample from a cell culture (or other microparticulate suspension)
spread into a thin layer on a glass slide for optical investigation
- **Source:**
https://pubs.usgs.gov/of/2001/of01-041/htmldocs/methods/sslide.htm
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/glassslidesmear


[]{#individualsolidcube}

###  Individual solid cube
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- A sample that is a prepared cube of material, intended as a sample
of that material.
- **Source:**
SESAR vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/individualsolidcube


[]{#magneticfraction}

###  Magnetic fraction
- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)
- a collection of particles separated from a crushed rock sample based
on their attraction to a magnet.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/magneticfraction


[]{#mechanicalfraction}

###  Mechanical fraction
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)
- defined by sample preparation involving mechanical processing, e.g.
grain size, density, or grain shape separation.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mechanicalfraction


[]{#mineralseparate}

###  Mineral separate
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)
- an aggregation of particles of the same mineral extracted and
concentrated from a rock.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mineralseparate


[]{#magneticfraction}

####  Magnetic fraction
- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)
- a collection of particles separated from a crushed rock sample based
on their attraction to a magnet.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/magneticfraction


[]{#nonmagneticfraction}

####  Non-magnetic fraction
- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)
- collection of particles from a crushed rock sample based on their
lack of attraction to a magnet
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/nonmagneticfraction


[]{#mountedsection}

###  Sectioned specimen
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- a thin slice of a solid material that has been mounted on a glass
slide for study
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mountedsection


[]{#thicksection}

####  Thick section
- Child of:
 [`mountedsection`](#mountedsection)
- Thick sections are like thin sections, but milled to a greater
thickness. Typcially polished on one or both sides and used for fluid
or melt inclusion studies, Raman analyses, and infrared spectroscopy
analyses, and SEM or electron microprobe. The standard thickness for a
fluid inclusion thick section is 50 micrometers, but thick sections
can be made at any thickness.  Thick sections can be attached to a
glass slide, or can be prepared so that they can be removed from their
mount as a stand-alone slice of rock.
- **Source:**
https://viva.pressbooks.pub/analyticalmethodsingeosciences/chapter/2-2-thin-section-and-thick-section-anatomy/
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/thicksection


[]{#thinsection}

####  Thin section
- Child of:
 [`mountedsection`](#mountedsection)
- thin sliver of rock cut from a sample with a diamond saw and ground
optically flat, and then mounted on a glass slide and ground smooth
using progressively finer abrasive grit until the sample is 30 microns
thick.
- **Source:**
 https://en.wikipedia.org/wiki/Thin_section, 
http://vocabulary.odm2.org/specimentype/thinSection/ , 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/thinsection


[]{#polishedthinsection}

#####  Polished thin section
- Child of:
 [`thinsection`](#thinsection)
- a thin section that has its free surface polished until perfectly
planar and free of pits and scratches. Used for reflected light
petrography and for electron microprobe or SEM investigation.
- **Source:**
http://www.minsocam.org/ammin/AM53/AM53_2070.pdf
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/polishedthinsection


[]{#ultrathinsection}

####  Ultra thin section
- Child of:
 [`mountedsection`](#mountedsection)
- An ordinary thin section that is attached to the glass slide using a
soluble cement such as Canada balsam (soluble in ethanol) to allow
both sides to be worked on. The section is polished on both sides
using a fine diamond paste until it has a thickness in the range of
2-12 microns. This technique has been used to study the microstructure
of very fine-grained carbonate rocks, and also in the preparation of
mineral and rock specimens for transmission electron microscopy.
- **Source:**
http://vocabulary.odm2.org/specimentype/thinSection/  | https://en.wikipedia.org/wiki/Thin_section
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/ultrathinsection


[]{#nonmagneticfraction}

###  Non-magnetic fraction
- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)
- collection of particles from a crushed rock sample based on their
lack of attraction to a magnet
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/nonmagneticfraction


[]{#peel}

###  Peel
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`othersolidobject`](#othersolidobject)
- Acetate peels are made by polishing a planar surface on a sample,
etching it with acid to give it some relief, and then chemically
melting a piece of acetate onto that surface. The acetate is then
pulled off for examination under a microscope. The acetate preserves a
fingerprint of the internal structure of the sample surface. Used in
paleontology to study complex fossils, e.g. bryozoan.
- **Source:**
https://strata.uga.edu/cincy/fauna/bryozoanStudy/acetatePeels.html
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/peel


[]{#preparedpowder}

###  Prepared powder
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)
- distinguish from particulate in that particulate is sampled as a
micron-size aggregate, whereas this material is ground to a powder for
subsequent analysis; it is a powder as a function of some preparation
process (e.g. chemical precipitation)
- **Alternate labels:**
Powder
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/preparedpowder


[]{#preparedrockpowder}

####  Prepared rock powder
- Child of:
 [`preparedpowder`](#preparedpowder)
- a powder manufactured by pulverizing a rock.
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/preparedrockpowder


[]{#pressedpellet}

###  Pressed pellet
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- a sample prepared by grinding a parent sample to a fine powder,
mixing it with a binder, and pressing the mixture into a die at a
pressure of between 15 and 35 tons to produce a solid disc for
subsequent analysis, typically by X-Ray fluorescence.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/pressedpellet


[]{#residualmaterial}

###  Residual material
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
- Sample is material remaining after processing to extract some other
components of interest from the sample.
- **Alternate labels:**
Residue
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/residualmaterial


[]{#slab}

###  Slab
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- a relatively planar rock sample,cut from a large sample to produce a
tabular peice of rock with the irregular outline of the original
sample on the diameter where the cut was mate.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/slab



[]{#bundlebiomeaggregation}

##  Bundle biome aggregation
- An aggregation of whole organisms representative of some biome
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/bundlebiomeaggregation


[]{#cellculture}

###  Cell culture
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`bundlebiomeaggregation`](#bundlebiomeaggregation)
- a collection of cells are grown under controlled conditions,
generally outside of their natural environment
- **Source:**
https://en.wikipedia.org/wiki/Cell_culture
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/cellculture



[]{#fluidincontainer}

##  Fluid in container
- Specimen is a container whose contents are liquid, gas, or mixed
dominantly fluid phases that is the actual sample material. Fluid
might include minor solid particles. Container typically human made,
but also includes natural fluid container, e.g. fluid inclusion in a
mineral grain.  Includes colloids, foams, gels, suspensions. The
sample is the fluid substance; fluid samples collected to analyze the
contained biome should be considered 'Biome Aggregation'
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/fluidincontainer


[]{#directfluidsample}

###  Direct fluid sample
- Child of:
 [`fluidincontainer`](#fluidincontainer)
- a fluid collected from the sampled feature (e.g. water body,
hydrothermal vent, atmosphere...) with no processing. (e.g.
filtration, addition of preservatives).
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/directfluidsample


[]{#dissolvedchemicalfraction}

###  Dissolved chemical fraction
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`fluidincontainer`](#fluidincontainer)
- A fluid concentrating some constituent of interest from a parent
sample. The dissolved constituent is actually the sample material of
interest.
- **Source:**

- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/dissolvedchemicalfraction


[]{#eluate}

####  Eluate
- Child of:
 [`dissolvedchemicalfraction`](#dissolvedchemicalfraction)
- The fluid product that contains the analyte of interest washed from
a chromatography column
- **Source:**
OSIRIS-Rex Sample types, 
https://en.wikipedia.org/wiki/Elution, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.6-Liquids-and-Washes, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/eluate


[]{#processedfluidsample}

###  Processed fluid sample
- Child of:
 [`fluidincontainer`](#fluidincontainer)
- fluid sample that has been processed in some way during or after
collection, e.g. by filtering, addition of preservatives.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/processedfluidsample


[]{#filtrate}

####  Filtrate
- Child of:
 [`processedfluidsample`](#processedfluidsample)
- A sample that has gone through a filtration process to separate
solids from fluids (liquids or gases), using a filter medium through
which only the fluid can pass. Must be associated with a filter size.
- **Source:**
https://github.com/ess-dive-community/essdive-sample-id-metadata/blob/master/terms/objectType.md
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/filtrate



[]{#genericaggregation}

##  Generic aggregation
- An aggregate specimen that is not biogenic or composed of
anthropogenic material fragments.  Examples: loose soil or sediment
(e.g. in a bag), rock chips, particulate filtrate or precipitate; rock
powders.
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/genericaggregation


[]{#boxedcore}

###  Boxed core
- Child of:
 [`genericaggregation`](#genericaggregation)
- A collection of core peices that are stored in an individual box.
Typically the box will contain core peices from the same core.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/boxedcore


[]{#compositesample}

###  Composite sample
- Child of:
 [`genericaggregation`](#genericaggregation)
- a sample composed of multiple peices, representative of some
material, or representative of some site. The peices do not all
originate from the same object.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/compositesample


[]{#chipchannelsample}

####  Chip Channel Sample
- Child of:
 [`compositesample`](#compositesample)
- small chips of rock collected over a specified interval, with the
objective to obtain a representative sample for that interval. Most of
the time chip channel samples are collected in succession along a
sample line which is laid out in advance using a tape.  The freshest
material possible is sampled, preferably chipping directly from
bedrock. Sample intervals are set at a specified width, usually
ranging from 30cm to 7m. Due to the method of sampling, chip channel
samples tend to be rather large (up to 20 pounds for a five foot
interval)
- **Source:**
http://earthsci.org/mineral/rockmin/sampling/sampling.html#Rock%20Sampling
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/chipchannelsample


[]{#highgradesample}

####  High Grade Sample
- Child of:
 [`compositesample`](#compositesample)
- in mineral exploration, selective pieces of the most highly
mineralized material from a mineralize site, intentionally excluding
less mineralized material. A high grade sample might be collected to
indicate what the best possible values are, or to provide material for
certain types of trace element analyses.
- **Source:**
http://earthsci.org/mineral/rockmin/sampling/sampling.html#Rock%20Sampling
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/highgradesample


[]{#sitecompositesample}

####  Site composite sample
- Child of:
 [`compositesample`](#compositesample)
- an aggregation of peices of uniform material collected over some
area (generally greater than 2.5m across). These are the ideal
'representative' samples used in mineral exploration. A composite
sample might be collected to determine the background values of trace
elements in a particular type of rock, or to determine if ore grade
mineralization is present over a large area.
- **Source:**
http://earthsci.org/mineral/rockmin/sampling/sampling.html#Rock%20Sampling
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/sitecompositesample


[]{#corecatcher}

###  Core catcher
- Child of:
 [`genericaggregation`](#genericaggregation)
- material recovered from the core catcher of a sedimentary core and
which is treated as a separate section from the core. The core catcher
is a device at the bottom of the core barrel that prevents the core
from sliding out while the barrel is retrieved from the hole.
(http://publications.iodp.org/proceedings/323/102/102_.htm)
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/corecatcher


[]{#cuttings}

###  Cuttings
- Child of:
 [`genericaggregation`](#genericaggregation)
- unconsolidated Earth material produced by the grinding action of a
drill bit during drilling of a borehole.
- **Source:**
http://vocabulary.odm2.org/specimentype/cuttings/
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/cuttings


[]{#dredge}

###  Dredge
- Child of:
 [`genericaggregation`](#genericaggregation)
- an aggregation of material sampled by dragging a collection bucket
(dredge) across the bottom of a water body
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/dredge


[]{#materialcapturedinfilter}

###  Material captured in filter
- Child of:
 [`genericaggregation`](#genericaggregation)
- A material sample captured in filter, for example from a water
sample that was filtered. Must be associated with filter size field.
- **Source:**
https://github.com/ess-dive-community/essdive-sample-id-metadata/blob/master/terms/objectType.md
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/materialcapturedinfilter


[]{#mechanicalfraction}

###  Mechanical fraction
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)
- defined by sample preparation involving mechanical processing, e.g.
grain size, density, or grain shape separation.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mechanicalfraction


[]{#mineralseparate}

###  Mineral separate
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)
- an aggregation of particles of the same mineral extracted and
concentrated from a rock.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mineralseparate


[]{#magneticfraction}

####  Magnetic fraction
- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)
- a collection of particles separated from a crushed rock sample based
on their attraction to a magnet.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/magneticfraction


[]{#nonmagneticfraction}

####  Non-magnetic fraction
- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)
- collection of particles from a crushed rock sample based on their
lack of attraction to a magnet
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/nonmagneticfraction


[]{#naturalaggregate}

###  Natural aggregate specimen
- Child of:
 [`genericaggregation`](#genericaggregation)
- E.g beach sand, soil, river sediment, scoop of regolith.
- Specimen is aggregate of non-consolidated material formed by natural
processes. Particles have not been intentionally modified from the
sampled feature.
- **Alternate labels:**
Aggregate sample
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/naturalaggregate


[]{#preparedpowder}

###  Prepared powder
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)
- distinguish from particulate in that particulate is sampled as a
micron-size aggregate, whereas this material is ground to a powder for
subsequent analysis; it is a powder as a function of some preparation
process (e.g. chemical precipitation)
- **Alternate labels:**
Powder
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/preparedpowder


[]{#preparedrockpowder}

####  Prepared rock powder
- Child of:
 [`preparedpowder`](#preparedpowder)
- a powder manufactured by pulverizing a rock.
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/preparedrockpowder


[]{#temgrid}

###  TEM grid
- Child of:
 [`genericaggregation`](#genericaggregation)
- FIB sections and microtome slices set onto a small grid for
handling, transport, and analysis using a transmission electron
microscope (TEM). The grid itself can be given a single sample
identifier (similar to how there are multiple grains in a grain
mount). The linkage from the individual samples in the grid to their
parent sample(s) should be documented
- **Source:**
OSIRIS-Rex Sample types, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.5-FIB-sections%2C-microtome-slices%2C-atom-probe-tips%2C-TEM-grids, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/temgrid


[]{#trawl}

###  Trawl
- Child of:
 [`genericaggregation`](#genericaggregation)
- an aggregation of biogenic or non-biogenic material extracted from a
water body
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/trawl



[]{#othersolidobject}

##  Other solid object
- Single piece of material not one of the other types.
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/othersolidobject


[]{#dustwipe}

###  Dust wipe
- Child of:
 [`othersolidobject`](#othersolidobject)
- a pre-weighed and packaged paper towel (wipe) used to wipe over a
surface to collect particulates from the surface
- **Source:**
https://www.cdc.gov/nceh/lead/docs/publications/Environmental_Sampling.pdf, dust wipe sampling
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/dustwipe


[]{#glassslidesmear}

###  Glass slide smear
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`othersolidobject`](#othersolidobject)
- sample from a cell culture (or other microparticulate suspension)
spread into a thin layer on a glass slide for optical investigation
- **Source:**
https://pubs.usgs.gov/of/2001/of01-041/htmldocs/methods/sslide.htm
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/glassslidesmear


[]{#peel}

###  Peel
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`othersolidobject`](#othersolidobject)
- Acetate peels are made by polishing a planar surface on a sample,
etching it with acid to give it some relief, and then chemically
melting a piece of acetate onto that surface. The acetate is then
pulled off for examination under a microscope. The acetate preserves a
fingerprint of the internal structure of the sample surface. Used in
paleontology to study complex fossils, e.g. bryozoan.
- **Source:**
https://strata.uga.edu/cincy/fauna/bryozoanStudy/acetatePeels.html
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/peel



[]{#solidmaterialsample}

##  Solid material sample
- **Alternate labels:**
Solid material specimen
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/solidmaterialsample


[]{#core}

###  Core
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- Cylinder of rock or sediment extracted from within the earth, and
representing the entire sample extracted during a single borehole
drilling event.  Typically using some rotary drilling technology. In
many cases the core is extracted in segments that are 'core sections'.
A core from a single borehole is rarely a continous unbroken object;
commonly parts of the core will break up during drilling or
extraction, leaving gaps or sections that are granular material. Cores
are normally composed of consolidated ('solid') material, but in some
cases loosely consolidated material might be recovered, and considered
sediment or tephra. To be called 'core' the material must be
sufficiently consolidated to maintain a cylindrical shape. A core
hasPart (hasChild) 'Core section'
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/core


[]{#corehalfround}

###  Core half round
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- Half-cylindrical peice of consolidated material produced by along-
axis split of a core whole round along a selected diameter .    Has
childOf relation to core section or core, core section, or Core peice
from which is was split
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/corehalfround


[]{#corepeice}

###  Core peice
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- A cylindrical peice of consolidated earth material extracted as a
single solid object between breaks in recovery of core from a
borehole. has parent core section
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/corepeice


[]{#corequarterround}

###  Core quarter round
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- a partial cylindrical peice of consolidated material created by
along-axis split of a core half round. Has Parent core half round
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/corequarterround


[]{#coresection}

###  Core section
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- Segment of a core representing some interval along the well bore.
Child of Core
- **Source:**
https://www.geosamples.org/vocabularies
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/coresection


[]{#coresubpeice}

###  Core subpeice
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- A peice of consolidated material broken from a core peice. has
Parent core peice or core section
- **Source:**
https://www.geosamples.org/vocabularies
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/coresubpeice


[]{#fiblamella}

###  FIB lamella
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- very thin sheet of solid material milled from a larger sample using
a focused ion beam. Used for TEM analysis.
- **Source:**
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.5-FIB-sections%2C-microtome-slices%2C-atom-probe-tips%2C-TEM-grids, 
this vocabulary, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/fiblamella


[]{#individualsolidcube}

###  Individual solid cube
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- A sample that is a prepared cube of material, intended as a sample
of that material.
- **Source:**
SESAR vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/individualsolidcube


[]{#individualsolidcylinder}

###  Individual solid cylinder
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- A cylindrical peice of consolidated material not obtained by
subsurface drilling.  Cores drilled for paleomagnetic analysis are a
common example. Tree ring cores are another...
- **Source:**
SESAR speciment types, ODM 2
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/individualsolidcylinder


[]{#meteorite}

###  Meteorite
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- A meteorite is a solid object that originates in interplanetary
space and survives passage through an atmosphere to reach the surface
of a planet or moon.
- **Source:**
https://ares.jsc.nasa.gov/meteorite-falls/what-are-meteorites/, 
https://www.iau.org/static/science/scientific_bodies/commissions/f1/meteordefinitions_approved.pdf, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/meteorite


[]{#mineralspecimen}

###  Mineral specimen
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- a solid object consisting of one particular mineral, or several
minerals intended to be representative of one or more of the mineral
species.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mineralspecimen


[]{#mountedsection}

###  Sectioned specimen
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- a thin slice of a solid material that has been mounted on a glass
slide for study
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/mountedsection


[]{#thicksection}

####  Thick section
- Child of:
 [`mountedsection`](#mountedsection)
- Thick sections are like thin sections, but milled to a greater
thickness. Typcially polished on one or both sides and used for fluid
or melt inclusion studies, Raman analyses, and infrared spectroscopy
analyses, and SEM or electron microprobe. The standard thickness for a
fluid inclusion thick section is 50 micrometers, but thick sections
can be made at any thickness.  Thick sections can be attached to a
glass slide, or can be prepared so that they can be removed from their
mount as a stand-alone slice of rock.
- **Source:**
https://viva.pressbooks.pub/analyticalmethodsingeosciences/chapter/2-2-thin-section-and-thick-section-anatomy/
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/thicksection


[]{#thinsection}

####  Thin section
- Child of:
 [`mountedsection`](#mountedsection)
- thin sliver of rock cut from a sample with a diamond saw and ground
optically flat, and then mounted on a glass slide and ground smooth
using progressively finer abrasive grit until the sample is 30 microns
thick.
- **Source:**
 https://en.wikipedia.org/wiki/Thin_section, 
http://vocabulary.odm2.org/specimentype/thinSection/ , 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/thinsection


[]{#polishedthinsection}

#####  Polished thin section
- Child of:
 [`thinsection`](#thinsection)
- a thin section that has its free surface polished until perfectly
planar and free of pits and scratches. Used for reflected light
petrography and for electron microprobe or SEM investigation.
- **Source:**
http://www.minsocam.org/ammin/AM53/AM53_2070.pdf
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/polishedthinsection


[]{#ultrathinsection}

####  Ultra thin section
- Child of:
 [`mountedsection`](#mountedsection)
- An ordinary thin section that is attached to the glass slide using a
soluble cement such as Canada balsam (soluble in ethanol) to allow
both sides to be worked on. The section is polished on both sides
using a fine diamond paste until it has a thickness in the range of
2-12 microns. This technique has been used to study the microstructure
of very fine-grained carbonate rocks, and also in the preparation of
mineral and rock specimens for transmission electron microscopy.
- **Source:**
http://vocabulary.odm2.org/specimentype/thinSection/  | https://en.wikipedia.org/wiki/Thin_section
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/ultrathinsection


[]{#pressedpellet}

###  Pressed pellet
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- a sample prepared by grinding a parent sample to a fine powder,
mixing it with a binder, and pressing the mixture into a die at a
pressure of between 15 and 35 tons to produce a solid disc for
subsequent analysis, typically by X-Ray fluorescence.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/pressedpellet


[]{#rockhandsample}

###  Rock hand sample
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- individual peice of rock broken from an outcrop or larger peice of
rock.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/rockhandsample


[]{#slab}

###  Slab
- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialsample`](#solidmaterialsample)
- a relatively planar rock sample,cut from a large sample to produce a
tabular peice of rock with the irregular outline of the original
sample on the diameter where the cut was mate.
- **Source:**
this vocabulary
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/slab


[]{#uchannelsample}

###  U-channel sample
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- a rectangular prism of loosely consolidated sediment extracted from
a core segment. has parent core piece or core segment
- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/uchannelsample


[]{#atomprobetip}

###  Atom probe tip
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- needle-shaped sample milled out of a larger sample with a focused
ion beam (FIB).
- **Source:**
OSIRIS-Rex Sample types, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.5-FIB-sections%2C-microtome-slices%2C-atom-probe-tips%2C-TEM-grids, 
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/atomprobetip


[]{#chip}

###  Chip
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- Individual solid object intentionally broken off a larger solid
object sample. A Chip must have a documented parent sample.
- **Source:**
OSIRIS-Rex Sample types, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138/SAMIS-JSC+Curation+Interface+Control+Document+ICD#6.1-Particles-and-chips, 
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/chip


[]{#microtomeslice}

###  Microtome slice
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- Typically from TEM analysis. Slices are commonly deposited in a grid
contain with multiple slices and the grid will be given a single
sample name, not the individual slices within it. The provenance of
the slice from paticle to mounted specimen to slice should be
carefully documented
- A very thin slice cut from a mounted specimen using a mocrotome or
ultramicrotome.
- **Source:**
OSIRIS-Rex Sample types, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.5-FIB-sections%2C-microtome-slices%2C-atom-probe-tips%2C-TEM-grids, 
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/microtomeslice


[]{#mountedspecimen}

###  Mounted specimen
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- one or more solid objects embedded in a stabilizing matrix,
typically epoxy, metal, or paraffin to allow slicing through the
mounted object(s).
- **Alternate labels:**
Potted butt
- **Source:**
OSIRIS-Rex Sample types, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.3-Thin-section%2C-thick-section%2C-grain-mounts-(epoxy%2Fmetal-mounts)%2C-and-potted-butts, 
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/mountedspecimen


[]{#polishedmountedspecimen}

####  Polished mounted specimen
- Child of:
 [`mountedspecimen`](#mountedspecimen)
- Mounted specimen with polished surface exposing mounted material for
analysis
- **Alternate labels:**
Grain mount
- **Source:**
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.3-Thin-section%2C-thick-section%2C-grain-mounts-(epoxy%2Fmetal-mounts)%2C-and-potted-butts, 
this vocabulary, 
- Concept URI: https://w3id.org/isample/earthenv/esmaterialsample/polishedmountedspecimen


[]{#particle}

###  Particle
- Child of:
 [`solidmaterialsample`](#solidmaterialsample)
- Can also used for small peices broken from a 'Rock hand sample'.
OSIRIS-Rex definition specifies 'competent individual geologic sample
of any size'. 'Competent' interpreted to be equivalent to 'solid', or
'consolidated'.  The definition here is broader in that it includes
materials of any origin, but narrower in that it is restricted to
small objects.
- A small individual solid object that is not one of the other sample
types.
- **Source:**
OSIRIS-Rex Sample types, 
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138/SAMIS-JSC+Curation+Interface+Control+Document+ICD#6.1-Particles-and-chips, 
- Concept URI: https://w3id.org/isample/vocabulary/materialsampleobjecttype/particle



