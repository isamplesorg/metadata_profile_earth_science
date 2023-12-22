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

[]{#iSamplesrockandsedimentvocabularyextension}

# **Concept scheme:** iSamples rock and sediment vocabulary extension

no modified date

subtitle: 
  Kinds of rock material.
  Rock and sediment categories for iSamples materialType classification. Remove anthropogenic materials and classes for consolidated or non-consolidated material; remove leaf classes subjectively based on abundance of material type and number of subclasses. There are 83 'mat:rock' subclasses; these include some classes that are non-consolidated material (e.g. fault gouge) but these are not sediment and adding 'material' classes that are independent of consolidation seems like more overhead than needed. Note that a given material is likely to fit in more that one class; for example the sediment subclasses include compositional classes (e.g. carbonate, clastic) as well as grain size classes (gravel-size sediment). A calcareous ooze sample would be both 'mud-size sediment' and 'carbonate sediment'.   Change owl:class to skos:concept, and rdfs:subClassOf to skos:broader.

Namespace: 
[`https://w3id.org/isample/vocabulary/rocksediment/0.9/rocksedimentvocabulary`](https://w3id.org/isample/vocabulary/rocksediment/0.9/rocksedimentvocabulary)

**History**


- [Rock](#rock)
    - [aphanite](#aphanite)
    - [breccia](#breccia)
    - [fault_related_material](#fault_related_material)
        - [cataclasite_series](#cataclasite_series)
        - [mylonitic_rock](#mylonitic_rock)
        - [breccia_gouge_series](#breccia_gouge_series)
    - [fragmental_igneous_rock](#fragmental_igneous_rock)
        - [pyroclastic_rock](#pyroclastic_rock)
    - [igneous_rock](#igneous_rock)
        - [acidic_igneous_rock](#acidic_igneous_rock)
            - [dacite](#dacite)
            - [granitoid](#granitoid)
                - [alkali_feldspar_granite](#alkali_feldspar_granite)
                - [granite](#granite)
                - [granodiorite](#granodiorite)
                - [tonalite](#tonalite)
            - [quartz_rich_igneous_rock](#quartz_rich_igneous_rock)
            - [rhyolitoid](#rhyolitoid)
        - [basic_igneous_rock](#basic_igneous_rock)
            - [basalt](#basalt)
            - [gabbroic_rock](#gabbroic_rock)
        - [doleritic_rock](#doleritic_rock)
        - [exotic_composition_igneous_rock](#exotic_composition_igneous_rock)
        - [fine_grained_igneous_rock](#fine_grained_igneous_rock)
            - [andesite](#andesite)
            - [basalt](#basalt)
            - [dacite](#dacite)
            - [foiditoid](#foiditoid)
            - [high_magnesium_fine_grained_igneous_rock](#high_magnesium_fine_grained_igneous_rock)
            - [phonolitoid](#phonolitoid)
            - [rhyolitoid](#rhyolitoid)
            - [tephritoid](#tephritoid)
            - [trachytoid](#trachytoid)
        - [fragmental_igneous_rock](#fragmental_igneous_rock)
            - [pyroclastic_rock](#pyroclastic_rock)
        - [glass_rich_igneous_rock](#glass_rich_igneous_rock)
        - [hypabyssal_intrusive_rock](#hypabyssal_intrusive_rock)
        - [intermediate_composition_igneous_rock](#intermediate_composition_igneous_rock)
            - [andesite](#andesite)
            - [dioritoid](#dioritoid)
        - [phaneritic_igneous_rock](#phaneritic_igneous_rock)
            - [anorthositic_rock](#anorthositic_rock)
            - [aplite](#aplite)
            - [dioritoid](#dioritoid)
            - [foid_dioritoid](#foid_dioritoid)
            - [foid_gabbroid](#foid_gabbroid)
            - [foid_syenitoid](#foid_syenitoid)
            - [foidolite](#foidolite)
            - [gabbroid](#gabbroid)
                - [gabbroic_rock](#gabbroic_rock)
                - [monzogabbroic_rock](#monzogabbroic_rock)
            - [granitoid](#granitoid)
                - [alkali_feldspar_granite](#alkali_feldspar_granite)
                - [granite](#granite)
                - [granodiorite](#granodiorite)
                - [tonalite](#tonalite)
            - [hornblendite](#hornblendite)
            - [pegmatite](#pegmatite)
            - [peridotite](#peridotite)
            - [pyroxenite](#pyroxenite)
            - [quartz_rich_igneous_rock](#quartz_rich_igneous_rock)
            - [syenitoid](#syenitoid)
        - [plutonic_igneous_rock](#plutonic_igneous_rock)
        - [porphyry](#porphyry)
        - [ultrabasic_igneous_rock](#ultrabasic_igneous_rock)
        - [ultramafic_igneous_rock](#ultramafic_igneous_rock)
            - [hornblendite](#hornblendite)
            - [peridotite](#peridotite)
            - [pyroxenite](#pyroxenite)
        - [volcanic rock](#volcanic_rock)
    - [impact_generated_material](#impact_generated_material)
    - [massive_sulphide](#massive_sulphide)
    - [metamorphic_rock](#metamorphic_rock)
    - [metasomatic_rock](#metasomatic_rock)
    - [sedimentary_rock](#sedimentary_rock)
        - [carbonate_sedimentary_rock](#carbonate_sedimentary_rock)
        - [clastic_sedimentary_rock](#clastic_sedimentary_rock)
            - [diamictite](#diamictite)
        - [generic_conglomerate](#generic_conglomerate)
        - [generic_mudstone](#generic_mudstone)
        - [generic_sandstone](#generic_sandstone)
        - [hybrid_sedimentary_rock](#hybrid_sedimentary_rock)
        - [iron_rich_sedimentary_rock](#iron_rich_sedimentary_rock)
        - [non_clastic_siliceous_sedimentary_rock](#non_clastic_siliceous_sedimentary_rock)
        - [organic_rich_sedimentary_rock](#organic_rich_sedimentary_rock)
            - [coal](#coal)
        - [phosphorite](#phosphorite)
    - [tuffite](#tuffite)
    - [residual_material](#residual_material)

- [Sediment](#sediment)
    - [biogenic_sediment](#biogenic_sediment)
    - [carbonate_sediment](#carbonate_sediment)
    - [chemical_sedimentary_material](#chemical_sedimentary_material)
    - [clastic_sediment](#clastic_sediment)
        - [diamicton](#diamicton)
    - [gravel_size_sediment](#gravel_size_sediment)
    - [hybrid_sediment](#hybrid_sediment)
    - [iron_rich_sediment](#iron_rich_sediment)
    - [mud_size_sediment](#mud_size_sediment)
    - [non_clastic_siliceous_sediment](#non_clastic_siliceous_sediment)
    - [phosphate_rich_sediment](#phosphate_rich_sediment)
    - [sand_size_sediment](#sand_size_sediment)
    - [tephra](#tephra)

**Concepts**

[]{#rock}

##  Rock


- Concept URI token: rock


[]{#aphanite}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Aphanite`

- Child of:
 [`rock`](#rock)

- Rock that is too fine grained to categorize in more detail.

- **Source:**
This vocabulary

- Concept URI token: Aphanite


[]{#breccia}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Breccia`

- Child of:
 [`rock`](#rock)

- Coarse-grained material composed of angular broken rock fragments;
the fragments typically have sharp edges and unworn corners. The
fragments may be held together by a mineral cement or in a fine-
grained matrix, and consolidated or nonconsolidated. Clasts may be of
any composition or origin. In sedimentary environments, breccia is
used for material that consists entirely of angular fragments, mostly
derived from a single source rock body, as in a rock avalanche
deposit, and matrix is interpreted to be the product of comminution of
clasts during transport. Diamictite or diamicton is used when the
material reflects mixing of rock from a variety of sources, some sub
angular or subrounded clasts may be present, and matrix is pre-
existing fine grained material that is not a direct product of the
brecciation/deposition process.

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Breccia


[]{#fault_related_material}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Fault_Related_Material`

- Child of:
 [`rock`](#rock)

- Material formed as a result brittle faulting, composed of greater
than 10 percent matrix; matrix is fine-grained material caused by
tectonic grainsize reduction. Includes cohesive (cataclasite series,
mylonitic rocks) and non-cohesive (breccia-gouge series) material.

- **Source:**
This vocabulary; SLTTm 2004

- Concept URI token: Fault_Related_Material


[]{#cataclasite_series}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Cataclasite_Series`

- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)

- Fault-related rock that maintained primary cohesion during
deformation, with matrix comprising greater than 10 percent of rock
mass; matrix is fine-grained material formed through grain size
reduction by fracture as opposed to crystal plastic process that
operate in mylonitic rock. Includes cataclasite, protocataclasite and
ultracataclasite.

- **Source:**
Sibson, 1977; Scholz, 1990; Snoke and Tullis, 1998; Barker, 1998 Appendix II; NADM SLTTm, 2004

- Concept URI token: Cataclasite_Series


[]{#mylonitic_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Mylonitic_Rock`

- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)

- Metamorphic rock characterised by a foliation resulting from
tectonic grain size reduction, in which more than 10 percent of the
rock volume has undergone grain size reduction. Includes
protomylonite, mylonite, ultramylonite, and blastomylonite.

- **Source:**
Marshak and Mitra 1988

- Concept URI token: Mylonitic_Rock


[]{#breccia_gouge_series}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/breccia_gouge_series`

- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)

- Fault-related material with features such as void spaces (filled or
unfilled), or unconsolidated matrix material between fragments,
indicating loss of cohesion during deformation. Includes fault-related
breccia and gouge.

- **Source:**
SLTTm 2004

- Concept URI token: breccia_gouge_series


[]{#fragmental_igneous_rock}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Fragmental_Igneous_Rock`

- Child of:
 [`rock`](#rock)
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock in which greater than 75 percent of the rock consists
of fragments produced as a result of igneous rock-forming process.
Includes pyroclastic rocks, autobreccia associated with lava flows and
intrusive breccias. Excludes deposits reworked by epiclastic processes
(see Tuffite)

- **Source:**
This vocabulary

- Concept URI token: Fragmental_Igneous_Rock


[]{#pyroclastic_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Pyroclastic_Rock`

- Child of:
 [`Fragmental_Igneous_Rock`](#Fragmental_Igneous_Rock)

- Fragmental igneous rock that consists of greater than 75 percent
fragments produced as a direct result of eruption or extrusion of
magma from within the earth onto its surface. Includes autobreccia
associated with lava flows and excludes deposits reworked by
epiclastic processes.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Rock


[]{#igneous_rock}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Igneous_Rock`

- Child of:
 [`rock`](#rock)

- rock formed as a result of igneous processes, for example intrusion
and cooling of magma in the crust, or volcanic eruption.

- **Source:**
Neuendorf et al 2005

- Concept URI token: Igneous_Rock


[]{#acidic_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Acidic_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock with more than 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Acidic_Igneous_Rock


[]{#dacite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Dacite`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine grained or porphyritic crystalline rock that contains less than
90 percent mafic minerals, between 20 and 60 percent quartz in the
QAPF fraction, and has a plagioclase to total feldspar ratio greater
than 0.65. Includes rocks defined modally in QAPF fields 4 and 5 or
chemically in TAS Field O3. Typically composed of quartz and sodic
plagioclase with minor amounts of biotite and/or hornblende and/or
pyroxene; fine-grained equivalent of granodiorite and tonalite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dacite


[]{#granitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Granitoid`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock consisting of quartz, alkali
feldspar and/or plagioclase. Includes rocks defined modally in QAPF
fields 2, 3, 4 and 5 as alkali feldspar granite, granite, granodiorite
or tonalite.

- **Alternate labels:**
granitic rock


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granitoid


[]{#alkali_feldspar_granite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Alkali_Feldspar_Granite`

- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Granite`

- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#granodiorite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Granodiorite`

- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting essentially of quartz, sodic
plagioclase and lesser amounts of alkali feldspar with minor
hornblende and biotite. Includes rocks defined modally in QAPF field
4.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granodiorite


[]{#tonalite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Tonalite`

- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#quartz_rich_igneous_rock}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Quartz_Rich_Igneous_Rock`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Occurrence of igneous rocks meeting this criteria seems to be
vanishingly rare, thus subdividing the category does not seem
warranted for the purposes of This vocabulary. Future usage of the
vocabulary may motivate including quatzolite and quartz-rich granitoid
in future revisions
- Phaneritic crystalline igneous rock that contains less than 90
percent mafic minerals and contains greater than 60 percent quartz in
the QAPF fraction.

- **Source:**
Gillespie and Styles 1999; LeMaitre et al. 2002

- Concept URI token: Quartz_Rich_Igneous_Rock


[]{#rhyolitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Rhyolitoid`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Note that technical definition, based on modal mineralogy plotted in
a QAPF triangle may be applied qualitatively, based on phenocryst
mineralogy when ground mass mineralogy can not be determined
optically, or based on CIPW norm. Although TAS categories are defined
based on chemical analyses, the correspondence with the QAPF defined
categories is generally close enough that QAPF categories are commonly
used interchangeably with TAS categories. It is important to note the
basis for assignment of fine-grained igneous rocks to a specifice
lithology category.
- fine_grained_igneous_rock consisting of quartz and alkali feldspar,
with minor plagioclase and biotite, in a microcrystalline,
cryptocrystalline or glassy groundmass. Flow texture is common.
Includes rocks defined modally in QAPF fields 2 and 3 or chemically in
TAS Field R as rhyolite. QAPF normative definition is based on modal
mineralogy thus: less than 90 percent mafic minerals, between 20 and
60 percent quartz in the QAPF fraction, and ratio of plagioclse to
total feldspar is less than 0.65.

- **Alternate labels:**
rhyolitic rock


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolitoid


[]{#basic_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Basic_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock with between 45 and 52 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Basic_Igneous_Rock


[]{#basalt}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Basalt`

- Child of:
 [`Basic_Igneous_Rock`](#Basic_Igneous_Rock)
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine-grained or porphyritic igneous rock with less than 20 percent
quartz, and less than 10 percent feldspathoid minerals, in which the
ratio of plagioclase to total feldspar is greater 0.65. Typically
composed of calcic plagioclase and clinopyroxene; phenocrysts
typically include one or more of calcic plagioclase, clinopyroxene,
orthopyroxene, and olivine. Includes rocks defined modally in QAPF
fields 9 and 10 or chemically in TAS field B as basalt. Basalt and
andesite are distinguished chemically based on silica content, with
basalt defined to contain less than 52 weight percent silica. If
chemical data are not available, the color index is used to
distinguish the categories, with basalt defined to contain greater
than 35 percent mafic minerals by volume or greater than 40 percent
mafic minerals by weight.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Basalt


[]{#gabbroic_rock}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Gabbroic_Rock`

- Child of:
 [`Basic_Igneous_Rock`](#Basic_Igneous_Rock)
 [`Gabbroid`](#Gabbroid)

- Gabbroid that has a plagioclase to total feldspar ratio greater than
0.9 in the QAPF fraction. Includes QAPF fields 10*, 10, and 10'. This
category includes the various categories defined in LeMaitre et al.
(2002) based on the mafic mineralogy, but apparently not subdivided
based on the quartz/feldspathoid content.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbroic_Rock


[]{#doleritic_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Doleritic_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Dark colored gabbroic (basaltic) or dioritic (andesitic) rock
intermediate in grain size between basalt and gabbro and composed of
plagioclase, pyroxene and opaque minerals; often with ophitic texture.
Typically occurs as hypabyssal intrusions. Includes dolerite,
microdiorite, diabase and microgabbro.

- **Source:**
Neuendorf et al 2005; LeMaitre et al. 2002; Gillespie and Styles 1999

- Concept URI token: Doleritic_Rock


[]{#exotic_composition_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Exotic_Composition_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Rock with 'exotic' mineralogical, textural or field setting
characteristics; typically dark colored, with abundant phenocrysts.
Criteria include: presence of greater than 10 percent melilite or
leucite, or presence of kalsilite, or greater than 50 percent
carbonate minerals. Includes Carbonatite, Melilitic rock, Kalsilitic
rocks, Kimberlite, Lamproite, Leucitic rock and Lamprophyres.

- **Source:**
Gillespie and Styles 1999; LeMaitre et al. 2002

- Concept URI token: Exotic_Composition_Igneous_Rock


[]{#fine_grained_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Fine_Grained_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock in which the framework of the rock consists of crystals
that are too small to determine mineralogy with the unaided eye;
framework may include up to 50 percent glass. A significant percentage
of the rock by volume may be phenocrysts. Includes rocks that are
generally called volcanic rocks.
- Need to make decision as to whether devitrified glass should be
considered glass or microcrystalline framework for purposes of
categorization

- **Alternate labels:**
volcanic rock


- **Source:**
Gillespie and Styles 1999; LeMaitre et al. 2002

- Concept URI token: Fine_Grained_Igneous_Rock


[]{#andesite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Andesite`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)
 [`Intermediate_Composition_Igneous_Rock`](#Intermediate_Composition_Igneous_Rock)

- Fine-grained igneous rock with less than 20 percent quartz and less
than 10 percent feldspathoid minerals in the QAPF fraction, in which
the ratio of plagioclase to total feldspar is greater 0.65. Includes
rocks defined modally in QAPF fields 9 and 10 or chemically in TAS
field O2 as andesite. Basalt and andesite, which share the same QAPF
fields, are distinguished chemically based on silica content, with
basalt defined to contain less than 52 weight percent silica. If
chemical data are not available, the color index is used to
distinguish the categories, with basalt defined to contain greater
than 35 percent mafic minerals by volume or greater than 40 percent
mafic minerals by weight. Typically consists of plagioclase
(frequently zoned from labradorite to oligoclase), pyroxene,
hornblende and/or biotite. Fine grained equivalent of dioritic rock.
- Note the mela-andesite and leuco-basalt categories are not
recommended in this system. If chemical analytical data are available
to constrain the silica content, the basalt or andesite category
should be used.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Andesite


[]{#basalt}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Basalt`

- Child of:
 [`Basic_Igneous_Rock`](#Basic_Igneous_Rock)
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine-grained or porphyritic igneous rock with less than 20 percent
quartz, and less than 10 percent feldspathoid minerals, in which the
ratio of plagioclase to total feldspar is greater 0.65. Typically
composed of calcic plagioclase and clinopyroxene; phenocrysts
typically include one or more of calcic plagioclase, clinopyroxene,
orthopyroxene, and olivine. Includes rocks defined modally in QAPF
fields 9 and 10 or chemically in TAS field B as basalt. Basalt and
andesite are distinguished chemically based on silica content, with
basalt defined to contain less than 52 weight percent silica. If
chemical data are not available, the color index is used to
distinguish the categories, with basalt defined to contain greater
than 35 percent mafic minerals by volume or greater than 40 percent
mafic minerals by weight.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Basalt


[]{#dacite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Dacite`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine grained or porphyritic crystalline rock that contains less than
90 percent mafic minerals, between 20 and 60 percent quartz in the
QAPF fraction, and has a plagioclase to total feldspar ratio greater
than 0.65. Includes rocks defined modally in QAPF fields 4 and 5 or
chemically in TAS Field O3. Typically composed of quartz and sodic
plagioclase with minor amounts of biotite and/or hornblende and/or
pyroxene; fine-grained equivalent of granodiorite and tonalite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dacite


[]{#foiditoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Foiditoid`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine grained crystalline rock containing less than 90 percent mafic
minerals and more than 60 percent feldspathoid minerals in the QAPF
fraction. Includes rocks defined modally in QAPF field 15 or
chemically in TAS field F.

- **Alternate labels:**
foidite (sensu lato), 
foiditic rock, 


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foiditoid


[]{#high_magnesium_fine_grained_igneous_rock}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/High_Magnesium_Fine_Grained_Igneous_Rock`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- fine-grained igneous rock that contains unusually high concentration
of MgO. For rocks that contain greater than 52 percent silica, MgO
must be greater than 8 percent. For rocks containing less than 52
percent silica, MgO must be greater than 12 percent.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: High_Magnesium_Fine_Grained_Igneous_Rock


[]{#phonolitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Phonolitoid`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine grained igneous rock than contains less than 90 percent mafic
minerals, between 10 and 60 percent feldspathoid mineral in the QAPF
fraction and has a plagioclase to total feldspar ratio less than 0.5.
Includes rocks defined modally in QAPF fields 11 and 12, and TAS field
Ph.

- **Alternate labels:**
phonolitic rock


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitoid


[]{#rhyolitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Rhyolitoid`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Note that technical definition, based on modal mineralogy plotted in
a QAPF triangle may be applied qualitatively, based on phenocryst
mineralogy when ground mass mineralogy can not be determined
optically, or based on CIPW norm. Although TAS categories are defined
based on chemical analyses, the correspondence with the QAPF defined
categories is generally close enough that QAPF categories are commonly
used interchangeably with TAS categories. It is important to note the
basis for assignment of fine-grained igneous rocks to a specifice
lithology category.
- fine_grained_igneous_rock consisting of quartz and alkali feldspar,
with minor plagioclase and biotite, in a microcrystalline,
cryptocrystalline or glassy groundmass. Flow texture is common.
Includes rocks defined modally in QAPF fields 2 and 3 or chemically in
TAS Field R as rhyolite. QAPF normative definition is based on modal
mineralogy thus: less than 90 percent mafic minerals, between 20 and
60 percent quartz in the QAPF fraction, and ratio of plagioclse to
total feldspar is less than 0.65.

- **Alternate labels:**
rhyolitic rock


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolitoid


[]{#tephritoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Tephritoid`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine grained igneous rock than contains less than 90 percent mafic
minerals, between 10 and 60 percent feldspathoid mineral in the QAPF
fraction and has a plagioclase to total feldspar ratio greater than
0.5. Includes rocks classified in QAPF field 13 and 14 or chemically
in TAS field U1 as basanite or tephrite.

- **Alternate labels:**
tephritic rock


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephritoid


[]{#trachytoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Trachytoid`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- Fine grained igneous rock than contains less than 90 percent mafic
minerals, less than 10 percent feldspathoid mineral and less than 20
percent quartz in the QAPF fraction and has a plagioclase to total
feldspar ratio less than 0.65. Mafic minerals typically include
amphibole or mica; typically porphyritic. Includes rocks defined
modally in QAPF fields 6, 7 and 8 (with subdivisions) or chemically in
TAS Field T as trachyte or latite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Trachytoid


[]{#fragmental_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Fragmental_Igneous_Rock`

- Child of:
 [`rock`](#rock)
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock in which greater than 75 percent of the rock consists
of fragments produced as a result of igneous rock-forming process.
Includes pyroclastic rocks, autobreccia associated with lava flows and
intrusive breccias. Excludes deposits reworked by epiclastic processes
(see Tuffite)

- **Source:**
This vocabulary

- Concept URI token: Fragmental_Igneous_Rock


[]{#pyroclastic_rock}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Pyroclastic_Rock`

- Child of:
 [`Fragmental_Igneous_Rock`](#Fragmental_Igneous_Rock)

- Fragmental igneous rock that consists of greater than 75 percent
fragments produced as a direct result of eruption or extrusion of
magma from within the earth onto its surface. Includes autobreccia
associated with lava flows and excludes deposits reworked by
epiclastic processes.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Rock


[]{#glass_rich_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Glass_Rich_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that contains greater than 50 percent massive glass.

- **Source:**
This vocabulary, based on Gillespie and Styles 1999

- Concept URI token: Glass_Rich_Igneous_Rock


[]{#hypabyssal_intrusive_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Hypabyssal_Intrusive_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rocks formed by crystallisation close to the Earth's
surface, characterized by more rapid cooling than plutonic setting to
produce generally fine-grained intrusive igneous rock, commonly
associated with co-magmatic volcanic rocks.

- **Source:**
This vocabulary

- Concept URI token: Hypabyssal_Intrusive_Rock


[]{#intermediate_composition_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Intermediate_Composition_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock with between 52 and 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Intermediate_Composition_Igneous_Rock


[]{#andesite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Andesite`

- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)
 [`Intermediate_Composition_Igneous_Rock`](#Intermediate_Composition_Igneous_Rock)

- Fine-grained igneous rock with less than 20 percent quartz and less
than 10 percent feldspathoid minerals in the QAPF fraction, in which
the ratio of plagioclase to total feldspar is greater 0.65. Includes
rocks defined modally in QAPF fields 9 and 10 or chemically in TAS
field O2 as andesite. Basalt and andesite, which share the same QAPF
fields, are distinguished chemically based on silica content, with
basalt defined to contain less than 52 weight percent silica. If
chemical data are not available, the color index is used to
distinguish the categories, with basalt defined to contain greater
than 35 percent mafic minerals by volume or greater than 40 percent
mafic minerals by weight. Typically consists of plagioclase
(frequently zoned from labradorite to oligoclase), pyroxene,
hornblende and/or biotite. Fine grained equivalent of dioritic rock.
- Note the mela-andesite and leuco-basalt categories are not
recommended in this system. If chemical analytical data are available
to constrain the silica content, the basalt or andesite category
should be used.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Andesite


[]{#dioritoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Dioritoid`

- Child of:
 [`Intermediate_Composition_Igneous_Rock`](#Intermediate_Composition_Igneous_Rock)
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock with M less than 90, consisting
of intermediate plagioclase, commonly with hornblende and often with
biotite or augite. Plagioclase to total feldspar ratio is greater that
0.65, and anorthite content of plagioclase is less than 50 percent.
Less than 10 percent feldspathoid mineral and less than 20 percent
quartz in the QAPF fraction. Includes rocks defined modally in QAPF
fields 9 and 10 (and their subdivisions).

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritoid


[]{#phaneritic_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Phaneritic_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock in which the framework of the rock consists of
individual crystals that can be discerned with the unaided eye.
Bounding grain size is on the order of 32 to 100 microns. Igneous
rocks with 'exotic' composition are excluded from this concept.

- **Alternate labels:**
coarse grained crystalline igneous rock, 
plutonic rock, 


- **Source:**
Neuendorf et al. 2005

- Concept URI token: Phaneritic_Igneous_Rock


[]{#anorthositic_rock}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Anorthositic_Rock`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Anorthositic rock term invented to label the combined QAPF fields
10, 10*, and 10', in order to construct hierarchy in this vocabulary.
- Leucocratic phaneritic crystalline igneous rock consisting
essentially of plagioclase, often with small amounts of pyroxene. By
definition, colour index M is less than 10, and plagiclase to total
feldspar ratio is greater than 0.9. Less than 20 percent quartz and
less than 10 percent feldspathoid in the QAPF fraction. QAPF field 10,
10*, and 10'.

- **Source:**
LeMaitre et al. 2002; This vocabulary

- Concept URI token: Anorthositic_Rock


[]{#aplite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Aplite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Light coloured crystalline rock, characterized by a fine grained
allotriomorphic-granular (aplitic, saccharoidal or xenomorphic)
texture; typically granitic composition, consisting of quartz, alkali
feldspar and sodic plagioclase.

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Aplite


[]{#dioritoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Dioritoid`

- Child of:
 [`Intermediate_Composition_Igneous_Rock`](#Intermediate_Composition_Igneous_Rock)
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock with M less than 90, consisting
of intermediate plagioclase, commonly with hornblende and often with
biotite or augite. Plagioclase to total feldspar ratio is greater that
0.65, and anorthite content of plagioclase is less than 50 percent.
Less than 10 percent feldspathoid mineral and less than 20 percent
quartz in the QAPF fraction. Includes rocks defined modally in QAPF
fields 9 and 10 (and their subdivisions).

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritoid


[]{#foid_dioritoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Foid_Dioritoid`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock in which M is less than 90, the
plagioclase to total feldspar ratio is greater than 0.5, feldspathoid
minerals form 10-60 percent of the QAPF fraction, plagioclase has
anorthite content less than 50 percent. These rocks typically contain
large amounts of mafic minerals. Includes rocks defined modally in
QAPF fields 13 and 14.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Dioritoid


[]{#foid_gabbroid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Foid_Gabbroid`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock in which M is less than 90, the
plagioclase to total feldspar ratio is greater than 0.5, feldspathoids
form 10-60 percent of the QAPF fraction, and plagioclase has anorthite
content greater than 50 percent. These rocks typically contain large
amounts of mafic minerals. Includes rocks defined modally in QAPF
fields 13 and 14.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Gabbroid


[]{#foid_syenitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Foid_Syenitoid`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock with M less than 90, contains
between 10 and 60 percent feldspathoid mineral in the QAPF fraction,
and has a plagioclase to total feldspar ratio less than 0.5. Includes
QAPF fields 11 and 12.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Syenitoid


[]{#foidolite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Foidolite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline rock containing more than 60 percent
feldspathoid minerals in the QAPF fraction. Includes rocks defined
modally in QAPF field 15

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foidolite


[]{#gabbroid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Gabbroid`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock that contains less than 90
percent mafic minerals, and up to 20 percent quartz or up to 10
percent feldspathoid in the QAPF fraction. The ratio of plagioclase to
total feldspar is greater than 0.65, and anorthite content of the
plagioclase is greater than 50 percent. Includes rocks defined modally
in QAPF fields 9 and 10 and their subdivisions.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbroid


[]{#gabbroic_rock}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Gabbroic_Rock`

- Child of:
 [`Basic_Igneous_Rock`](#Basic_Igneous_Rock)
 [`Gabbroid`](#Gabbroid)

- Gabbroid that has a plagioclase to total feldspar ratio greater than
0.9 in the QAPF fraction. Includes QAPF fields 10*, 10, and 10'. This
category includes the various categories defined in LeMaitre et al.
(2002) based on the mafic mineralogy, but apparently not subdivided
based on the quartz/feldspathoid content.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbroic_Rock


[]{#monzogabbroic_rock}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Monzogabbroic_Rock`

- Child of:
 [`Gabbroid`](#Gabbroid)

- Gabbroid with a plagioclase to total feldspar ratio between 0.65 and
0.9. QAPF field 9, 9 prime and 9 asterisk

- **Source:**
LeMaitre et al. 2002, This vocabulary

- Concept URI token: Monzogabbroic_Rock


[]{#granitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Granitoid`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock consisting of quartz, alkali
feldspar and/or plagioclase. Includes rocks defined modally in QAPF
fields 2, 3, 4 and 5 as alkali feldspar granite, granite, granodiorite
or tonalite.

- **Alternate labels:**
granitic rock


- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granitoid


[]{#alkali_feldspar_granite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Alkali_Feldspar_Granite`

- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Granite`

- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#granodiorite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Granodiorite`

- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting essentially of quartz, sodic
plagioclase and lesser amounts of alkali feldspar with minor
hornblende and biotite. Includes rocks defined modally in QAPF field
4.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granodiorite


[]{#tonalite}

######  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Tonalite`

- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#hornblendite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Hornblendite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic rock that consists of greater than 40 percent hornblende
plus pyroxene and has a hornblende to pyroxene ratio greater than 1.
Includes olivine hornblendite, olivine-pyroxene hornblendite, pyroxene
hornblendite, and hornblendite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Hornblendite


[]{#pegmatite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Pegmatite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Exceptionally coarse grained crystalline rock with interlocking
crystals; most grains are 1cm or more diameter; composition is
generally that of granite, but the term may refer to the coarse
grained facies of any type of igneous rock;usually found as irregular
dikes, lenses, or veins associated with plutons or batholiths.

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Pegmatite


[]{#peridotite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Peridotite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic rock consisting of more than 40 percent (by volume)
olivine with pyroxene and/or amphibole and little or no feldspar.
commonly altered to serpentinite. Includes rocks defined modally in
the ultramafic rock classification as dunite, harzburgite, lherzolite,
wehrlite, olivinite, pyroxene peridotite, pyroxene hornblende
peridotite or hornblende peridotite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Peridotite


[]{#pyroxenite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Pyroxenite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic phaneritic igneous rock composed almost entirely of one
or more pyroxenes and occasionally biotite, hornblende and olivine.
Includes rocks defined modally in the ultramafic rock classification
as olivine pyroxenite, olivine-hornblende pyroxenite, pyroxenite,
orthopyroxenite, clinopyroxenite and websterite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Pyroxenite


[]{#quartz_rich_igneous_rock}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Quartz_Rich_Igneous_Rock`

- Child of:
 [`Acidic_Igneous_Rock`](#Acidic_Igneous_Rock)
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Occurrence of igneous rocks meeting this criteria seems to be
vanishingly rare, thus subdividing the category does not seem
warranted for the purposes of This vocabulary. Future usage of the
vocabulary may motivate including quatzolite and quartz-rich granitoid
in future revisions
- Phaneritic crystalline igneous rock that contains less than 90
percent mafic minerals and contains greater than 60 percent quartz in
the QAPF fraction.

- **Source:**
Gillespie and Styles 1999; LeMaitre et al. 2002

- Concept URI token: Quartz_Rich_Igneous_Rock


[]{#syenitoid}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Syenitoid`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock with M less than 90, consisting
mainly of alkali feldspar and plagioclase; minor quartz or nepheline
may be present, along with pyroxene, amphibole or biotite. Ratio of
plagioclase to total feldspar is less than 0.65, quartz forms less
than 20 percent of QAPF fraction, and feldspathoid minerals form less
than 10 percent of QAPF fraction. Includes rocks classified in QAPF
fields 6, 7 and 8 and their subdivisions.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenitoid


[]{#plutonic_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Plutonic_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Instrusive igneous rock formed by crystallisation of magma far
enough below Earth surface that complete crystallization of magma
bodies forms holocrystalline medium to coarse grained igneous rock,
wall rocks generally do not include volcanic products related to the
magma, and some contact metamorphism is tyypically developed at
intrusive contacts.

- **Source:**
This vocabulary

- Concept URI token: Plutonic_Igneous_Rock


[]{#porphyry}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Porphyry`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that contains conspicuous phenocrysts in a finer
grained groundmass; groundmass itself may be phaneritic or fine-
grained.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Porphyry


[]{#ultrabasic_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Ultrabasic_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock with less than 45 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Ultrabasic_Igneous_Rock


[]{#ultramafic_igneous_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Ultramafic_Igneous_Rock`

- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that consists of greater than 90 percent mafic
minerals.

- **Source:**
LeMaitre et al. 2002; Gillespie and Styles 1999

- Concept URI token: Ultramafic_Igneous_Rock


[]{#hornblendite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Hornblendite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic rock that consists of greater than 40 percent hornblende
plus pyroxene and has a hornblende to pyroxene ratio greater than 1.
Includes olivine hornblendite, olivine-pyroxene hornblendite, pyroxene
hornblendite, and hornblendite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Hornblendite


[]{#peridotite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Peridotite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic rock consisting of more than 40 percent (by volume)
olivine with pyroxene and/or amphibole and little or no feldspar.
commonly altered to serpentinite. Includes rocks defined modally in
the ultramafic rock classification as dunite, harzburgite, lherzolite,
wehrlite, olivinite, pyroxene peridotite, pyroxene hornblende
peridotite or hornblende peridotite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Peridotite


[]{#pyroxenite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Pyroxenite`

- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic phaneritic igneous rock composed almost entirely of one
or more pyroxenes and occasionally biotite, hornblende and olivine.
Includes rocks defined modally in the ultramafic rock classification
as olivine pyroxenite, olivine-hornblende pyroxenite, pyroxenite,
orthopyroxenite, clinopyroxenite and websterite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Pyroxenite


[]{#volcanic_rock}

####  volcanic rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Rock that exhibits direct evidence of extrusive igneous processes in
its genesis.
- Concept URI token: Volcanic_Rock


[]{#impact_generated_material}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Impact_Generated_Material`

- Child of:
 [`rock`](#rock)

- Material that contains features indicative of shock metamorphism,
such as microscopic planar deformation features within grains or
shatter cones, interpreted to be the result of extraterrestrial bolide
impact. Includes breccias and melt rocks.

- **Source:**
Stöffler and Grieve 2007; Jackson 1997

- Concept URI token: Impact_Generated_Material


[]{#massive_sulphide}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Massive_Sulphide`

- Child of:
 [`rock`](#rock)

- rock consisting of greater than 50% sulphide or sulfosalt minerals
formed by any processes. Includes hydrothermal and sedimentary
ehalative sulfide.

- **Alternate labels:**
Massive Sulfide


- **Source:**
Provisional SMR 2020-06-07

- Concept URI token: Massive_Sulphide


[]{#metamorphic_rock}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Metamorphic_Rock`

- Child of:
 [`rock`](#rock)

- Robertson (1999, Classification of metamorphic rocks: British
Geological Survey Research Report, RR 99–02) defines the boundary
between diagenesis and metamorphism in sedimentary rocks as follows:
“…the boundary between diagenesis and metamorphism is somewhat
arbitrary and strongly dependent on the lithologies involved. For
example changes take place in organic materials at lower temperatures
than in rocks dominated by silicate minerals. In mudrocks, a white
mica (illite) crystallinity value of less than 0.42 Delta 2 Theta
obtained by X-ray diffraction analysis, is used to define the onset of
metamorphism (Kisch, 1991). In this scheme, the first appearance of
glaucophane, lawsonite, paragonite, prehnite, pumpellyite or
stilpnomelane is taken to indicate the lower limit of metamorphism
(Frey and Kisch, 1987; Bucher and Frey, 1994; Frey and Robinson,
1998). Most workers agree that such mineral growth starts at 150 +/-
50° C in silicate rocks. Many lithologies may show no change in
mineralogy under these conditions and hence the recognition of the
onset of metamorphism will vary with bulk composition.”
- Rock formed by solid-state mineralogical, chemical and/or structural
changes to a pre-existing rock, in response to marked changes in
temperature, pressure, shearing stress and chemical environment.

- **Source:**
Jackson 1997

- Concept URI token: Metamorphic_Rock


[]{#metasomatic_rock}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Metasomatic_Rock`

- Child of:
 [`rock`](#rock)

- Rock that has fabric and composition indicating open-system
mineralogical and chemical changes in response to interaction with a
fluid phase, typically water rich.
- SLTTm (2004) proposed the following criteria to distinguish
hydrothermally altered or metasomatic rock from igneous rock. "The
rock is classified as metamorphic if (1) the texture has been modified
such that it can no longer be considered igneous, (2) the bulk
composition of the rock is inconsistent with compositions that can be
derived purely from a magma and associated processes such as
assimilation and differentiation, or (3) minerals inconsistent with
magmatic crystallization are present."

- **Source:**
This vocabulary

- Concept URI token: Metasomatic_Rock


[]{#sedimentary_rock}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Sedimentary_Rock`

- Child of:
 [`rock`](#rock)

- Rock formed by accumulation and cementation of solid fragmental
material deposited by air, water or ice, or as a result of other
natural agents, such as precipitation from solution, the accumulation
of organic material, or from biogenic processes, including secretion
by organisms. Includes epiclastic deposits.

- **Source:**
SLTTs 2004

- Concept URI token: Sedimentary_Rock


[]{#carbonate_sedimentary_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Carbonate_Sedimentary_Rock`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Particularly for fine-grained sedimentary rocks, distinction of
'intrabasinal' versus 'clastic' genesis can be very interpretive. In
practice the use of clastic mudstone terminology as opposed to
carbonate mudstone terminology may be dermined by a priori knowledge
about the rock being categorized. If it is associated with other
clastic rocks, the clastic categories will be favored, if with
cabonate rocks, the carbonate categories will be favored. Carbonate
rock subcatgories are defined on two orthogonal dimensions--mineralogy
(calcitic vs. dolomitic vs non-carbonate impurities), and texture. The
texture categories used here are those of Dunham (1962), and involve
grain size (matrix vs. grains/allochems), fabric (matrix vs. grain
supported), and genesis (bound, frame, or fragmental). The textural
approach used for carbonate rocks is conceptually incompatible with
that used for clastic sedimentary rocks, which is solely grain size or
mineralogy based. This leads to problems in the vocabulary for rocks
of mixed siliclastic/carbonate mineralogy (grainstone vs. sandstone,
carbonate mudstone vs. carbonate rich mudstone, how to accomodate
marlstone...).
- Sedimentary rock in which at least 50 percent of the primary and/or
recrystallized constituents are composed of one (or more) of the
carbonate minerals calcite, aragonite, magnesite or dolomite.

- **Source:**
SLTTs 2004

- Concept URI token: Carbonate_Sedimentary_Rock


[]{#clastic_sedimentary_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Clastic_Sedimentary_Rock`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock in which at least 50 percent of the constituent
particles were derived from erosion, weathering, or mass-wasting of
pre-existing earth materials, and transported to the place of
deposition by mechanical agents such as water, wind, ice and gravity.
- The conglomerate, sandstone, mudstone, and wackestone categories are
not defined as kinds of clastic sedimentary rocks because rocks
meeting their purely grainsize based definitions might also be iron-
rich, phosphatic, or carbonate. This is based on GeoSciML allowance to
assign rocks to more than one lithology category. For example to
categorize a rock as a clastic conglomerate requires assignment ot the
'clastic sedimentary rock' category and to the 'conglomerate'
category. Particularly for fine-grained sedimentary rocks, distinction
of 'intrabasinal' versus 'clastic' genesis can be very interpretive.
In practice the use of clastic mudstone terminology as opposed to
carbonate mudstone terminology may be dermined by a priori knowledge
about the rock being categorized. If it is associated with other
clastic rocks, the clastic categories will be favored, if with
cabonate rocks, the carbonate categories will be favored.

- **Source:**
SLTTs 2004; Neuendorf et al. 2005

- Concept URI token: Clastic_Sedimentary_Rock


[]{#diamictite}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Diamictite`

- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)

- Unsorted or poorly sorted, clastic sedimentary rock with a wide
range of particle sizes including a muddy matrix. Biogenic materials
that have such texture are excluded. Distinguished from conglomerate,
sandstone, mudstone based on polymodality and lack of structures
related to transport and deposition of sediment by moving air or
water. If more than 10 percent of the fine grained matrix is of
indeterminant clastic or diagenetic origin and the fabric is matrix
supported, may also be categorized as wacke.

- **Source:**
Fairbridge and Bourgeois 1978

- Concept URI token: Diamictite


[]{#generic_conglomerate}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Generic_Conglomerate`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock composed of at least 30 percent rounded to
subangular fragments larger than 2 mm in diameter; typically contains
finer grained material in interstices between larger fragments. If
more than 15 percent of the fine grained matrix is of indeterminant
clastic or diagenetic origin and the fabric is matrix supported, may
also be categorized as wackestone. If rock has unsorted or poorly
sorted texture with a wide range of particle sizes, may also be
categorized as diamictite.

- **Source:**
Neuendorf et al. 2005; SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Generic_Conglomerate


[]{#generic_mudstone}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Generic_Mudstone`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Distinction of intrabasinal, diagenetic, or clastic genesis for very
fine-grained carbonate minerals is so interpretive that it is proposed
to not define the mudstone category based on intrabasinal vs
epiclastic distinction required for clastic sedimentary rock-carbonate
sedimentary rock categorization in this system. Schnurrenberger, D.,
Russell, J. and Kelts, K., 2003, Classification of lacustrine
sediments based on sedimentary components: Journal of Paleolimnology,
v.29, p141-154.
- Sedimentary rock consisting of less than 30 percent gravel-size (2
mm) particles and with a mud to sand ratio greater than 1. Clasts may
be of any composition or origin.

- **Source:**
Pettijohn et al. 1987 referenced in Hallsworth and Knox 1999; extrapolated from Folk, 1954, Figure 1a; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Generic_Mudstone


[]{#generic_sandstone}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Generic_Sandstone`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock in which less than 30 percent of particles are
greater than 2 mm in diameter (gravel) and the sand to mud ratio is at
least 1.

- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Generic_Sandstone


[]{#hybrid_sedimentary_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Hybrid_Sedimentary_Rock`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock that does not fit any of the other
composition/genesis categories. Sedimentary rock consisting of three
or more components which form more than 5 percent but less than 50
precent of the material.

- **Source:**
Hallsworth and Knox, 1999

- Concept URI token: Hybrid_Sedimentary_Rock


[]{#iron_rich_sedimentary_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Iron_Rich_Sedimentary_Rock`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock that consists of at least 50 percent iron-bearing
minerals (hematite, magnetite, limonite-group, siderite, iron-
sulfides), as determined by hand-lens or petrographic analysis.
Corresponds to a rock typically containing 15 percent iron by weight.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Iron_Rich_Sedimentary_Rock


[]{#non_clastic_siliceous_sedimentary_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Non_Clastic_Siliceous_Sedimentary_Rock`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Definition updated to include chert, flint SMR 2020-09-21
- Sedimentary rock that consists of at least 50 percent silicate
mineral material, deposited directly by chemical or biological
processes at the depositional surface, in particles formed by chemical
or biological processes within the basin of deposition, or formed by
diagenetic processes. Includes chert and flint found in carbonate
rocks.

- **Source:**
modified from SLTTs 2004

- Concept URI token: Non_Clastic_Siliceous_Sedimentary_Rock


[]{#organic_rich_sedimentary_rock}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Organic_Rich_Sedimentary_Rock`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sapropelic coal, and asphaltite are not differentiated in This
vocabulary
- Sedimentary rock with color, composition, texture and apparent
density indicating greater than 50 percent organic content by weight
on a moisture-free basis.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sedimentary_Rock


[]{#coal}

#####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Coal`

- Child of:
 [`Organic_Rich_Sedimentary_Rock`](#Organic_Rich_Sedimentary_Rock)

- A consolidated organic sedimentary material having less than 75%
moisture. This category includes low, medium, and high rank coals
according to International Classification of In-Seam Coal (United
Nations, 1998), thus including lignite. Sapropelic coal is not
distinguished in this category from humic coals. Formed from the
compaction or induration of variously altered plant remains similar to
those of peaty deposits.

- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp.

- Concept URI token: Coal


[]{#phosphorite}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Phosphorite`

- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock in which at least 50 percent of the primary or
recrystallized constituents are phosphate minerals. Most commonly
occurs as a bedded primary or reworked secondary marine rock, composed
of microcrystalline carbonate fluorapatite in the form of lamina,
pellets, oolites and nodules, and skeletal, shell and bone fragments.

- **Source:**
HallsworthandKnox 1999, Jackson 1997

- Concept URI token: Phosphorite


[]{#tuffite}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Tuffite`

- Child of:
 [`rock`](#rock)

- In practice, it is likely that any rock for which there is suspicion
that it may consist of redeposited pyroclastic material, usually based
on sedimentary structures, irrespective of the presence or percentage
of clearly epiclastic particles, would be called a tuffite. 50 percent
cutoff with epiclastic rock is in contrast with LeMaitre et al., but
is used for consistentency with other sedimentary rock categories
following the pattern that the rock name reflects the predominant
constituent.
- Rock consists of more than 50 percent particles of indeterminate
pyroclastic or epiclastic origin and less than 75 percent particles of
clearly pyroclastic origin. commonly the rock is laminated or exhibits
size grading. (based on LeMaitre et al. 2002; Murawski and Meyer
1998).
- synonym: volcaniclastic rock

- **Source:**
LeMaitre et al. 2002; Murawski and Meyer 1998

- Concept URI token: Tuffite


[]{#residual_material}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/residual_material`

- Child of:
 [`rock`](#rock)

- Material of composite origin resulting from weathering processes at
the Earth's surface, with genesis dominated by removal of chemical
constituents by aqueous leaching. Minor clastic, chemical, or organic
input may also contribute. Consolidation state is not inherent in
definition, but typically material is unconsolidated or weakly
consolidated.

- **Source:**
This vocabulary

- Concept URI token: residual_material



[]{#sediment}

##  Sediment


- Concept URI token: sediment


[]{#biogenic_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Biogenic_Sediment`

- Child of:
 [`sediment`](#sediment)

- Corresponding biogenic sedimentary material and biogenic sedimentary
rock categories are not included based on the interpretation that
biogenic sedimentary rock will be in a different category, e.g.
carbonate sedimentary rock or organic rich sedimentary rock.
- Sediment composed of greater than 50 percent material of biogenic
origin. Because the biogenic material may be skeletal remains that are
not organic, all biogenic sediment is not necessarily organic-rich.

- **Source:**
SLTTs 2004

- Concept URI token: Biogenic_Sediment


[]{#carbonate_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Carbonate_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment in which at least 50 percent of the primary and/or
recrystallized constituents are composed of one (or more) of the
carbonate minerals calcite, aragonite and dolomite, in particles of
intrabasinal origin.

- **Source:**
SLTTs 2004

- Concept URI token: Carbonate_Sediment


[]{#chemical_sedimentary_material}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Chemical_Sedimentary_Material`

- Child of:
 [`sediment`](#sediment)

- Sedimentary material that consists of at least 50 percent material
produced by inorganic chemical processes within the basin of
deposition. Includes inorganic siliceous, carbonate, evaporite, iron-
rich, and phosphatic sediment classes, as well as chemical sediments
associated with submarine hot springs ('black smokers'). Note that
these sediments might crystallize as a solid as they are deposited,
thus similar to rock....

- **Source:**
SLTTs 2004

- Concept URI token: Chemical_Sedimentary_Material


[]{#clastic_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Clastic_Sediment`

- Child of:
 [`sediment`](#sediment)

- Choice of 'clastic' is purposful. Other suggested labels for this
category include siliciclastic and terrigineous clastic. Siliciclastic
is considered too limiting because the category includes rocks that
consists clasts of carbonate minerals, e.g. epiclastic detritus eroded
from carbonate rock. Terrigineous clastic was considered and rejected
first because it is considered redundant, anything that is
terrigineous is clastic. Second, it is questionable if clastic
sediment derived by submarine processes (fragementation by gravity
sliding, faulting, or volcanic activity, with transport by sediment
gravity flow or submarine currents) is terrigineous, but it is clastic
and is meant to be included in this category.
- Sediment in which at least 50 percent of the constituent particles
were derived from erosion, weathering, or mass-wasting of pre-existing
earth materials, and transported to the place of deposition by
mechanical agents such as water, wind, ice and gravity.

- **Source:**
SLTTs 2004; Neuendorf et al. 2005

- Concept URI token: Clastic_Sediment


[]{#diamicton}

####  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Diamicton`

- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)

- Unsorted or poorly sorted, clastic sediment with a wide range of
particle sizes, including a muddy matrix. Biogenic materials that have
such texture are excluded. Distinguished from conglomerate, sandstone,
mudstone based on polymodality and lack of structures related to
transport and deposition of sediment by moving air or water.
Assignment to an other size class can be used in conjunction to
indicate the dominant grain size.
- definition amplified to help distinguish diamicton, conglomerate and
wackestone in this version

- **Source:**
Fairbridge and Bourgeois 1978

- Concept URI token: Diamicton


[]{#gravel_size_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Gravel_Size_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment containing greater than 30 percent gravel-size particles
(greater than 2.0 mm diameter). Composition or gensis of clasts not
specified.

- **Source:**
SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel_Size_Sediment


[]{#hybrid_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Hybrid_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment that does not fit any of the other sediment
composition/genesis categories. Sediment consisting of three or more
components which form more than 5 percent but less than 50 precent of
the material.

- **Source:**
Hallsworth and Knox, 1999

- Concept URI token: Hybrid_Sediment


[]{#iron_rich_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Iron_Rich_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment that consists of at least 50 percent iron-bearing minerals
(hematite, magnetite, limonite-group, siderite, iron-sulfides), as
determined by hand-lens or petrographic analysis. Corresponds to a
rock typically containing 15 percent iron by weight.

- **Source:**
SLTTs 2004

- Concept URI token: Iron_Rich_Sediment


[]{#mud_size_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Mud_Size_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment consisting of less than 30 percent gravel-size (2 mm)
particles and with a mud-size to sand-size particle ratio greater than
1. Clasts may be of any composition or origin.  BGS  (Hallsworth and
Knox, 1999, p. 9) define the  'upper size limit of mud ... at 32
micrometers (.032 mm)', but Wentworth scale and Krumbein scale put
boundary at .064 or .062 mm (inidistinguishable difference in
rocks...) BGS 'mud-grade sediment' or sedimentary rock definition is
'over 75% of the clasts smaller than  .032 mm', which is narrower than
the definition here.

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud_Size_Sediment


[]{#non_clastic_siliceous_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Non_Clastic_Siliceous_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment that consists of at least 50 percent silicate mineral
material, deposited directly by chemical or biological processes at
the depositional surface, or in particles formed by chemical or
biological processes within the basin of deposition.

- **Source:**
NGMDB 2008; Hallsworth and Knox 1999

- Concept URI token: Non_Clastic_Siliceous_Sediment


[]{#phosphate_rich_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Phosphate_Rich_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment in which at least 50 percent of the primary and/or
recrystallized constituents are phosphate minerals.

- **Source:**
SLTTs 2004

- Concept URI token: Phosphate_Rich_Sediment


[]{#sand_size_sediment}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Sand_Size_Sediment`

- Child of:
 [`sediment`](#sediment)

- Sediment in which less than 30 percent of particles are gravel
(greater than 2 mm in diameter) and the sand to mud ratio is at least
1. composition or genesis of clasts not specified.

- **Source:**
Neuendorf et al. 2005 ; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand_Size_Sediment


[]{#tephra}

###  `https://w3id.org/isample/vocabulary/rocksediment/0.9/Tephra`

- Child of:
 [`sediment`](#sediment)

- Unconsolidated pyroclastic material in which greater than 75 percent
of the fragments are deposited as a direct result of volcanic
processes and the deposit has not been reworked by epiclastic
processes. Includes ash, lapilli tephra, bomb tephra, block tephra and
unconsolidated agglomerate.

- **Source:**
Hallsworth and Knox 1999; LeMaitre et al. 2002

- Concept URI token: Tephra



