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

[]{#EarthandEnvironmentalSciencespecimentypeextension}

# **Concept scheme:** Earth and Environmental Science specimen type extension

Vocabulary last modified:  2023-07-27

subtitle: 
  This concept scheme contains skos concepts for categorizing kinds of Earth Material sample types, extending the iSamples Material Sample Type vocabulary. Defintions from SESAR, ODM2, wikipedia, ESS-DIVE, and other sources; sources are cited with each term.

Namespace: 
[`https://w3id.org/isample/1.0/esmaterialsample/essampletype`](https://w3id.org/isample/1.0/esmaterialsample/essampletype)

**History**

* 2023-07-07 SMR add solid material sample and broader relations from classes it subsumes.
* 2023-07-27 SMR modify base specimen type vocabulary, add 'Non biologic solid object' to replace 'solid material sample', change broader relations in this vocab to use that as parent class where appropriate. 'Solid material sample' is too closely linked to material type, created confusion. Intention is a specimen category for solid objects that are not biologic. Obviously there is some overlap with Research specimens.

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

- [genericAggregation](#genericaggregation)
    - [Boxed core](#boxedcore)
    - [Composite sample](#compositesample)
        - [Chip Channel Sample](#chipchannelsample)
        - [High Grade Sample](#highgradesample)
        - [Site composite sample](#sitecompositesample)
    - [Core Catcher](#corecatcher)
    - [Cuttings](#cuttings)
    - [Dredge](#dredge)
    - [Material Captured in Filter](#materialcapturedinfilter)
    - [Mechanical fraction](#mechanicalfraction)
    - [Mineral separate](#mineralseparate)
        - [Magnetic fraction](#magneticfraction)
        - [Non-magnetic fraction](#nonmagneticfraction)
    - [Natural aggregate specimen](#naturalaggregate)
    - [Prepared powder](#preparedpowder)
        - [Prepared rock powder](#preparedrockpowder)
    - [Trawl](#trawl)
    - [Resonance ionization mass spectrometry](#temgrid)

- [Other solid Object](#othersolidobject)
    - [Dust wipe](#dustwipe)
    - [Glass slide smear](#glassslidesmear)
    - [Peel](#peel)

**Concepts**

[]{#analyticalpreparation}

##  Analytical preparation


- Concept URI token: analyticalpreparation


[]{#cellculture}

###  Cell culture


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`bundlebiomeaggregation`](#bundlebiomeaggregation)

- a collection of cells are grown under controlled conditions,
generally outside of their natural environment

- **Source:**
https://en.wikipedia.org/wiki/Cell_culture

- Concept URI token: cellculture


[]{#dissolvedchemicalfraction}

###  Dissolved chemical fraction


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`fluidincontainer`](#fluidincontainer)

- A fluid concentrating some constituent of interest from a parent
sample. The dissolved constituent is actually the sample material of
interest.

- **Source:**


- Concept URI token: dissolvedchemicalfraction


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

- Concept URI token: eluate


[]{#fiblamella}

###  FIB lamella


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialspecimen`](#solidmaterialspecimen)

- very thin sheet of solid material milled from a larger sample using
a focused ion beam. Used for TEM analysis.

- **Source:**
https://osiris-rex.atlassian.net/wiki/spaces/UTDMP/pages/410288138#6.5-FIB-sections%2C-microtome-slices%2C-atom-probe-tips%2C-TEM-grids, 
this vocabulary, 

- Concept URI token: fiblamella


[]{#glassslidesmear}

###  Glass slide smear


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`othersolidobject`](#othersolidobject)

- sample from a cell culture (or other microparticulate suspension)
spread into a thin layer on a glass slide for optical investigation

- **Source:**
https://pubs.usgs.gov/of/2001/of01-041/htmldocs/methods/sslide.htm

- Concept URI token: glassslidesmear


[]{#individualsolidcube}

###  Individual solid cube


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialspecimen`](#solidmaterialspecimen)

- A sample that is a prepared cube of material, intended as a sample
of that material.

- **Source:**
SESAR vocabulary

- Concept URI token: individualsolidcube


[]{#magneticfraction}

###  Magnetic fraction


- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)

- a collection of particles separated from a crushed rock sample based
on their attraction to a magnet.

- **Source:**
this vocabulary

- Concept URI token: magneticfraction


[]{#mechanicalfraction}

###  Mechanical fraction


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)

- defined by sample preparation involving mechanical processing, e.g.
grain size, density, or grain shape separation.

- **Source:**
this vocabulary

- Concept URI token: mechanicalfraction


[]{#mineralseparate}

###  Mineral separate


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)

- an aggregation of particles of the same mineral extracted and
concentrated from a rock.

- **Source:**
this vocabulary

- Concept URI token: mineralseparate


[]{#magneticfraction}

####  Magnetic fraction


- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)

- a collection of particles separated from a crushed rock sample based
on their attraction to a magnet.

- **Source:**
this vocabulary

- Concept URI token: magneticfraction


[]{#nonmagneticfraction}

####  Non-magnetic fraction


- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)

- collection of particles from a crushed rock sample based on their
lack of attraction to a magnet

- **Source:**
this vocabulary

- Concept URI token: nonmagneticfraction


[]{#mountedsection}

###  Sectioned specimen


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialspecimen`](#solidmaterialspecimen)

- a thin slice of a solid material that has been mounted on a glass
slide for study

- **Source:**
this vocabulary

- Concept URI token: mountedsection


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

- Concept URI token: thicksection


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

- Concept URI token: thinsection


[]{#polishedthinsection}

#####  Polished thin section


- Child of:
 [`thinsection`](#thinsection)

- a thin section that has its free surface polished until perfectly
planar and free of pits and scratches. Used for reflected light
petrography and for electron microprobe or SEM investigation.

- **Source:**
http://www.minsocam.org/ammin/AM53/AM53_2070.pdf

- Concept URI token: polishedthinsection


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

- Concept URI token: ultrathinsection


[]{#nonmagneticfraction}

###  Non-magnetic fraction


- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)

- collection of particles from a crushed rock sample based on their
lack of attraction to a magnet

- **Source:**
this vocabulary

- Concept URI token: nonmagneticfraction


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

- Concept URI token: peel


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

- Concept URI token: preparedpowder


[]{#preparedrockpowder}

####  Prepared rock powder


- Child of:
 [`preparedpowder`](#preparedpowder)

- a powder manufactured by pulverizing a rock.

- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object

- Concept URI token: preparedrockpowder


[]{#pressedpellet}

###  Pressed pellet


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialspecimen`](#solidmaterialspecimen)

- a sample prepared by grinding a parent sample to a fine powder,
mixing it with a binder, and pressing the mixture into a die at a
pressure of between 15 and 35 tons to produce a solid disc for
subsequent analysis, typically by X-Ray fluorescence.

- **Source:**
this vocabulary

- Concept URI token: pressedpellet


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

- Concept URI token: residualmaterial


[]{#slab}

###  Slab


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`solidmaterialspecimen`](#solidmaterialspecimen)

- a relatively planar rock sample,cut from a large sample to produce a
tabular peice of rock with the irregular outline of the original
sample on the diameter where the cut was mate.

- **Source:**
this vocabulary

- Concept URI token: slab



[]{#bundlebiomeaggregation}

##  Bundle biome aggregation


- Concept URI token: bundlebiomeaggregation


[]{#cellculture}

###  Cell culture


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`bundlebiomeaggregation`](#bundlebiomeaggregation)

- a collection of cells are grown under controlled conditions,
generally outside of their natural environment

- **Source:**
https://en.wikipedia.org/wiki/Cell_culture

- Concept URI token: cellculture



[]{#fluidincontainer}

##  Fluid in container


- Concept URI token: fluidincontainer


[]{#directfluidsample}

###  Direct fluid sample


- Child of:
 [`fluidincontainer`](#fluidincontainer)

- a fluid collected from the sampled feature (e.g. water body,
hydrothermal vent, atmosphere...) with no processing. (e.g.
filtration, addition of preservatives).

- **Source:**
this vocabulary

- Concept URI token: directfluidsample


[]{#dissolvedchemicalfraction}

###  Dissolved chemical fraction


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`fluidincontainer`](#fluidincontainer)

- A fluid concentrating some constituent of interest from a parent
sample. The dissolved constituent is actually the sample material of
interest.

- **Source:**


- Concept URI token: dissolvedchemicalfraction


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

- Concept URI token: eluate


[]{#processedfluidsample}

###  Processed fluid sample


- Child of:
 [`fluidincontainer`](#fluidincontainer)

- fluid sample that has been processed in some way during or after
collection, e.g. by filtering, addition of preservatives.

- **Source:**
this vocabulary

- Concept URI token: processedfluidsample


[]{#filtrate}

####  Filtrate


- Child of:
 [`processedfluidsample`](#processedfluidsample)

- A sample that has gone through a filtration process to separate
solids from fluids (liquids or gases), using a filter medium through
which only the fluid can pass. Must be associated with a filter size.

- **Source:**
https://github.com/ess-dive-community/essdive-sample-id-metadata/blob/master/terms/objectType.md

- Concept URI token: filtrate



[]{#genericaggregation}

##  genericAggregation


- Concept URI token: genericaggregation


[]{#boxedcore}

###  Boxed core


- Child of:
 [`genericaggregation`](#genericaggregation)

- A collection of core peices that are stored in an individual box.
Typically the box will contain core peices from the same core.

- **Source:**
this vocabulary

- Concept URI token: boxedcore


[]{#compositesample}

###  Composite sample


- Child of:
 [`genericaggregation`](#genericaggregation)

- a sample composed of multiple peices, representative of some
material, or representative of some site. The peices do not all
originate from the same object.

- **Source:**
this vocabulary

- Concept URI token: compositesample


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

- Concept URI token: chipchannelsample


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

- Concept URI token: highgradesample


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

- Concept URI token: sitecompositesample


[]{#corecatcher}

###  Core Catcher


- Child of:
 [`genericaggregation`](#genericaggregation)

- material recovered from the core catcher of a sedimentary core and
which is treated as a separate section from the core. The core catcher
is a device at the bottom of the core barrel that prevents the core
from sliding out while the barrel is retrieved from the hole.
(http://publications.iodp.org/proceedings/323/102/102_.htm)

- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object

- Concept URI token: corecatcher


[]{#cuttings}

###  Cuttings


- Child of:
 [`genericaggregation`](#genericaggregation)

- unconsolidated Earth material produced by the grinding action of a
drill bit during drilling of a borehole.

- **Source:**
http://vocabulary.odm2.org/specimentype/cuttings/

- Concept URI token: cuttings


[]{#dredge}

###  Dredge


- Child of:
 [`genericaggregation`](#genericaggregation)

- an aggregation of material sampled by dragging a collection bucket
(dredge) across the bottom of a water body

- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object

- Concept URI token: dredge


[]{#materialcapturedinfilter}

###  Material Captured in Filter


- Child of:
 [`genericaggregation`](#genericaggregation)

- A material sample captured in filter, for example from a water
sample that was filtered. Must be associated with filter size field.

- **Source:**
https://github.com/ess-dive-community/essdive-sample-id-metadata/blob/master/terms/objectType.md

- Concept URI token: materialcapturedinfilter


[]{#mechanicalfraction}

###  Mechanical fraction


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)

- defined by sample preparation involving mechanical processing, e.g.
grain size, density, or grain shape separation.

- **Source:**
this vocabulary

- Concept URI token: mechanicalfraction


[]{#mineralseparate}

###  Mineral separate


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`genericaggregation`](#genericaggregation)

- an aggregation of particles of the same mineral extracted and
concentrated from a rock.

- **Source:**
this vocabulary

- Concept URI token: mineralseparate


[]{#magneticfraction}

####  Magnetic fraction


- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)

- a collection of particles separated from a crushed rock sample based
on their attraction to a magnet.

- **Source:**
this vocabulary

- Concept URI token: magneticfraction


[]{#nonmagneticfraction}

####  Non-magnetic fraction


- Child of:
 [`mineralseparate`](#mineralseparate)
 [`analyticalpreparation`](#analyticalpreparation)

- collection of particles from a crushed rock sample based on their
lack of attraction to a magnet

- **Source:**
this vocabulary

- Concept URI token: nonmagneticfraction


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

- Concept URI token: naturalaggregate


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

- Concept URI token: preparedpowder


[]{#preparedrockpowder}

####  Prepared rock powder


- Child of:
 [`preparedpowder`](#preparedpowder)

- a powder manufactured by pulverizing a rock.

- **Source:**
https://www.geosamples.org/vocabularies/sample-type-object

- Concept URI token: preparedrockpowder


[]{#trawl}

###  Trawl


- Child of:
 [`genericaggregation`](#genericaggregation)

- an aggregation of biogenic or non-biogenic material extracted from a
water body

- **Source:**
this vocabulary

- Concept URI token: trawl


[]{#temgrid}

###  Resonance ionization mass spectrometry


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

- Concept URI token: temgrid



[]{#othersolidobject}

##  Other solid Object


- Concept URI token: othersolidobject


[]{#dustwipe}

###  Dust wipe


- Child of:
 [`othersolidobject`](#othersolidobject)

- a pre-weighed and packaged paper towel (wipe) used to wipe over a
surface to collect particulates from the surface

- **Source:**
https://www.cdc.gov/nceh/lead/docs/publications/Environmental_Sampling.pdf, dust wipe sampling

- Concept URI token: dustwipe


[]{#glassslidesmear}

###  Glass slide smear


- Child of:
 [`analyticalpreparation`](#analyticalpreparation)
 [`othersolidobject`](#othersolidobject)

- sample from a cell culture (or other microparticulate suspension)
spread into a thin layer on a glass slide for optical investigation

- **Source:**
https://pubs.usgs.gov/of/2001/of01-041/htmldocs/methods/sslide.htm

- Concept URI token: glassslidesmear


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

- Concept URI token: peel



