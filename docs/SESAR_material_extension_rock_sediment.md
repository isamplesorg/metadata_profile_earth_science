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

[]{#SESAR-Rockandsedimentmaterialsvocabulary}

# **Concept scheme:** SESAR - Rock and sediment materials vocabulary

Vocabulary last modified:  2024-08-19

subtitle: 
  Rock and sediment categories for SESAR materialType classification. Extends the iSamples Earth and Environment rock and sediment extension, which extends the base iSamples Material Type vocabulary.

Namespace: 
[`https://w3id.org/sesar/rocksediment/0.1/rocksedimentvocabulary`](https://w3id.org/sesar/rocksediment/0.1/rocksedimentvocabulary)

**History**

* 2024-08-19 SMR generate vocabulary by merging with GSO Rock_Material vocabulary .

- [Rock Material](#rock_material)
    - [rock](#rock)
        - [Aphanite](#aphanite)
        - [Igneous rock](#igneous_rock)
            - [acidic igneous rock](#acidic_igneous_rock)
                - [dacite](#dacite)
                - [granitoid](#granitoid)
                    - [alkali feldspar granite](#alkali_feldspar_granite)
                    - [granite](#granite)
                        - [monzogranite](#monzogranite)
                        - [syenogranite](#syenogranite)
                    - [granodiorite](#granodiorite)
                    - [tonalite](#tonalite)
                - [quartz rich igneous rock](#quartz_rich_igneous_rock)
                - [rhyolitoid](#rhyolitoid)
                    - [alkali feldspar rhyolite](#alkali_feldspar_rhyolite)
                    - [rhyolite](#rhyolite)
            - [basic igneous rock](#basic_igneous_rock)
                - [basalt](#basalt)
                    - [alkali olivine basalt](#alkali-olivine_basalt)
                    - [tholeiitic basalt](#tholeiitic_basalt)
                - [gabbroic rock](#gabbroic_rock)
                    - [foid bearing gabbro](#foid_bearing_gabbro)
                    - [gabbro](#gabbro)
                    - [quartz gabbro](#quartz_gabbro)
            - [exotic composition igneous rock](#exotic_composition_igneous_rock)
                - [carbonatite](#carbonatite)
                - [exotic alkaline rock](#exotic_alkaline_rock)
                - [kalsilitic and melilitic rocks](#kalsilitic_and_melilitic_rock)
            - [fine grained igneous rock](#fine_grained_igneous_rock)
                - [andesite](#andesite)
                    - [boninite](#boninite)
                - [basalt](#basalt)
                    - [alkali olivine basalt](#alkali-olivine_basalt)
                    - [tholeiitic basalt](#tholeiitic_basalt)
                - [dacite](#dacite)
                - [foiditoid](#foiditoid)
                    - [basanitic foidite](#basanitic_foidite)
                    - [foidite](#foidite)
                    - [phonolitic foidite](#phonolitic_foidite)
                    - [tephritic foidite](#tephritic_foidite)
                - [high magnesium fine grained igneous rock](#high_magnesium_fine_grained_igneous_rock)
                    - [boninite](#boninite)
                    - [komatiitic rock](#komatiitic_rock)
                - [phonolitoid](#phonolitoid)
                    - [phonolite](#phonolilte)
                    - [tephritic phonolite](#tephritic_phonolite)
                - [rhyolitoid](#rhyolitoid)
                    - [alkali feldspar rhyolite](#alkali_feldspar_rhyolite)
                    - [rhyolite](#rhyolite)
                - [tephritoid](#tephritoid)
                    - [basanite](#basanite)
                    - [phonolitic basanite](#phonolitic_basanite)
                    - [phonolitic tephrite](#phonolitic_tephrite)
                    - [tephrite](#tephrite)
                - [trachytoid](#trachytoid)
                    - [alkali feldspar trachytic rock](#alkali_feldspar_trachytic_rock)
                        - [alkali feldspar trachyte](#alkali_feldspar_trachyte)
                        - [foid bearing alkali feldspar trachyte](#foid_bearing_alkali_feldspar_trachyte)
                        - [quartz alkali feldspar trachyte](#quartz_alkali_feldspar_trachyte)
                    - [latitic rock](#latitic_rock)
                        - [foid bearing latite](#foid_bearing_latite)
                        - [latite](#latite)
                        - [quartz latite](#quartz_latite)
                    - [trachytic rock](#trachytic_rock)
                        - [foid bearing trachyte](#foid_bearing_trachyte)
                        - [quartz trachyte](#quartz_trachyte)
                        - [trachyte](#trachyte)
            - [fragmental igneous rock](#fragmental_igneous_rock)
            - [glass rich igneous rock](#glass_rich_igneous_rock)
                - [glassy igneous rock](#glassy_igneous_rock)
            - [hypabyssal intrusive rock](#hypabyssal_intrusive_rock)
            - [intermediate composition igneous rock](#intermediate_composition_igneous_rock)
                - [andesite](#andesite)
                    - [boninite](#boninite)
                - [dioritoid](#dioritoid)
                    - [dioritic rock](#dioritic_rock)
                        - [diorite](#diorite)
                        - [foid bearing diorite](#foid_bearing_diorite)
                        - [quartz diorite](#quartz_diorite)
                    - [monzodioritic rock](#monzodioritic_rock)
                        - [foid bearing monzodiorite](#foid_bearing_monzodiorite)
                        - [monzodiorite](#monzodiorite)
                        - [quartz monzodiorite](#quartz_monzodiorite)
            - [phaneritic igneous rock](#phaneritic_igneous_rock)
                - [anorthositic rock](#anorthositic_rock)
                    - [anorthosite](#anorthosite)
                    - [foid bearing anorthosite](#foid_bearing_anorthosite)
                    - [quartz anorthosite](#quartz_anorthosite)
                - [aplite](#aplite)
                - [dioritoid](#dioritoid)
                    - [dioritic rock](#dioritic_rock)
                        - [diorite](#diorite)
                        - [foid bearing diorite](#foid_bearing_diorite)
                        - [quartz diorite](#quartz_diorite)
                    - [monzodioritic rock](#monzodioritic_rock)
                        - [foid bearing monzodiorite](#foid_bearing_monzodiorite)
                        - [monzodiorite](#monzodiorite)
                        - [quartz monzodiorite](#quartz_monzodiorite)
                - [foid dioritoid](#foid_dioritoid)
                    - [foid diorite](#foid_diorite)
                    - [foid monzodiorite](#foid_monzodiorite)
                - [foid gabbroid](#foid_gabbroid)
                    - [foid gabbro](#foid_gabbro)
                    - [foid monzogabbro](#foid_monzogabbro)
                - [foid syenitoid](#foid_syenitoid)
                    - [foid monzosyenite](#foid_monzosyenite)
                    - [foid syenite](#foid_syenite)
                - [foidolite](#foidolite)
                - [gabbroid](#gabbroid)
                    - [gabbroic rock](#gabbroic_rock)
                        - [foid bearing gabbro](#foid_bearing_gabbro)
                        - [gabbro](#gabbro)
                        - [quartz gabbro](#quartz_gabbro)
                    - [monzogabbroic rock](#monzogabbroic_rock)
                        - [foid bearing monzogabbro](#foid_bearing_monzogabbro)
                        - [monzogabbro](#monzogabbro)
                        - [quartz monzogabbro](#quartz_monzogabbro)
                - [granitoid](#granitoid)
                    - [alkali feldspar granite](#alkali_feldspar_granite)
                    - [granite](#granite)
                        - [monzogranite](#monzogranite)
                        - [syenogranite](#syenogranite)
                    - [granodiorite](#granodiorite)
                    - [tonalite](#tonalite)
                - [hornblendite](#hornblendite)
                - [pegmatite](#pegmatite)
                - [peridotite](#peridotite)
                - [pyroxenite](#pyroxenite)
                - [quartz rich igneous rock](#quartz_rich_igneous_rock)
                - [syenitoid](#syenitoid)
                    - [alkali feldspar syenitic rock](#alkali_feldspar_syenitic_rock)
                        - [alkali feldspar syenite](#alkali_feldspar_syenite)
                        - [foid bearing alkali feldspar syenite](#foid_bearing_alkali_feldspar_syenite)
                        - [quartz alkali feldspar syenite](#quartz_alkali_feldspar_syenite)
                    - [monzonitic rock](#monzonitic_rock)
                        - [foid bearing monzonite](#foid_bearing_monzonite)
                        - [monzonite](#monzonite)
                        - [quartz monzonite](#quartz_monzonite)
                    - [syenitic rock](#syenitic_rock)
                        - [foid bearing syenite](#foid_bearing_syenite)
                        - [quartz syenite](#quartz_syenite)
                        - [syenite](#syenite)
            - [plutonic rock](#plutonic_igneous_rock)
            - [porphyry](#porphyry)
            - [ultrabasic igneous rock](#ultrabasic_igneous_rock)
            - [ultramafic igneous rock](#ultramafic_igneous_rock)
                - [hornblendite](#hornblendite)
                - [peridotite](#peridotite)
                - [pyroxenite](#pyroxenite)
                - [komatiitic rock](#komatiitic_rock)
        - [Massive sulphide](#massive_sulphide)
            - [Hydrothermal Massive Sulphide](#hydrothermal_massive_sulphide)
            - [Sedimentary Massive Sulphide](#sedimentary_massive_sulphide)
        - [Sedimentary rock](#sedimentary_rock)
            - [carbonate sedimentary rock](#carbonate_sedimentary_rock)
                - [boundstone](#boundstone)
                - [calcareous carbonate sedimentary rock](#calcareous_carbonate_sedimentary_rock)
                    - [impure limestone](#impure_limestone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
                - [carbonate mudstone](#carbonate_mudstone)
                - [carbonate wackestone](#carbonate_wackestone)
                - [crystalline carbonate](#crystalline_carbonate)
                - [dolomitic or magnesian sedimentary rock](#dolomitic_or_magnesian_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [impure dolomite](#impure_dolostone)
                - [framestone](#framestone)
                - [grainstone](#grainstone)
                - [impure carbonate sedimentary rock](#impure_carbonate_sedimentary_rock)
                    - [impure dolomite](#impure_dolostone)
                    - [impure limestone](#impure_limestone)
                - [packstone](#packstone)
                - [pure carbonate sedimentary rock](#pure_carbonate_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
                    - [pure carbonate mudstone](#pure_carbonate_mudstone)
            - [clastic sedimentary rock](#clastic_sedimentary_rock)
                - [diamictite](#diamictite)
                - [conglomerate](#clastic_conglomerate)
                - [mudstone](#clastic_mudstone)
                    - [claystone](#claystone)
                    - [shale](#shale)
                    - [siltstone](#siltstone)
                - [sandstone](#clastic_sandstone)
                    - [arenit](#arenite)
                    - [piedra](#wacke)
            - [generic conglomerate](#generic_conglomerate)
                - [conglomerate](#clastic_conglomerate)
            - [generic mudstone](#generic_mudstone)
                - [carbonate mudstone](#carbonate_mudstone)
                - [carbonate rich mudstone](#carbonate_rich_mudstone)
                - [mudstone](#clastic_mudstone)
                    - [claystone](#claystone)
                    - [shale](#shale)
                    - [siltstone](#siltstone)
                - [organic bearing mudstone](#organic_bearing_mudstone)
                - [pure carbonate mudstone](#pure_carbonate_mudstone)
                - [silicate mudstone](#silicate_mudstone)
            - [Generic sandstone](#generic_sandstone)
                - [sandstone](#clastic_sandstone)
                    - [arenit](#arenite)
                    - [piedra](#wacke)
            - [hybrid sedimentary rock](#hybrid_sedimentary_rock)
            - [iron rich sedimentary rock](#iron_rich_sedimentary_rock)
            - [non clastic siliceous sedimentary rock](#non_clastic_siliceous_sedimentary_rock)
                - [biogenic silica sedimentary rock](#biogenic_silica_sedimentary_rock)
            - [organic rich sedimentary rock](#organic_rich_sedimentary_rock)
                - [coal](#coal)
                    - [anthracite](#anthracite_coal)
                    - [bituminous coal](#bituminous_coal)
                    - [lignite](#lignite)
            - [phosphorite](#phosphorite)
        - [Tuffite](#tuffite)
        - [Composite genesis rock](#composite_genesis_rock)
            - [cataclasite series](#cataclasite_series)
            - [Metamorphic rock](#metamorphic_rock)
                - [amphibolite](#amphibolite)
                - [Argillite ](#argillite)
                - [calc silicate metamorphic rock](#calcsilicate_metamorphic_rock)
                - [chlorite actinolite epidote metamorphic rock](#chlorite_actinolite_epidote_metamorphic_rock)
                - [eclogite](#eclogite)
                - [foliated metamorphic rock](#foliated_metamorphic_rock)
                    - [mylonitic rock](#mylonitic_rock)
                        - [phyllonite](#phyllonite)
                    - [gneiss](#gneiss)
                        - [orthogneiss](#orthogneiss)
                        - [paragneiss](#paragneiss)
                    - [phyllite](#phyllite)
                    - [schist](#schist)
                        - [mica schist](#mica_schist)
                    - [slate](#slate)
                - [glaucophane lawsonite epidote metamorphic rock](#glaucophane_lawsonite_epidote_metamorphic_rock)
                - [granofels](#granofels)
                    - [hornfels](#hornfels)
                - [granulite](#granulite)
                - [marble](#marble)
                - [metaplutonic rock](#metaplutonic_rock)
                - [metasedimentary rock](#metasedimentary_rock)
                - [metavolcanic rock](#metavolcanic_rock)
                - [migmatite](#migmatite)
                - [quartzite](#quartzite)
                - [serpentinite](#serpentinite)
            - [metasomatic rock](#metasomatic_rock)
                - [Hydrothermal Massive Sulphide](#hydrothermal_massive_sulphide)
                - [skarn](#skarn)
                - [spilite](#spilite)
                - [Altered, type not specified ](#altered_rock)
                    - [advanced argillic altered rock](#advanced_argillic_altered_rock)
                    - [albitic altered rock](#albitic_altered_rock)
                    - [alunitic altered rock](#alunitic_altered_rock)
                    - [argillic altered rock](#argillic_altered_rock)
                    - [calcsilicate altered rock](#calcsilicate_altered_rock)
                    - [carbonate altered rock](#carbonate_altered_rock)
                    - [chloritic altered rock](#chloritic_altered_rock)
                    - [deuteric altered rock](#deuteric_altered_rock)
                    - [epidote altered rock](#epidote_altered_rock)
                    - [greisen](#greisen)
                    - [hematitic altered rock](#hematitic_altered_rock)
                    - [kaolinitic altered rock](#kaolinitic_altered_rock)
                    - [phyllic altered rock](#phyllic_altered_rock)
                    - [potassic altered rock](#potassic_altered_rock)
                    - [propylitic altered rock](#propylitic_altered_rock)
                    - [pyritic altered rock](#pyritic_altered_rock)
                    - [red rock altered rock](#red_rock_altered_rock)
                    - [saussuritised rock](#saussuritised_rock)
                    - [sericitic altered rock](#sericitic_altered_rock)
                    - [serpentinised rock](#serpentinised_rock)
                    - [silicificed rock](#silicified_rock)
                    - [uralitised rock](#uralitised_rock)
                    - [zeolitic altered rock](#zeolitic_altered_rock)
            - [Duricrust](#duricrust)
    - [Anthropogenic material](#anthropogenic_material)
        - [Anthropogenic unconsolidated material](#anthropogenic_unconsolidated_material)
    - [Breccia](#breccia)
    - [Composite genesis material](#composite_genesis_material)
        - [Fault related material](#fault_related_material)
            - [cataclasite series](#cataclasite_series)
            - [mylonitic rock](#mylonitic_rock)
                - [phyllonite](#phyllonite)
            - [breccia gouge series](#breccia_gouge_series)
        - [Impact generated material](#impact_generated_material)
        - [material formed in surficial environment](#material_formed_in_surficial_environment)
            - [residual material](#residual_material)
            - [Duricrust](#duricrust)
            - [bauxite](#bauxite)
    - [Igneous material](#igneous_material)
        - [Igneous rock](#igneous_rock)
            - [acidic igneous rock](#acidic_igneous_rock)
                - [dacite](#dacite)
                - [granitoid](#granitoid)
                    - [alkali feldspar granite](#alkali_feldspar_granite)
                    - [granite](#granite)
                        - [monzogranite](#monzogranite)
                        - [syenogranite](#syenogranite)
                    - [granodiorite](#granodiorite)
                    - [tonalite](#tonalite)
                - [quartz rich igneous rock](#quartz_rich_igneous_rock)
                - [rhyolitoid](#rhyolitoid)
                    - [alkali feldspar rhyolite](#alkali_feldspar_rhyolite)
                    - [rhyolite](#rhyolite)
            - [basic igneous rock](#basic_igneous_rock)
                - [basalt](#basalt)
                    - [alkali olivine basalt](#alkali-olivine_basalt)
                    - [tholeiitic basalt](#tholeiitic_basalt)
                - [gabbroic rock](#gabbroic_rock)
                    - [foid bearing gabbro](#foid_bearing_gabbro)
                    - [gabbro](#gabbro)
                    - [quartz gabbro](#quartz_gabbro)
            - [exotic composition igneous rock](#exotic_composition_igneous_rock)
                - [carbonatite](#carbonatite)
                - [exotic alkaline rock](#exotic_alkaline_rock)
                - [kalsilitic and melilitic rocks](#kalsilitic_and_melilitic_rock)
            - [fine grained igneous rock](#fine_grained_igneous_rock)
                - [andesite](#andesite)
                    - [boninite](#boninite)
                - [basalt](#basalt)
                    - [alkali olivine basalt](#alkali-olivine_basalt)
                    - [tholeiitic basalt](#tholeiitic_basalt)
                - [dacite](#dacite)
                - [foiditoid](#foiditoid)
                    - [basanitic foidite](#basanitic_foidite)
                    - [foidite](#foidite)
                    - [phonolitic foidite](#phonolitic_foidite)
                    - [tephritic foidite](#tephritic_foidite)
                - [high magnesium fine grained igneous rock](#high_magnesium_fine_grained_igneous_rock)
                    - [boninite](#boninite)
                    - [komatiitic rock](#komatiitic_rock)
                - [phonolitoid](#phonolitoid)
                    - [phonolite](#phonolilte)
                    - [tephritic phonolite](#tephritic_phonolite)
                - [rhyolitoid](#rhyolitoid)
                    - [alkali feldspar rhyolite](#alkali_feldspar_rhyolite)
                    - [rhyolite](#rhyolite)
                - [tephritoid](#tephritoid)
                    - [basanite](#basanite)
                    - [phonolitic basanite](#phonolitic_basanite)
                    - [phonolitic tephrite](#phonolitic_tephrite)
                    - [tephrite](#tephrite)
                - [trachytoid](#trachytoid)
                    - [alkali feldspar trachytic rock](#alkali_feldspar_trachytic_rock)
                        - [alkali feldspar trachyte](#alkali_feldspar_trachyte)
                        - [foid bearing alkali feldspar trachyte](#foid_bearing_alkali_feldspar_trachyte)
                        - [quartz alkali feldspar trachyte](#quartz_alkali_feldspar_trachyte)
                    - [latitic rock](#latitic_rock)
                        - [foid bearing latite](#foid_bearing_latite)
                        - [latite](#latite)
                        - [quartz latite](#quartz_latite)
                    - [trachytic rock](#trachytic_rock)
                        - [foid bearing trachyte](#foid_bearing_trachyte)
                        - [quartz trachyte](#quartz_trachyte)
                        - [trachyte](#trachyte)
            - [fragmental igneous rock](#fragmental_igneous_rock)
            - [glass rich igneous rock](#glass_rich_igneous_rock)
                - [glassy igneous rock](#glassy_igneous_rock)
            - [hypabyssal intrusive rock](#hypabyssal_intrusive_rock)
            - [intermediate composition igneous rock](#intermediate_composition_igneous_rock)
                - [andesite](#andesite)
                    - [boninite](#boninite)
                - [dioritoid](#dioritoid)
                    - [dioritic rock](#dioritic_rock)
                        - [diorite](#diorite)
                        - [foid bearing diorite](#foid_bearing_diorite)
                        - [quartz diorite](#quartz_diorite)
                    - [monzodioritic rock](#monzodioritic_rock)
                        - [foid bearing monzodiorite](#foid_bearing_monzodiorite)
                        - [monzodiorite](#monzodiorite)
                        - [quartz monzodiorite](#quartz_monzodiorite)
            - [phaneritic igneous rock](#phaneritic_igneous_rock)
                - [anorthositic rock](#anorthositic_rock)
                    - [anorthosite](#anorthosite)
                    - [foid bearing anorthosite](#foid_bearing_anorthosite)
                    - [quartz anorthosite](#quartz_anorthosite)
                - [aplite](#aplite)
                - [dioritoid](#dioritoid)
                    - [dioritic rock](#dioritic_rock)
                        - [diorite](#diorite)
                        - [foid bearing diorite](#foid_bearing_diorite)
                        - [quartz diorite](#quartz_diorite)
                    - [monzodioritic rock](#monzodioritic_rock)
                        - [foid bearing monzodiorite](#foid_bearing_monzodiorite)
                        - [monzodiorite](#monzodiorite)
                        - [quartz monzodiorite](#quartz_monzodiorite)
                - [foid dioritoid](#foid_dioritoid)
                    - [foid diorite](#foid_diorite)
                    - [foid monzodiorite](#foid_monzodiorite)
                - [foid gabbroid](#foid_gabbroid)
                    - [foid gabbro](#foid_gabbro)
                    - [foid monzogabbro](#foid_monzogabbro)
                - [foid syenitoid](#foid_syenitoid)
                    - [foid monzosyenite](#foid_monzosyenite)
                    - [foid syenite](#foid_syenite)
                - [foidolite](#foidolite)
                - [gabbroid](#gabbroid)
                    - [gabbroic rock](#gabbroic_rock)
                        - [foid bearing gabbro](#foid_bearing_gabbro)
                        - [gabbro](#gabbro)
                        - [quartz gabbro](#quartz_gabbro)
                    - [monzogabbroic rock](#monzogabbroic_rock)
                        - [foid bearing monzogabbro](#foid_bearing_monzogabbro)
                        - [monzogabbro](#monzogabbro)
                        - [quartz monzogabbro](#quartz_monzogabbro)
                - [granitoid](#granitoid)
                    - [alkali feldspar granite](#alkali_feldspar_granite)
                    - [granite](#granite)
                        - [monzogranite](#monzogranite)
                        - [syenogranite](#syenogranite)
                    - [granodiorite](#granodiorite)
                    - [tonalite](#tonalite)
                - [hornblendite](#hornblendite)
                - [pegmatite](#pegmatite)
                - [peridotite](#peridotite)
                - [pyroxenite](#pyroxenite)
                - [quartz rich igneous rock](#quartz_rich_igneous_rock)
                - [syenitoid](#syenitoid)
                    - [alkali feldspar syenitic rock](#alkali_feldspar_syenitic_rock)
                        - [alkali feldspar syenite](#alkali_feldspar_syenite)
                        - [foid bearing alkali feldspar syenite](#foid_bearing_alkali_feldspar_syenite)
                        - [quartz alkali feldspar syenite](#quartz_alkali_feldspar_syenite)
                    - [monzonitic rock](#monzonitic_rock)
                        - [foid bearing monzonite](#foid_bearing_monzonite)
                        - [monzonite](#monzonite)
                        - [quartz monzonite](#quartz_monzonite)
                    - [syenitic rock](#syenitic_rock)
                        - [foid bearing syenite](#foid_bearing_syenite)
                        - [quartz syenite](#quartz_syenite)
                        - [syenite](#syenite)
            - [plutonic rock](#plutonic_igneous_rock)
            - [porphyry](#porphyry)
            - [ultrabasic igneous rock](#ultrabasic_igneous_rock)
            - [ultramafic igneous rock](#ultramafic_igneous_rock)
                - [hornblendite](#hornblendite)
                - [peridotite](#peridotite)
                - [pyroxenite](#pyroxenite)
                - [komatiitic rock](#komatiitic_rock)
        - [acidic igneous material](#acidic_igneous_material)
            - [acidic igneous rock](#acidic_igneous_rock)
                - [dacite](#dacite)
                - [granitoid](#granitoid)
                    - [alkali feldspar granite](#alkali_feldspar_granite)
                    - [granite](#granite)
                        - [monzogranite](#monzogranite)
                        - [syenogranite](#syenogranite)
                    - [granodiorite](#granodiorite)
                    - [tonalite](#tonalite)
                - [quartz rich igneous rock](#quartz_rich_igneous_rock)
                - [rhyolitoid](#rhyolitoid)
                    - [alkali feldspar rhyolite](#alkali_feldspar_rhyolite)
                    - [rhyolite](#rhyolite)
        - [basic igneous material](#basic_igneous_material)
            - [basic igneous rock](#basic_igneous_rock)
                - [basalt](#basalt)
                    - [alkali olivine basalt](#alkali-olivine_basalt)
                    - [tholeiitic basalt](#tholeiitic_basalt)
                - [gabbroic rock](#gabbroic_rock)
                    - [foid bearing gabbro](#foid_bearing_gabbro)
                    - [gabbro](#gabbro)
                    - [quartz gabbro](#quartz_gabbro)
        - [fragmental igneous material](#fragmental_igneous_material)
            - [fragmental igneous rock](#fragmental_igneous_rock)
            - [pyroclastic material](#pyroclastic_material)
                - [pyroclastic rock](#pyroclastic_rock)
                    - [ash tuff lapillistone and lapilli tuff](#ash_tuff_lapillistone_and_lapilli_tuff)
                    - [tuff breccia agglomerate or pyroclastic breccia](#tuff_breccia_agglomerate_or_pyroclastic_breccia)
                - [Tephra](#tephra)
                    - [ash and lapilli](#ash_and_lapilli)
                    - [ash breccia bomb or block tephra](#ash_breccia_bomb_or_block_tephra)
        - [intermediate composition igneous material](#intermediate_composition_igneous_material)
            - [intermediate composition igneous rock](#intermediate_composition_igneous_rock)
                - [andesite](#andesite)
                    - [boninite](#boninite)
                - [dioritoid](#dioritoid)
                    - [dioritic rock](#dioritic_rock)
                        - [diorite](#diorite)
                        - [foid bearing diorite](#foid_bearing_diorite)
                        - [quartz diorite](#quartz_diorite)
                    - [monzodioritic rock](#monzodioritic_rock)
                        - [foid bearing monzodiorite](#foid_bearing_monzodiorite)
                        - [monzodiorite](#monzodiorite)
                        - [quartz monzodiorite](#quartz_monzodiorite)
        - [Volcanic Material ](#volcanic_material)
            - [volcanic rock ](#volcanic_rock)
                - [pyroclastic rock](#pyroclastic_rock)
                    - [ash tuff lapillistone and lapilli tuff](#ash_tuff_lapillistone_and_lapilli_tuff)
                    - [tuff breccia agglomerate or pyroclastic breccia](#tuff_breccia_agglomerate_or_pyroclastic_breccia)
                - [Lava ](#lava)
            - [pyroclastic material](#pyroclastic_material)
                - [pyroclastic rock](#pyroclastic_rock)
                    - [ash tuff lapillistone and lapilli tuff](#ash_tuff_lapillistone_and_lapilli_tuff)
                    - [tuff breccia agglomerate or pyroclastic breccia](#tuff_breccia_agglomerate_or_pyroclastic_breccia)
                - [Tephra](#tephra)
                    - [ash and lapilli](#ash_and_lapilli)
                    - [ash breccia bomb or block tephra](#ash_breccia_bomb_or_block_tephra)
    - [Sedimentary material](#sedimentary_material)
        - [chemical sedimentary material](#chemical_sedimentary_material)
            - [evaporite](#evaporite)
                - [exotic evaporite](#exotic_evaporite)
                - [gypsum or anhydrite](#rock_gypsum_or_anhydrite)
                - [rock salt](#rock_salt)
            - [iron rich sedimentary material](#iron_rich_sedimentary_material)
                - [iron rich sediment](#iron_rich_sediment)
                - [iron rich sedimentary rock](#iron_rich_sedimentary_rock)
            - [Sedimentary Massive Sulphide](#sedimentary_massive_sulphide)
            - [travertine](#travertine)
        - [Sedimentary rock](#sedimentary_rock)
            - [carbonate sedimentary rock](#carbonate_sedimentary_rock)
                - [boundstone](#boundstone)
                - [calcareous carbonate sedimentary rock](#calcareous_carbonate_sedimentary_rock)
                    - [impure limestone](#impure_limestone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
                - [carbonate mudstone](#carbonate_mudstone)
                - [carbonate wackestone](#carbonate_wackestone)
                - [crystalline carbonate](#crystalline_carbonate)
                - [dolomitic or magnesian sedimentary rock](#dolomitic_or_magnesian_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [impure dolomite](#impure_dolostone)
                - [framestone](#framestone)
                - [grainstone](#grainstone)
                - [impure carbonate sedimentary rock](#impure_carbonate_sedimentary_rock)
                    - [impure dolomite](#impure_dolostone)
                    - [impure limestone](#impure_limestone)
                - [packstone](#packstone)
                - [pure carbonate sedimentary rock](#pure_carbonate_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
                    - [pure carbonate mudstone](#pure_carbonate_mudstone)
            - [clastic sedimentary rock](#clastic_sedimentary_rock)
                - [diamictite](#diamictite)
                - [conglomerate](#clastic_conglomerate)
                - [mudstone](#clastic_mudstone)
                    - [claystone](#claystone)
                    - [shale](#shale)
                    - [siltstone](#siltstone)
                - [sandstone](#clastic_sandstone)
                    - [arenit](#arenite)
                    - [piedra](#wacke)
            - [generic conglomerate](#generic_conglomerate)
                - [conglomerate](#clastic_conglomerate)
            - [generic mudstone](#generic_mudstone)
                - [carbonate mudstone](#carbonate_mudstone)
                - [carbonate rich mudstone](#carbonate_rich_mudstone)
                - [mudstone](#clastic_mudstone)
                    - [claystone](#claystone)
                    - [shale](#shale)
                    - [siltstone](#siltstone)
                - [organic bearing mudstone](#organic_bearing_mudstone)
                - [pure carbonate mudstone](#pure_carbonate_mudstone)
                - [silicate mudstone](#silicate_mudstone)
            - [Generic sandstone](#generic_sandstone)
                - [sandstone](#clastic_sandstone)
                    - [arenit](#arenite)
                    - [piedra](#wacke)
            - [hybrid sedimentary rock](#hybrid_sedimentary_rock)
            - [iron rich sedimentary rock](#iron_rich_sedimentary_rock)
            - [non clastic siliceous sedimentary rock](#non_clastic_siliceous_sedimentary_rock)
                - [biogenic silica sedimentary rock](#biogenic_silica_sedimentary_rock)
            - [organic rich sedimentary rock](#organic_rich_sedimentary_rock)
                - [coal](#coal)
                    - [anthracite](#anthracite_coal)
                    - [bituminous coal](#bituminous_coal)
                    - [lignite](#lignite)
            - [phosphorite](#phosphorite)
        - [sediment](#sediment)
            - [biogenic sediment](#biogenic_sediment)
                - [ooze](#ooze)
                    - [carbonate ooze](#carbonate_ooze)
                    - [siliceous ooze](#siliceous_ooze)
                - [organic rich sediment](#organic_rich_sediment)
                    - [peat](#peat)
                    - [sapropel](#sapropel)
            - [carbonate sediment](#carbonate_sediment)
                - [calcareous carbonate sediment](#calcareous_carbonate_sediment)
                    - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                    - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                - [carbonate mud](#carbonate_mud)
                    - [carbonate ooze](#carbonate_ooze)
                - [dolomitic sediment](#dolomitic_sediment)
                    - [impure dolomitic sediment](#impure_dolomitic_sediment)
                    - [pure dolomitic sediment](#pure_dolomitic_sediment)
                - [impure carbonate sediment](#impure_carbonate_sediment)
                    - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                    - [impure dolomitic sediment](#impure_dolomitic_sediment)
                - [pure carbonate sediment](#pure_carbonate_sediment)
                    - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                    - [pure dolomitic sediment](#pure_dolomitic_sediment)
            - [clastic sediment](#clastic_sediment)
                - [diamicton](#diamicton)
                - [gravel](#gravel)
                - [mud](#mud)
                    - [clay](#clay)
                    - [silt](#silt)
                - [sand](#sand)
            - [gravel size sediment](#gravel_size_sediment)
                - [boulder gravel size sediment](#boulder_gravel_size_sediment)
                - [cobble gravel size sediment](#cobble_gravel_size_sediment)
                - [gravel](#gravel)
                - [pebble gravel size sediment](#pebble_gravel_size_sediment)
            - [Hybrid sediment](#hybrid_sediment)
            - [iron rich sediment](#iron_rich_sediment)
            - [mud size sediment](#mud_size_sediment)
                - [carbonate mud](#carbonate_mud)
                    - [carbonate ooze](#carbonate_ooze)
                - [carbonate rich mud](#carbonate_rich_mud)
                - [mud](#mud)
                    - [clay](#clay)
                    - [silt](#silt)
                - [ooze](#ooze)
                    - [carbonate ooze](#carbonate_ooze)
                    - [siliceous ooze](#siliceous_ooze)
                - [silicate mud](#silicate_mud)
                    - [siliceous ooze](#siliceous_ooze)
            - [non clastic siliceous sediment](#non_clastic_siliceous_sediment)
            - [phosphate rich sediment](#phosphate_rich_sediment)
            - [sand size sediment](#sand_size_sediment)
                - [sand](#sand)
        - [Carbonate sedimentary material](#carbonate_sedimentary_material)
            - [carbonate sediment](#carbonate_sediment)
                - [calcareous carbonate sediment](#calcareous_carbonate_sediment)
                    - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                    - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                - [carbonate mud](#carbonate_mud)
                    - [carbonate ooze](#carbonate_ooze)
                - [dolomitic sediment](#dolomitic_sediment)
                    - [impure dolomitic sediment](#impure_dolomitic_sediment)
                    - [pure dolomitic sediment](#pure_dolomitic_sediment)
                - [impure carbonate sediment](#impure_carbonate_sediment)
                    - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                    - [impure dolomitic sediment](#impure_dolomitic_sediment)
                - [pure carbonate sediment](#pure_carbonate_sediment)
                    - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                    - [pure dolomitic sediment](#pure_dolomitic_sediment)
            - [carbonate sedimentary rock](#carbonate_sedimentary_rock)
                - [boundstone](#boundstone)
                - [calcareous carbonate sedimentary rock](#calcareous_carbonate_sedimentary_rock)
                    - [impure limestone](#impure_limestone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
                - [carbonate mudstone](#carbonate_mudstone)
                - [carbonate wackestone](#carbonate_wackestone)
                - [crystalline carbonate](#crystalline_carbonate)
                - [dolomitic or magnesian sedimentary rock](#dolomitic_or_magnesian_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [impure dolomite](#impure_dolostone)
                - [framestone](#framestone)
                - [grainstone](#grainstone)
                - [impure carbonate sedimentary rock](#impure_carbonate_sedimentary_rock)
                    - [impure dolomite](#impure_dolostone)
                    - [impure limestone](#impure_limestone)
                - [packstone](#packstone)
                - [pure carbonate sedimentary rock](#pure_carbonate_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
                    - [pure carbonate mudstone](#pure_carbonate_mudstone)
            - [calcareous carbonate sedimentary material](#calcareous_carbonate_sedimentary_material)
                - [calcareous carbonate sediment](#calcareous_carbonate_sediment)
                    - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                    - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                - [calcareous carbonate sedimentary rock](#calcareous_carbonate_sedimentary_rock)
                    - [impure limestone](#impure_limestone)
                    - [limestone](#limestone)
                        - [chalk](#chalk)
                        - [travertine](#travertine)
            - [dolomitic or magnesian sedimentary material](#dolomitic_or_magnesian_sedimentary_material)
                - [dolomitic or magnesian sedimentary rock](#dolomitic_or_magnesian_sedimentary_rock)
                    - [dolomite](#dolostone)
                    - [impure dolomite](#impure_dolostone)
                - [dolomitic sediment](#dolomitic_sediment)
                    - [impure dolomitic sediment](#impure_dolomitic_sediment)
                    - [pure dolomitic sediment](#pure_dolomitic_sediment)
        - [clastic sedimentary material](#clastic_sedimentary_material)
            - [clastic sediment](#clastic_sediment)
                - [diamicton](#diamicton)
                - [gravel](#gravel)
                - [mud](#mud)
                    - [clay](#clay)
                    - [silt](#silt)
                - [sand](#sand)
            - [clastic sedimentary rock](#clastic_sedimentary_rock)
                - [diamictite](#diamictite)
                - [conglomerate](#clastic_conglomerate)
                - [mudstone](#clastic_mudstone)
                    - [claystone](#claystone)
                    - [shale](#shale)
                    - [siltstone](#siltstone)
                - [sandstone](#clastic_sandstone)
                    - [arenit](#arenite)
                    - [piedra](#wacke)
        - [non clastic siliceous sedimentary material](#non_clastic_siliceous_sedimentary_material)
            - [non clastic siliceous sediment](#non_clastic_siliceous_sediment)
            - [non clastic siliceous sedimentary rock](#non_clastic_siliceous_sedimentary_rock)
                - [biogenic silica sedimentary rock](#biogenic_silica_sedimentary_rock)
        - [organic rich sedimentary material](#organic_rich_sedimentary_material)
            - [organic rich sedimentary rock](#organic_rich_sedimentary_rock)
                - [coal](#coal)
                    - [anthracite](#anthracite_coal)
                    - [bituminous coal](#bituminous_coal)
                    - [lignite](#lignite)
            - [organic rich sediment](#organic_rich_sediment)
                - [peat](#peat)
                - [sapropel](#sapropel)
        - [phosphate rich sedimentary material](#phosphate_rich_sedimentary_material)
            - [phosphate rich sediment](#phosphate_rich_sediment)
            - [phosphorite](#phosphorite)
    - [Unconsolidated material](#unconsolidated_material)
        - [Anthropogenic unconsolidated material](#anthropogenic_unconsolidated_material)
        - [Natural unconsolidated material](#natural_unconsolidated_material)
            - [Tephra](#tephra)
                - [ash and lapilli](#ash_and_lapilli)
                - [ash breccia bomb or block tephra](#ash_breccia_bomb_or_block_tephra)
            - [sediment](#sediment)
                - [biogenic sediment](#biogenic_sediment)
                    - [ooze](#ooze)
                        - [carbonate ooze](#carbonate_ooze)
                        - [siliceous ooze](#siliceous_ooze)
                    - [organic rich sediment](#organic_rich_sediment)
                        - [peat](#peat)
                        - [sapropel](#sapropel)
                - [carbonate sediment](#carbonate_sediment)
                    - [calcareous carbonate sediment](#calcareous_carbonate_sediment)
                        - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                        - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                    - [carbonate mud](#carbonate_mud)
                        - [carbonate ooze](#carbonate_ooze)
                    - [dolomitic sediment](#dolomitic_sediment)
                        - [impure dolomitic sediment](#impure_dolomitic_sediment)
                        - [pure dolomitic sediment](#pure_dolomitic_sediment)
                    - [impure carbonate sediment](#impure_carbonate_sediment)
                        - [impure calcareous carbonate sediment](#impure_calcareous_carbonate_sediment)
                        - [impure dolomitic sediment](#impure_dolomitic_sediment)
                    - [pure carbonate sediment](#pure_carbonate_sediment)
                        - [pure calcareous carbonate sediment](#pure_calcareous_carbonate_sediment)
                        - [pure dolomitic sediment](#pure_dolomitic_sediment)
                - [clastic sediment](#clastic_sediment)
                    - [diamicton](#diamicton)
                    - [gravel](#gravel)
                    - [mud](#mud)
                        - [clay](#clay)
                        - [silt](#silt)
                    - [sand](#sand)
                - [gravel size sediment](#gravel_size_sediment)
                    - [boulder gravel size sediment](#boulder_gravel_size_sediment)
                    - [cobble gravel size sediment](#cobble_gravel_size_sediment)
                    - [gravel](#gravel)
                    - [pebble gravel size sediment](#pebble_gravel_size_sediment)
                - [Hybrid sediment](#hybrid_sediment)
                - [iron rich sediment](#iron_rich_sediment)
                - [mud size sediment](#mud_size_sediment)
                    - [carbonate mud](#carbonate_mud)
                        - [carbonate ooze](#carbonate_ooze)
                    - [carbonate rich mud](#carbonate_rich_mud)
                    - [mud](#mud)
                        - [clay](#clay)
                        - [silt](#silt)
                    - [ooze](#ooze)
                        - [carbonate ooze](#carbonate_ooze)
                        - [siliceous ooze](#siliceous_ooze)
                    - [silicate mud](#silicate_mud)
                        - [siliceous ooze](#siliceous_ooze)
                - [non clastic siliceous sediment](#non_clastic_siliceous_sediment)
                - [phosphate rich sediment](#phosphate_rich_sediment)
                - [sand size sediment](#sand_size_sediment)
                    - [sand](#sand)

**Concepts**

[]{#rock_material}

##  Rock Material


- Concept URI token: Rock_Material


[]{#rock}

###  rock


- Child of:
 [`Rock_Material`](#Rock_Material)

- Consolidated aggregate of one or more EarthMaterials, or a body of
undifferentiated mineral matter, or of solid organic material.
Includes mineral aggregates such as granite, shale, marble; glassy
matter such as obsidian; and organic material such a coal. Excludes
unconsolidated materials.

- **Source:**
Jackson, 1997; NADM C1 2004; Neuendorf et al 2005

- Concept URI token: rock


[]{#aphanite}

####  Aphanite
* `aphanite`


- Child of:
 [`rock`](#rock)


- **Source:**
This vocabulary

- Concept URI token: Aphanite


[]{#igneous_rock}

####  Igneous rock
* `igneous rock`


- Child of:
 [`rock`](#rock)
 [`Igneous_Material`](#Igneous_Material)


- **Source:**
Neuendorf et al 2005

- Concept URI token: Igneous_Rock


[]{#acidic_igneous_rock}

#####  acidic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Acidic_Igneous_Material`](#Acidic_Igneous_Material)

- Igneous rock with more than 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Acidic_Igneous_Rock


[]{#dacite}

######  dacite


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

######  granitoid


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

#######  alkali feldspar granite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

#######  granite


- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#monzogranite}

########  monzogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.35
and 0.65. QAPF field 3b.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzogranite


[]{#syenogranite}

########  syenogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.10
and 0.35. QAPF field 3a.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenogranite


[]{#granodiorite}

#######  granodiorite


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

#######  tonalite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#quartz_rich_igneous_rock}

######  quartz rich igneous rock


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

######  rhyolitoid


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


[]{#alkali_feldspar_rhyolite}

#######  alkali feldspar rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- Rhyolitoid in which the ratio of plagioclase to total feldspar is
less than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Rhyolite


[]{#rhyolite}

#######  rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- rhyolitoid in which the ratio of plagioclase to total feldspar is
between 0.1 and 0.65.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolite


[]{#basic_igneous_rock}

#####  basic igneous rock
* `doleritic rock`


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Basic_Igneous_Material`](#Basic_Igneous_Material)

- Dark colored gabbroic (basaltic) or dioritic (andesitic) rock
intermediate in grain size between basalt and gabbro and composed of
plagioclase, pyroxene and opaque minerals; often with ophitic texture.
Typically occurs as hypabyssal intrusions. Includes dolerite,
microdiorite, diabase and microgabbro.
- Igneous rock with between 45 and 52 percent SiO2.

- **Source:**
Neuendorf et al 2005; LeMaitre et al. 2002; Gillespie and Styles 1999, 
after LeMaitre et al. 2002, 

- Concept URI token: Basic_Igneous_Rock


[]{#basalt}

######  basalt


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


[]{#alkali-olivine_basalt}

#######  alkali olivine basalt


- Child of:
 [`Basalt`](#Basalt)

- Alkali olivine basalt is silica-undersaturated, characterized by the
absence of orthopyroxene, absence of quartz, presence of olivine, and
typically contains some feldspathoid mineral, alkali feldspar or
phlogopite in the groundmass. Feldspar phenocrysts typically are
labradorite to andesine in composition. Augite is rich in titanium
compared to augite in tholeiitic basalt. Alkali olivine basalt is
relatively rich in sodium.
- The definition of tholeiite and alkali basalt here are more
prescriptive than those found in most reference authorities. This is
to actually provide some descriptive criteria to allow assignment of
rocks on a hand sample basis to the tholeiite or alkali basalt
categories if detailed petrographic or chemical data are available.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Alkali-Olivine_Basalt


[]{#tholeiitic_basalt}

#######  tholeiitic basalt


- Child of:
 [`Basalt`](#Basalt)

- Definition of tholeiite and alkali basalt here are more proscriptive
than those found in most reference authorities. This is to actually
provide some descriptive criteria to allow assignment of rocks on a
hand sample basis to the tholeiite or alkali basalt categories if
detailed petrographic or chemical data are available.
- Tholeiitic basalt is defined here to contain 2 pyroxene phases and
interstitial quartz or tridymite or cristobalite in the groundmass.
Pyroxene (augite and orthopyroxene or pigeonite) and calcium-rich
plagioclase are common phenocryst minerals. Olivine may also be a
phenocryst, and when present, may have rims of pigeonite. Only in
tholeiitic basalt is olivine in reaction relationship with melt.
Interstitial siliceous residue may be present, and is often glassy.
Tholeiitic basalt is relatively poor in sodium. This category includes
most basalts of the ocean floor, most large oceanic islands, and
continental flood basalts such as the Columbia River Plateau.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Tholeiitic_Basalt


[]{#gabbroic_rock}

######  gabbroic rock


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


[]{#foid_bearing_gabbro}

#######  foid bearing gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains 0-10 percent feldspathoid minerals and
no quartz in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Gabbro


[]{#gabbro}

#######  gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF Field 10 as gabbro.
- Note that this category includes gabbro (sensu stricto) of LeMaitre
et al. 2002, but is broader, including the other rock types defined by
orthopyroxene-clinopyroxene-olivine-hornblende mineral ratios.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbro


[]{#quartz_gabbro}

#######  quartz gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Gabbro


[]{#exotic_composition_igneous_rock}

#####  exotic composition igneous rock


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


[]{#carbonatite}

######  carbonatite


- Child of:
 [`Exotic_Composition_Igneous_Rock`](#Exotic_Composition_Igneous_Rock)

- Igneous rock composed of more than 50 percent modal carbonate
minerals.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Carbonatite


[]{#exotic_alkaline_rock}

######  exotic alkaline rock


- Child of:
 [`Exotic_Composition_Igneous_Rock`](#Exotic_Composition_Igneous_Rock)

- Kimberlite, lamproite, or lamprophyre. Generally are potassic, mafic
or ultramafic rocks. Olivine (commonly serpentinized in kimberlite),
and phlogopite are significant constituents.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Exotic_Alkaline_Rock


[]{#kalsilitic_and_melilitic_rock}

######  kalsilitic and melilitic rocks


- Child of:
 [`Exotic_Composition_Igneous_Rock`](#Exotic_Composition_Igneous_Rock)

- Igneous rock containing greater than 10 percent melilite or
kalsilite. Typically undersaturated, ultrapotassic (kalsilitic rocks)
or calcium-rich (melilitic rocks) mafic or ultramafic rocks.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Kalsilitic_And_Melilitic_Rock


[]{#fine_grained_igneous_rock}

#####  fine grained igneous rock


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

######  andesite


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


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#basalt}

######  basalt


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


[]{#alkali-olivine_basalt}

#######  alkali olivine basalt


- Child of:
 [`Basalt`](#Basalt)

- Alkali olivine basalt is silica-undersaturated, characterized by the
absence of orthopyroxene, absence of quartz, presence of olivine, and
typically contains some feldspathoid mineral, alkali feldspar or
phlogopite in the groundmass. Feldspar phenocrysts typically are
labradorite to andesine in composition. Augite is rich in titanium
compared to augite in tholeiitic basalt. Alkali olivine basalt is
relatively rich in sodium.
- The definition of tholeiite and alkali basalt here are more
prescriptive than those found in most reference authorities. This is
to actually provide some descriptive criteria to allow assignment of
rocks on a hand sample basis to the tholeiite or alkali basalt
categories if detailed petrographic or chemical data are available.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Alkali-Olivine_Basalt


[]{#tholeiitic_basalt}

#######  tholeiitic basalt


- Child of:
 [`Basalt`](#Basalt)

- Definition of tholeiite and alkali basalt here are more proscriptive
than those found in most reference authorities. This is to actually
provide some descriptive criteria to allow assignment of rocks on a
hand sample basis to the tholeiite or alkali basalt categories if
detailed petrographic or chemical data are available.
- Tholeiitic basalt is defined here to contain 2 pyroxene phases and
interstitial quartz or tridymite or cristobalite in the groundmass.
Pyroxene (augite and orthopyroxene or pigeonite) and calcium-rich
plagioclase are common phenocryst minerals. Olivine may also be a
phenocryst, and when present, may have rims of pigeonite. Only in
tholeiitic basalt is olivine in reaction relationship with melt.
Interstitial siliceous residue may be present, and is often glassy.
Tholeiitic basalt is relatively poor in sodium. This category includes
most basalts of the ocean floor, most large oceanic islands, and
continental flood basalts such as the Columbia River Plateau.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Tholeiitic_Basalt


[]{#dacite}

######  dacite


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

######  foiditoid


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


[]{#basanitic_foidite}

#######  basanitic foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains less than 90 percent feldspathoid minerals
in the QAPF fraction, and has a plagioclase to total feldspar ratio
that is greater than 0.5, with greater than 10 percent normative
olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Basanitic_Foidite


[]{#foidite}

#######  foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains greater than 90 percent feldspathoid
minerals in the QAPF fraction.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foidite


[]{#phonolitic_foidite}

#######  phonolitic foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains less than 90 percent feldspathoid minerals
in the QAPF fraction, and has a plagioclase to total feldspar ratio
that is less than 0.5

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitic_Foidite


[]{#tephritic_foidite}

#######  tephritic foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains less than 90 percent feldspathoid minerals
in the QAPF fraction, and has a plagioclase to total feldspar ratio
that is greater than 0.5, with less than 10 percent normative olivine

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephritic_Foidite


[]{#high_magnesium_fine_grained_igneous_rock}

######  high magnesium fine grained igneous rock


- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- fine-grained igneous rock that contains unusually high concentration
of MgO. For rocks that contain greater than 52 percent silica, MgO
must be greater than 8 percent. For rocks containing less than 52
percent silica, MgO must be greater than 12 percent.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: High_Magnesium_Fine_Grained_Igneous_Rock


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#komatiitic_rock}

#######  komatiitic rock


- Child of:
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic, magnesium-rich volcanic rock, typically with spinifex
texture of intergrown skeletal and bladed olivine and pyroxene
crystals set in abundant glass. Includes komatiite and meimechite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Komatiitic_Rock


[]{#phonolitoid}

######  phonolitoid


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


[]{#phonolilte}

#######  phonolite


- Child of:
 [`Phonolitoid`](#Phonolitoid)

- Phonolitoid in which the plagioclase to total feldspar ratio is less
than 0.1. Rock consists of alkali feldspar, feldspathoid minerals, and
mafic minerals.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolilte


[]{#tephritic_phonolite}

#######  tephritic phonolite


- Child of:
 [`Phonolitoid`](#Phonolitoid)

- Phonolitoid that has a plagioclase to total feldspar ratio between
0.1 and 0.5. Broadly corresponds to TAS tephriphonolite of TAS field
U3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephritic_Phonolite


[]{#rhyolitoid}

######  rhyolitoid


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


[]{#alkali_feldspar_rhyolite}

#######  alkali feldspar rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- Rhyolitoid in which the ratio of plagioclase to total feldspar is
less than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Rhyolite


[]{#rhyolite}

#######  rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- rhyolitoid in which the ratio of plagioclase to total feldspar is
between 0.1 and 0.65.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolite


[]{#tephritoid}

######  tephritoid


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


[]{#basanite}

#######  basanite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio greater
than 0.9, and contains more than 10 percent normative (CIPW) olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Basanite


[]{#phonolitic_basanite}

#######  phonolitic basanite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio between
0.5 and 0.9, and contains more than 10 percent normative (CIPW)
olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitic_Basanite


[]{#phonolitic_tephrite}

#######  phonolitic tephrite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio between
0.5 and 0.9, and contains less than 10 percent normative (CIPW)
olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitic_Tephrite


[]{#tephrite}

#######  tephrite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio greater
than 0.9, and contains less than 10 percent normative (CIPW) olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephrite


[]{#trachytoid}

######  trachytoid


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


[]{#alkali_feldspar_trachytic_rock}

#######  alkali feldspar trachytic rock


- Child of:
 [`Trachytoid`](#Trachytoid)

- Trachytoid that has a plagioclase to total feldspar ratio less than
0.1. QAPF fields 6, 6', and 6*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Trachytic_Rock


[]{#alkali_feldspar_trachyte}

########  alkali feldspar trachyte


- Child of:
 [`Alkali_Feldspar_Trachytic_Rock`](#Alkali_Feldspar_Trachytic_Rock)

- Trachytoid that has a plagioclase to total feldspar ratio less than
0.1, between 0 and 5 percent quartz in the QAPF fraction, and no
feldspathoid minerals. QAPF field 6.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Trachyte


[]{#foid_bearing_alkali_feldspar_trachyte}

########  foid bearing alkali feldspar trachyte


- Child of:
 [`Alkali_Feldspar_Trachytic_Rock`](#Alkali_Feldspar_Trachytic_Rock)

- Alkali feldspar trachytic rock that contains no quartz and between 0
and 10 percent feldspathoid mineral in the QAPF fraction. QAPF field
6'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Alkali_Feldspar_Trachyte


[]{#quartz_alkali_feldspar_trachyte}

########  quartz alkali feldspar trachyte


- Child of:
 [`Alkali_Feldspar_Trachytic_Rock`](#Alkali_Feldspar_Trachytic_Rock)

- Alkali feldspar trachytic rock that contains and between 5 and 20
percent quartz mineral in the QAPF fraction. QAPF field 6*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Alkali_Feldspar_Trachyte


[]{#latitic_rock}

#######  latitic rock


- Child of:
 [`Trachytoid`](#Trachytoid)

- Trachytoid that has a plagioclase to total feldspar ratio between
0.35 and 0.65. QAPF fields 8, 8' and 8*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Latitic_Rock


[]{#foid_bearing_latite}

########  foid bearing latite


- Child of:
 [`Latitic_Rock`](#Latitic_Rock)

- Latitic rock that contains no quartz and between 0 and 10 percent
feldspathoid minerals in the QAPF fraction. QAPF field 8'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Latite


[]{#latite}

########  latite


- Child of:
 [`Latitic_Rock`](#Latitic_Rock)

- Latitic rock that contains between 0 and 5 percent quartz and no
feldspathoid in the QAPF fraction. QAPF field 8.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Latite


[]{#quartz_latite}

########  quartz latite


- Child of:
 [`Latitic_Rock`](#Latitic_Rock)

- Latitic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 8*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Latite


[]{#trachytic_rock}

#######  trachytic rock


- Child of:
 [`Trachytoid`](#Trachytoid)

- LeMaitre et al. (2002) used 'trachyte' to refer to QAPF fields 7,
7', and 7* in the text (p. 30) as well as to the more restrictive
category (QAPF field 7 only). The term Trachytic rock is introduced
here to label this more general category of trachyte.
- Trachytoid that has a plagioclase to total feldspar ratio between
0.1 and 0.35. QAPF fields 7, 7', and 7*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Trachytic_Rock


[]{#foid_bearing_trachyte}

########  foid bearing trachyte


- Child of:
 [`Trachytic_Rock`](#Trachytic_Rock)

- Trachytic rock that contains between 0 and 10 percent feldspathoid
in the QAPF fraction, and no quartz. QAPF field 7'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Trachyte


[]{#quartz_trachyte}

########  quartz trachyte


- Child of:
 [`Trachytic_Rock`](#Trachytic_Rock)

- Trachytic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 7*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Trachyte


[]{#trachyte}

########  trachyte


- Child of:
 [`Trachytic_Rock`](#Trachytic_Rock)

- Trachytoid that has a plagioclase to total feldspar ratio between
0.1 and 0.35, between 0 and 5 percent quartz in the QAPF fraction, and
no feldspathoid minerals. QAPF field 7.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Trachyte


[]{#fragmental_igneous_rock}

#####  fragmental igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Fragmental_Igneous_Material`](#Fragmental_Igneous_Material)

- Igneous rock in which greater than 75 percent of the rock consists
of fragments produced as a result of igneous rock-forming process.
Includes pyroclastic rocks, autobreccia associated with lava flows and
intrusive breccias. Excludes deposits reworked by epiclastic processes
(see Tuffite)

- **Source:**
This vocabulary

- Concept URI token: Fragmental_Igneous_Rock


[]{#glass_rich_igneous_rock}

#####  glass rich igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that contains greater than 50 percent massive glass.

- **Source:**
This vocabulary, based on Gillespie and Styles 1999

- Concept URI token: Glass_Rich_Igneous_Rock


[]{#glassy_igneous_rock}

######  glassy igneous rock


- Child of:
 [`Glass_Rich_Igneous_Rock`](#Glass_Rich_Igneous_Rock)

- Igneous rock that consists of greater than 80 percent massive glass.
- Note that this category is used for massive glassy rocks. Much of
the pyroclastic material in a pyroclastic rock may be composed of
glass, but the rock is named based on its fragmental nature.

- **Source:**
This vocabulary

- Concept URI token: Glassy_Igneous_Rock


[]{#hypabyssal_intrusive_rock}

#####  hypabyssal intrusive rock


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

#####  intermediate composition igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Intermediate_Composition_Igneous_Material`](#Intermediate_Composition_Igneous_Material)

- Igneous rock with between 52 and 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Intermediate_Composition_Igneous_Rock


[]{#andesite}

######  andesite


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


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#dioritoid}

######  dioritoid


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


[]{#dioritic_rock}

#######  dioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline rock with M less than 90, consisting of
intermediate plagioclase, commonly with hornblende and often with
biotite or augite. A dioritoid with a plagioclase to total feldspar
ratio (in the QAPF fraction) greater than 0.9. Includes rocks defined
modally in QAPF fields 10, 10' and 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritic_Rock


[]{#diorite}

########  diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Phaneritic crystalline rock consisting of intermediate plagioclase,
commonly with hornblende and often with biotite or augite; colour
index M less than 90, sodic plagioclase (An0-An50), no feldspathoid,
and between 0 and 5 percent quartz. Includes rocks defined modally in
QAPF field 10 as diorite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Diorite


[]{#foid_bearing_diorite}

########  foid bearing diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 0 and 10 percent feldspathoid
minerals in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Diorite


[]{#quartz_diorite}

########  quartz diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 5 to 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Diorite


[]{#monzodioritic_rock}

#######  monzodioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 10 percent feldspathoid or 0 to 20 percent
quartz in the QAPF fraction. Plagioclase to total feldspar ratio in
the QAPF fraction is between 0.65 and 0.9. Includes rocks defined
modally in QAPF field 9, 9' and 9* as monzodiorite, foid-beaing
monzodiorite, and quartz monzodiorite.

- **Source:**
This vocabulary; LeMaitre et al. 2002

- Concept URI token: Monzodioritic_Rock


[]{#foid_bearing_monzodiorite}

########  foid bearing monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 0 and 10 percent
feldspathoid mineral.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzodiorite


[]{#monzodiorite}

########  monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 5 percent quartz. Includes rocks defined
modally in QAPF field 9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzodiorite


[]{#quartz_monzodiorite}

########  quartz monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 5 and 20 percent quartz.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzodiorite


[]{#phaneritic_igneous_rock}

#####  phaneritic igneous rock


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

######  anorthositic rock


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


[]{#anorthosite}

#######  anorthosite


- Child of:
 [`Anorthositic_Rock`](#Anorthositic_Rock)

- Anorthositic rock that contains between 0 and 5 percent quartz and
no feldspathoid mineral in the QAPF fraction. QAPF field 10.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Anorthosite


[]{#foid_bearing_anorthosite}

#######  foid bearing anorthosite


- Child of:
 [`Anorthositic_Rock`](#Anorthositic_Rock)

- Anorthositic rock that contains between 0 and 10 percent
feldspathoid mineral and no quartz in the QAPF fraction. QAPF field
10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Anorthosite


[]{#quartz_anorthosite}

#######  quartz anorthosite


- Child of:
 [`Anorthositic_Rock`](#Anorthositic_Rock)

- Anorthositic rock that contains between 5 and 20 percent quartz in
the QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Anorthosite


[]{#aplite}

######  aplite


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

######  dioritoid


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


[]{#dioritic_rock}

#######  dioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline rock with M less than 90, consisting of
intermediate plagioclase, commonly with hornblende and often with
biotite or augite. A dioritoid with a plagioclase to total feldspar
ratio (in the QAPF fraction) greater than 0.9. Includes rocks defined
modally in QAPF fields 10, 10' and 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritic_Rock


[]{#diorite}

########  diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Phaneritic crystalline rock consisting of intermediate plagioclase,
commonly with hornblende and often with biotite or augite; colour
index M less than 90, sodic plagioclase (An0-An50), no feldspathoid,
and between 0 and 5 percent quartz. Includes rocks defined modally in
QAPF field 10 as diorite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Diorite


[]{#foid_bearing_diorite}

########  foid bearing diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 0 and 10 percent feldspathoid
minerals in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Diorite


[]{#quartz_diorite}

########  quartz diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 5 to 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Diorite


[]{#monzodioritic_rock}

#######  monzodioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 10 percent feldspathoid or 0 to 20 percent
quartz in the QAPF fraction. Plagioclase to total feldspar ratio in
the QAPF fraction is between 0.65 and 0.9. Includes rocks defined
modally in QAPF field 9, 9' and 9* as monzodiorite, foid-beaing
monzodiorite, and quartz monzodiorite.

- **Source:**
This vocabulary; LeMaitre et al. 2002

- Concept URI token: Monzodioritic_Rock


[]{#foid_bearing_monzodiorite}

########  foid bearing monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 0 and 10 percent
feldspathoid mineral.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzodiorite


[]{#monzodiorite}

########  monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 5 percent quartz. Includes rocks defined
modally in QAPF field 9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzodiorite


[]{#quartz_monzodiorite}

########  quartz monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 5 and 20 percent quartz.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzodiorite


[]{#foid_dioritoid}

######  foid dioritoid


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


[]{#foid_diorite}

#######  foid diorite


- Child of:
 [`Foid_Dioritoid`](#Foid_Dioritoid)

- Foid dioritoid in which the plagioclase to total feldspar ratio is
greater than 0.9. Includes rocks defined modally in QAPF field 14.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Diorite


[]{#foid_monzodiorite}

#######  foid monzodiorite


- Child of:
 [`Foid_Dioritoid`](#Foid_Dioritoid)

- Foid dioritoid in which the plagioclase to total feldspar ratio is
between 0.1 and 0.9. Includes rocks defined modally in QAPF field 13.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Monzodiorite


[]{#foid_gabbroid}

######  foid gabbroid


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


[]{#foid_gabbro}

#######  foid gabbro


- Child of:
 [`Foid_Gabbroid`](#Foid_Gabbroid)

- Foid gabbroid that has a plagioclase to total feldspar ratio greater
than 0.9. Includes rocks defined modally in QAPF field 14.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Gabbro


[]{#foid_monzogabbro}

#######  foid monzogabbro


- Child of:
 [`Foid_Gabbroid`](#Foid_Gabbroid)

- Foid gabbroid that has a plagioclase to total feldspar ratio between
0.5 and 0.9. Includes rocks defined modally in QAPF field 13.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Monzogabbro


[]{#foid_syenitoid}

######  foid syenitoid


- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock with M less than 90, contains
between 10 and 60 percent feldspathoid mineral in the QAPF fraction,
and has a plagioclase to total feldspar ratio less than 0.5. Includes
QAPF fields 11 and 12.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Syenitoid


[]{#foid_monzosyenite}

#######  foid monzosyenite


- Child of:
 [`Foid_Syenitoid`](#Foid_Syenitoid)

- Foid syenitoid rock that has a plagioclase to total feldspar ratio
of between 0.1 and 0.5. Includes rocks defined modally in QAPF Field
12.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Monzosyenite


[]{#foid_syenite}

#######  foid syenite


- Child of:
 [`Foid_Syenitoid`](#Foid_Syenitoid)

- Foid syenitoid that has a plagioclase to total feldspar ratio of
less than 0.1. Includes rocks defined modally in QAPF field 11.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Syenite


[]{#foidolite}

######  foidolite


- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline rock containing more than 60 percent
feldspathoid minerals in the QAPF fraction. Includes rocks defined
modally in QAPF field 15

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foidolite


[]{#gabbroid}

######  gabbroid


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

#######  gabbroic rock


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


[]{#foid_bearing_gabbro}

########  foid bearing gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains 0-10 percent feldspathoid minerals and
no quartz in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Gabbro


[]{#gabbro}

########  gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF Field 10 as gabbro.
- Note that this category includes gabbro (sensu stricto) of LeMaitre
et al. 2002, but is broader, including the other rock types defined by
orthopyroxene-clinopyroxene-olivine-hornblende mineral ratios.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbro


[]{#quartz_gabbro}

########  quartz gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Gabbro


[]{#monzogabbroic_rock}

#######  monzogabbroic rock


- Child of:
 [`Gabbroid`](#Gabbroid)

- Gabbroid with a plagioclase to total feldspar ratio between 0.65 and
0.9. QAPF field 9, 9 prime and 9 asterisk

- **Source:**
LeMaitre et al. 2002, This vocabulary

- Concept URI token: Monzogabbroic_Rock


[]{#foid_bearing_monzogabbro}

########  foid bearing monzogabbro


- Child of:
 [`Monzogabbroic_Rock`](#Monzogabbroic_Rock)

- Monzogabbroic rock that contains 0 to 10 percent feldspathoid
mineral in the QAPF fraction. QAPF field 9'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzogabbro


[]{#monzogabbro}

########  monzogabbro


- Child of:
 [`Monzogabbroic_Rock`](#Monzogabbroic_Rock)

- Monzogabbroic rock that contains between 0 an 5 percent quartz and
no feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF field 9 .

- **Source:**
LeMaitre et al. 2002, This vocabulary

- Concept URI token: Monzogabbro


[]{#quartz_monzogabbro}

########  quartz monzogabbro


- Child of:
 [`Monzogabbroic_Rock`](#Monzogabbroic_Rock)

- Monzogabbroic rock that contains between 5 and 20 percent quartz in
the QAPF fraction. QAPF field 9*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzogabbro


[]{#granitoid}

######  granitoid


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

#######  alkali feldspar granite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

#######  granite


- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#monzogranite}

########  monzogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.35
and 0.65. QAPF field 3b.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzogranite


[]{#syenogranite}

########  syenogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.10
and 0.35. QAPF field 3a.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenogranite


[]{#granodiorite}

#######  granodiorite


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

#######  tonalite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#hornblendite}

######  hornblendite


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

######  pegmatite


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

######  peridotite


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

######  pyroxenite


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

######  quartz rich igneous rock


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

######  syenitoid


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


[]{#alkali_feldspar_syenitic_rock}

#######  alkali feldspar syenitic rock


- Child of:
 [`Syenitoid`](#Syenitoid)

- Syenitoid with a plagioclase to total feldspar ratio of less than
0.1. QAPF fields 6, 6*, and 6'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Syenitic_Rock


[]{#alkali_feldspar_syenite}

########  alkali feldspar syenite


- Child of:
 [`Alkali_Feldspar_Syenitic_Rock`](#Alkali_Feldspar_Syenitic_Rock)

- Alkali feldspar syenitic rock that contains 0-5 percent quartz and
no feldspathoid in the QAPF fraction. QAPF field 6.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Syenite


[]{#foid_bearing_alkali_feldspar_syenite}

########  foid bearing alkali feldspar syenite


- Child of:
 [`Alkali_Feldspar_Syenitic_Rock`](#Alkali_Feldspar_Syenitic_Rock)

- Alkali feldspar syenitic rock that contains 0-10 percent
feldspathoid mineral and no quartz in the QAPF fraction. QAPF field
6'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Alkali_Feldspar_Syenite


[]{#quartz_alkali_feldspar_syenite}

########  quartz alkali feldspar syenite


- Child of:
 [`Alkali_Feldspar_Syenitic_Rock`](#Alkali_Feldspar_Syenitic_Rock)

- Alkali feldspar syenitic rock that contains 5 to 20 percent quartz
and no feldspathoid in the QAPF fraction. QAPF field 6*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Alkali_Feldspar_Syenite


[]{#monzonitic_rock}

#######  monzonitic rock


- Child of:
 [`Syenitoid`](#Syenitoid)

- Syenitoid with a plagioclase to total feldspar ratio between 0.35
and 0.65. Includes rocks in QAPF fields 8, 8*, and 8'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzonitic_Rock


[]{#foid_bearing_monzonite}

########  foid bearing monzonite


- Child of:
 [`Monzonitic_Rock`](#Monzonitic_Rock)

- Monzonitic rock that contains 0-10 percent feldspathoid mineral and
no quartz in the QAPF fraction. Includes rocks defined modally in QAPF
Field 8'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzonite


[]{#monzonite}

########  monzonite


- Child of:
 [`Monzonitic_Rock`](#Monzonitic_Rock)

- Monzonitic rock that contains 0-5 percent quartz and no feldspathoid
mineral in the QAPF fraction. Includes rocks defined modally in QAPF
Field 8.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzonite


[]{#quartz_monzonite}

########  quartz monzonite


- Child of:
 [`Monzonitic_Rock`](#Monzonitic_Rock)

- Monzonitic rock that contains 5-20 percent quartz iin the QAPF
fraction. Includes rocks defined modally in QAPF Field 8*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzonite


[]{#syenitic_rock}

#######  syenitic rock


- Child of:
 [`Syenitoid`](#Syenitoid)

- Syenitoid with a plagioclase to total feldspar ratio between 0.1 and
0.35. Includes rocks in QAPF fields 7, 7*, and 7'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenitic_Rock


[]{#foid_bearing_syenite}

########  foid bearing syenite


- Child of:
 [`Syenitic_Rock`](#Syenitic_Rock)

- Syenitic rock that contains between 0 and 10 percent feldspathoid
mineral and no quartz in the QAPF fraction. Defined modally in QAPF
Field 7'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Syenite


[]{#quartz_syenite}

########  quartz syenite


- Child of:
 [`Syenitic_Rock`](#Syenitic_Rock)

- Syenitic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. Defined modally in QAPF Field 7*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Syenite


[]{#syenite}

########  syenite


- Child of:
 [`Syenitic_Rock`](#Syenitic_Rock)

- Syenitic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Defined modally in QAPF
Field 7.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenite


[]{#plutonic_igneous_rock}

#####  plutonic rock


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

#####  porphyry


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that contains conspicuous phenocrysts in a finer
grained groundmass; groundmass itself may be phaneritic or fine-
grained.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Porphyry


[]{#ultrabasic_igneous_rock}

#####  ultrabasic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock with less than 45 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Ultrabasic_Igneous_Rock


[]{#ultramafic_igneous_rock}

#####  ultramafic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that consists of greater than 90 percent mafic
minerals.

- **Source:**
LeMaitre et al. 2002; Gillespie and Styles 1999

- Concept URI token: Ultramafic_Igneous_Rock


[]{#hornblendite}

######  hornblendite


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

######  peridotite


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

######  pyroxenite


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


[]{#komatiitic_rock}

######  komatiitic rock


- Child of:
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic, magnesium-rich volcanic rock, typically with spinifex
texture of intergrown skeletal and bladed olivine and pyroxene
crystals set in abundant glass. Includes komatiite and meimechite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Komatiitic_Rock


[]{#massive_sulphide}

####  Massive sulphide
* `massive sulphide`


- Child of:
 [`rock`](#rock)


- **Alternate labels:**
Massive Sulfide


- **Source:**
Provisional SMR 2020-06-07

- Concept URI token: Massive_Sulphide


[]{#hydrothermal_massive_sulphide}

#####  Hydrothermal Massive Sulphide


- Child of:
 [`Massive_Sulphide`](#Massive_Sulphide)
 [`Metasomatic_Rock`](#Metasomatic_Rock)

- Rock consisting of greater that 50% sulphide or sulfosalt minerals
formed by hydrothermal mineralization processes.

- **Alternate labels:**
Hydrothermal Massive Sulfide


- **Source:**
provisional by SMR 2020-06-07

- Concept URI token: Hydrothermal_Massive_Sulphide


[]{#sedimentary_massive_sulphide}

#####  Sedimentary Massive Sulphide


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Massive_Sulphide`](#Massive_Sulphide)

- rock consisting of greater than 50% sulphide or sulfosalt minerals
formed by sedimentary exhalative processes.

- **Alternate labels:**
Sedimentary Massive Sulfide


- **Source:**
smr provisional 2020-06-07

- Concept URI token: Sedimentary_Massive_Sulphide


[]{#sedimentary_rock}

####  Sedimentary rock
* `sedimentary rock`


- Child of:
 [`rock`](#rock)
 [`Sedimentary_Material`](#Sedimentary_Material)


- **Source:**
SLTTs 2004

- Concept URI token: Sedimentary_Rock


[]{#carbonate_sedimentary_rock}

#####  carbonate sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

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


[]{#boundstone}

######  boundstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary carbonate rock with preserved biogenic texture, whose
original components were bound and encrusted together during
deposition by the action of plants and animals during deposition, and
remained substantially in the position of growth.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Boundstone


[]{#calcareous_carbonate_sedimentary_rock}

######  calcareous carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
SLTTs 2004; Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sedimentary_Rock


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#carbonate_mudstone}

######  carbonate mudstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that consists of greater than 50 percent carbonate minerals
of any origin in the mud size fraction.
- Not a subcategory of carbonate sedimentary rock because definition
does not specify 'carbonate minerals of intrabasinal origin', but is
agnostic on origin of carbonate. Schnurrenberger et al. 2003 point out
that it is very difficult (at least in lacustrine rocks) to
distinguish chemically precipitated or diagenetic carbonate from
primary biogenic carbonate. This distinction between biogenic,
detrital, and pedogenic or authigenic carbonate material is thus not a
good one to use in a general purpose classification system.
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Mudstone


[]{#carbonate_wackestone}

######  carbonate wackestone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with discernible mud supported
depositional texture and containing greater than 10 percent allochems,
and constituent particles are of intrabasinal origin. If particles are
not intrabasinal, categorization as a mudstone or wackestone should be
considered.

- **Source:**
Dunham 1962

- Concept URI token: Carbonate_Wackestone


[]{#crystalline_carbonate}

######  crystalline carbonate


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate rock of indeterminate mineralogy in which diagenetic
processes have obliterated any original depositional texture.

- **Source:**
SLTTs 2004

- Concept URI token: Crystalline_Carbonate


[]{#dolomitic_or_magnesian_sedimentary_rock}

######  dolomitic or magnesian sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sedimentary rock with a ratio of magnesium carbonate to
calcite (plus aragonite) greater than 1 to 1. Includes dolostone, lime
dolostone and magnesite-stone.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Or_Magnesian_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#framestone}

######  framestone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate reef rock consisting of a rigid framework of colonies,
shells or skeletons, with internal cavities filled with fine sediment;
usually created through the activities of colonial organisms.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004, Table 15-3-1

- Concept URI token: Framestone


[]{#grainstone}

######  grainstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with recognizable depositional fabric
that is grain-supported, and constituent particles are of intrabasinal
origin; contains little or no mud matrix. Distinction from sandstone
is based on interpretation of intrabasinal origin of clasts and grain-
supported fabric, but grainstone definition does not include a grain
size criteria.

- **Alternate labels:**
carbonate grainstone


- **Source:**
Dunham 1962

- Concept URI token: Grainstone


[]{#impure_carbonate_sedimentary_rock}

######  impure carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary rock in which between 50 and 90 percent of the primary
and/or recrystallized constituents are composed of carbonate minerals.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Carbonate_Sedimentary_Rock


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#packstone}

######  packstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with discernible grain supported
depositional texture, containing greater than 10 percent grains, and
constituent particles are of intrabasinal origin; intergranular spaces
are filled by matrix.
- Note that this category overlaps with 'carbonate mudstone'.

- **Source:**
Hallsworth and Knox 1999

- Concept URI token: Packstone


[]{#pure_carbonate_sedimentary_rock}

######  pure carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary rock in which greater than 90 percent of the primary
and/or recrystallized constituents are carbonate minerals.

- **Source:**
This vocabulary

- Concept URI token: Pure_Carbonate_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#pure_carbonate_mudstone}

#######  pure carbonate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Mudstone that consists of greater than 90 percent carbonate minerals
of intrabasinal orign in the mud fraction, and contains less than 10
percent allochems. The original depositional texture is preserved and
fabric is matrix supported. Carbonate mudstone of Dunham (1962)

- **Source:**
Dunham 1962

- Concept URI token: Pure_Carbonate_Mudstone


[]{#clastic_sedimentary_rock}

#####  clastic sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Clastic_Sedimentary_Material`](#Clastic_Sedimentary_Material)

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

######  diamictite


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


[]{#clastic_conglomerate}

######  conglomerate


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Conglomerate`](#Generic_Conglomerate)

- Clastic sedimentary rock composed of at least 30 percent rounded to
subangular fragments larger than 2 mm in diameter; typically contains
finer grained material in interstices between larger fragments. If
more than 15 percent of the fine grained matrix is of indeterminant
clastic or diagenetic origin and the fabric is matrix supported, may
also be categorized as wackestone. If rock has unsorted or poorly
sorted texture with a wide range of particle sizes, may also be
categorized as diamictite.
- Note this category is equivlanet to category labeled 'Conglomeratic
rock in SLTTs (2004), not to the category labeled 'Conglomerate' in
that system.

- **Alternate labels:**
conglomeratic rock


- **Source:**
Neuendorf et al. 2005; SLTTs 2004

- Concept URI token: Clastic_Conglomerate


[]{#clastic_mudstone}

######  mudstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Clastic sedimentary rock consisting of less than 30 percent gravel-
size (2 mm) particles and with a mud to sand ratio greater than 1.
- Distinction of intrabasinal, diagenetic, or clastic genesis for very
fine-grained carbonate minerals is interpretive in many cases. If
there is uncertainty on the mudstone category based on intrabasinal vs
epiclastic distinction required for clastic sedimentary rock-carbonate
sedimentary rock categorization in this system, it is recommended to
use the generic_mudstone category. This category is the union of the
various fields labeled 'mudstone' with various qualifiers in Folk,
1954, Figure 1a, although Folk's (1954) category labeled 'mudstone' is
a much more restricted category. The CGI category is equivalent to
category labeled 'Mudrock' in SLTTs (2004), not to the category
labeled 'Mudstone' adopted by that system from Folk (1954).
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
clastic mudstone, 
mudrock, 


- **Source:**
Pettijohn et al. 1987 referenced in Hallsworth and Knox 1999.

- Concept URI token: Clastic_Mudstone


[]{#claystone}

#######  claystone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains no detectable silt, inferred to consist
virtually entirely of clay-size particles.

- **Source:**
This vocabulary

- Concept URI token: Claystone


[]{#shale}

#######  shale


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Laminated mudstone that will part or break along thin, closely
spaced layers parallel to stratification.
- Note definition does not specify carbonate vs. siliclastic nature of
mud.

- **Source:**
NADM SLTT sedimentary, 2004

- Concept URI token: Shale


[]{#siltstone}

#######  siltstone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains detectable silt. (see comments)
- Use of 'dectable silt' in the criteria for this category is based on
the observation that in practice, distinction of claystone from
'siltstone' is typically based on a qualitative assessment of
'grittiness' (e.g. rubbing with fingers, or chewing); the property
that these tests can determine is the presence or absence of silty
particles in the material. Quantitative grain size analysis in the the
clay/silt fraction of a lithified sediment is difficult at best, and
of questionable significance because diagensis has altered the size
and mineralogy of original sedimentary particles.

- **Alternate labels:**
Silt bearing mudstone


- **Source:**
This vocabulary

- Concept URI token: Siltstone


[]{#clastic_sandstone}

######  sandstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Sandstone`](#Generic_Sandstone)

- Clastic sedimentary rock in which less than 30 percent of particles
are greater than 2 mm in diameter (gravel) and the sand to mud ratio
is at least 1.
- Note this category is equivalent to cagetory labeled 'sandy rock' in
SLTTs (2004), not to the much more restricted category labeled
'Sandstone' in that system.

- **Alternate labels:**
clastic sandstone, 
sandy rock, 


- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clastic_Sandstone


[]{#arenite}

#######  arenit
* `arenite`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone that contains less than 10 percent matrix. Matrix
is mud-size silicate minerals (clay, feldspar, quartz, rock fragments,
and alteration products) of detrital or diagenetic nature.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Arenite


[]{#wacke}

#######  piedra
* `wacke`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone with more than 10 percent matrix of indeterminate
detrital or diagenetic nature. Matrix is mud size silicate minerals
(clay, feldspar, quartz, rock fragments, and alteration products).
- Distinction from mudstone is based on inference that less that 50
percent of the mud size fraction (matrix) is original mud size
detrital particles. May also grade into diamictite or conglomerate
based on size distribution of discernible particles. If more than 50
percent of rock is detrital particles of intrabasinal orgin and
carbonate composition, categorize as carbonate wackestone. Term is
typically applied to diagenetically altered volcanic-lithic clastic
rocks in which the definition of the original clasts has been
obscured. Suggested boundaries between wacke and arenite range from 5
to 15 percent matrix. See Dickinson (1970) for discussion of
interpretation of undiscernible matrix in diagenetically altered
lithic clastic rocks. Dickinson, W.R., 1970, Interpreting detrital
modes of graywacke and arkose: Journal of Sedimentary Petrology, v.
40, p. 695-707.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Wacke


[]{#generic_conglomerate}

#####  generic conglomerate


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


[]{#clastic_conglomerate}

######  conglomerate


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Conglomerate`](#Generic_Conglomerate)

- Clastic sedimentary rock composed of at least 30 percent rounded to
subangular fragments larger than 2 mm in diameter; typically contains
finer grained material in interstices between larger fragments. If
more than 15 percent of the fine grained matrix is of indeterminant
clastic or diagenetic origin and the fabric is matrix supported, may
also be categorized as wackestone. If rock has unsorted or poorly
sorted texture with a wide range of particle sizes, may also be
categorized as diamictite.
- Note this category is equivlanet to category labeled 'Conglomeratic
rock in SLTTs (2004), not to the category labeled 'Conglomerate' in
that system.

- **Alternate labels:**
conglomeratic rock


- **Source:**
Neuendorf et al. 2005; SLTTs 2004

- Concept URI token: Clastic_Conglomerate


[]{#generic_mudstone}

#####  generic mudstone


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


[]{#carbonate_mudstone}

######  carbonate mudstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that consists of greater than 50 percent carbonate minerals
of any origin in the mud size fraction.
- Not a subcategory of carbonate sedimentary rock because definition
does not specify 'carbonate minerals of intrabasinal origin', but is
agnostic on origin of carbonate. Schnurrenberger et al. 2003 point out
that it is very difficult (at least in lacustrine rocks) to
distinguish chemically precipitated or diagenetic carbonate from
primary biogenic carbonate. This distinction between biogenic,
detrital, and pedogenic or authigenic carbonate material is thus not a
good one to use in a general purpose classification system.
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Mudstone


[]{#carbonate_rich_mudstone}

######  carbonate rich mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)

- Carbonate-rich mudstone' definition limits carbonate to mud-size
fraction to avoid overlap with 'impure carbonate sedimentary rock'. If
carbonate minerals are in sand or gravel size fractions, use 'impure
carbonate sedimentary rock'. The operational test typically used to
identify this category is if the rock fizzes when hydrochloric acid is
applied. The '10 percent carbonate' criteria is a fuzzy boundary.
- Mudstone that contains between 10 and 50 percent carbonate minerals
in the mud size fraction. Carbonate origin is not specified.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Rich_Mudstone


[]{#clastic_mudstone}

######  mudstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Clastic sedimentary rock consisting of less than 30 percent gravel-
size (2 mm) particles and with a mud to sand ratio greater than 1.
- Distinction of intrabasinal, diagenetic, or clastic genesis for very
fine-grained carbonate minerals is interpretive in many cases. If
there is uncertainty on the mudstone category based on intrabasinal vs
epiclastic distinction required for clastic sedimentary rock-carbonate
sedimentary rock categorization in this system, it is recommended to
use the generic_mudstone category. This category is the union of the
various fields labeled 'mudstone' with various qualifiers in Folk,
1954, Figure 1a, although Folk's (1954) category labeled 'mudstone' is
a much more restricted category. The CGI category is equivalent to
category labeled 'Mudrock' in SLTTs (2004), not to the category
labeled 'Mudstone' adopted by that system from Folk (1954).
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
clastic mudstone, 
mudrock, 


- **Source:**
Pettijohn et al. 1987 referenced in Hallsworth and Knox 1999.

- Concept URI token: Clastic_Mudstone


[]{#claystone}

#######  claystone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains no detectable silt, inferred to consist
virtually entirely of clay-size particles.

- **Source:**
This vocabulary

- Concept URI token: Claystone


[]{#shale}

#######  shale


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Laminated mudstone that will part or break along thin, closely
spaced layers parallel to stratification.
- Note definition does not specify carbonate vs. siliclastic nature of
mud.

- **Source:**
NADM SLTT sedimentary, 2004

- Concept URI token: Shale


[]{#siltstone}

#######  siltstone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains detectable silt. (see comments)
- Use of 'dectable silt' in the criteria for this category is based on
the observation that in practice, distinction of claystone from
'siltstone' is typically based on a qualitative assessment of
'grittiness' (e.g. rubbing with fingers, or chewing); the property
that these tests can determine is the presence or absence of silty
particles in the material. Quantitative grain size analysis in the the
clay/silt fraction of a lithified sediment is difficult at best, and
of questionable significance because diagensis has altered the size
and mineralogy of original sedimentary particles.

- **Alternate labels:**
Silt bearing mudstone


- **Source:**
This vocabulary

- Concept URI token: Siltstone


[]{#organic_bearing_mudstone}

######  organic bearing mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that contains a significant amount of organic carbon,
typically kerogen. commonly finely laminated, brown or black in color.

- **Alternate labels:**
oil shale


- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Oil_shale

- Concept URI token: Organic_Bearing_Mudstone


[]{#pure_carbonate_mudstone}

######  pure carbonate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Mudstone that consists of greater than 90 percent carbonate minerals
of intrabasinal orign in the mud fraction, and contains less than 10
percent allochems. The original depositional texture is preserved and
fabric is matrix supported. Carbonate mudstone of Dunham (1962)

- **Source:**
Dunham 1962

- Concept URI token: Pure_Carbonate_Mudstone


[]{#silicate_mudstone}

######  silicate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that contains less than 10 percent carbonate minerals.
- Operational distinction of this category will typically be based on
whether or not the rock fizzes when hydrochloric acid is applied--the
rock is silicate mudstone if it does not fizz. The quantitative '10
percent' criteria is fuzzy.

- **Source:**
This vocabulary

- Concept URI token: Silicate_Mudstone


[]{#generic_sandstone}

#####  Generic sandstone
* `generic sandstone`


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock in which less than 30 percent of particles are
greater than 2 mm in diameter (gravel) and the sand to mud ratio is at
least 1.

- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Generic_Sandstone


[]{#clastic_sandstone}

######  sandstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Sandstone`](#Generic_Sandstone)

- Clastic sedimentary rock in which less than 30 percent of particles
are greater than 2 mm in diameter (gravel) and the sand to mud ratio
is at least 1.
- Note this category is equivalent to cagetory labeled 'sandy rock' in
SLTTs (2004), not to the much more restricted category labeled
'Sandstone' in that system.

- **Alternate labels:**
clastic sandstone, 
sandy rock, 


- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clastic_Sandstone


[]{#arenite}

#######  arenit
* `arenite`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone that contains less than 10 percent matrix. Matrix
is mud-size silicate minerals (clay, feldspar, quartz, rock fragments,
and alteration products) of detrital or diagenetic nature.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Arenite


[]{#wacke}

#######  piedra
* `wacke`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone with more than 10 percent matrix of indeterminate
detrital or diagenetic nature. Matrix is mud size silicate minerals
(clay, feldspar, quartz, rock fragments, and alteration products).
- Distinction from mudstone is based on inference that less that 50
percent of the mud size fraction (matrix) is original mud size
detrital particles. May also grade into diamictite or conglomerate
based on size distribution of discernible particles. If more than 50
percent of rock is detrital particles of intrabasinal orgin and
carbonate composition, categorize as carbonate wackestone. Term is
typically applied to diagenetically altered volcanic-lithic clastic
rocks in which the definition of the original clasts has been
obscured. Suggested boundaries between wacke and arenite range from 5
to 15 percent matrix. See Dickinson (1970) for discussion of
interpretation of undiscernible matrix in diagenetically altered
lithic clastic rocks. Dickinson, W.R., 1970, Interpreting detrital
modes of graywacke and arkose: Journal of Sedimentary Petrology, v.
40, p. 695-707.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Wacke


[]{#hybrid_sedimentary_rock}

#####  hybrid sedimentary rock


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

#####  iron rich sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Iron_Rich_Sedimentary_Material`](#Iron_Rich_Sedimentary_Material)

- Sedimentary rock that consists of at least 50 percent iron-bearing
minerals (hematite, magnetite, limonite-group, siderite, iron-
sulfides), as determined by hand-lens or petrographic analysis.
Corresponds to a rock typically containing 15 percent iron by weight.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Iron_Rich_Sedimentary_Rock


[]{#non_clastic_siliceous_sedimentary_rock}

#####  non clastic siliceous sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Non_Clastic_Siliceous_Sedimentary_Material`](#Non_Clastic_Siliceous_Sedimentary_Material)

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


[]{#biogenic_silica_sedimentary_rock}

######  biogenic silica sedimentary rock


- Child of:
 [`Non_Clastic_Siliceous_Sedimentary_Rock`](#Non_Clastic_Siliceous_Sedimentary_Rock)

- Sedimentary rock that consists of at least 50 percent silicate
mineral material, deposited directly by biological processes at the
depositional surface, or in particles formed by biological processes
within the basin of deposition. Includes radiolarian chert, diatomite,
novaculite.

- **Source:**
based on NADM SLTT sedimentary; Hallsworth and Knox 1999

- Concept URI token: Biogenic_Silica_Sedimentary_Rock


[]{#organic_rich_sedimentary_rock}

#####  organic rich sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Organic_Rich_Sedimentary_Material`](#Organic_Rich_Sedimentary_Material)

- Sapropelic coal, and asphaltite are not differentiated in This
vocabulary
- Sedimentary rock with color, composition, texture and apparent
density indicating greater than 50 percent organic content by weight
on a moisture-free basis.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sedimentary_Rock


[]{#coal}

######  coal
* `kohle`


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


[]{#anthracite_coal}

#######  anthracite
* `anthrazit`


- Child of:
 [`Coal`](#Coal)

- Coal that has vitrinite mean random reflectance greater than 2.0%
(determined in conformance with ISO 7404-5). Less than 12-14 percent
volatiles (dry, ash free), greater than 91 percent fixed carbon (dry,
ash free basis). The highest rank coal; very hard, glossy, black, with
semimetallic luster, semi conchoidal fracture.

- **Alternate labels:**
High rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp; see also Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Coal#Types_of_coal; Eberhard Lindner; Chemie für Ingenieure; Lindner Verlag Karlsruhe, S. 258

- Concept URI token: Anthracite_Coal


[]{#bituminous_coal}

#######  bituminous coal


- Child of:
 [`Coal`](#Coal)

- Coal that has vitrinite mean random reflectance greater than 0.6%
and less than 2.0% (determined in conformance with ISO 7404-5), or has
a gross calorific value greater than 24 MJ/kg (determined in
conformance with ISO 1928). Hard, black, organic rich sedimentary
rock; contains less than 91 percent fixed carbon on a dry, mineral-
matter-free basis, and greater than 13-14 percent volatiles (dry, ash
free). Formed from the compaction or induration of variously altered
plant remains similar to those of peaty deposits.

- **Alternate labels:**
medium rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp; see also http://en.wikipedia.org/wiki/Coal#Types_of_coal; Eberhard Lindner; Chemie für Ingenieure; Lindner Verlag Karlsruhe, S. 258

- Concept URI token: Bituminous_Coal


[]{#lignite}

#######  lignite


- Child of:
 [`Coal`](#Coal)

- Coal that has a gross calorific value less than 24 MJ/kg (determined
in conformance with ISO 1928), and vitrinite mean random reflectance
less than 0.6% (determined in conformance with ISO 7404-5). Gross
calorific value is recalculated to a moist, ash free basis using bed
moisture (determined according to ISO 1015 or ISO 5068). Includes all
low-rank coals, including sub-bitiminous coal. A consolidated, dull,
soft brown to black coal having many readily discernible plant
fragments set in a finer grained organic matrix. Tends to crack and
fall apart on drying. Operationally sub-bituminous and bitiminous coal
are qualitatively distinguished based on brown streak for sub-
bitiminous coal and black streak for bituminous coal.

- **Alternate labels:**
low rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp.

- Concept URI token: Lignite


[]{#phosphorite}

#####  phosphorite


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Phosphate_Rich_Sedimentary_Material`](#Phosphate_Rich_Sedimentary_Material)

- Sedimentary rock in which at least 50 percent of the primary or
recrystallized constituents are phosphate minerals. Most commonly
occurs as a bedded primary or reworked secondary marine rock, composed
of microcrystalline carbonate fluorapatite in the form of lamina,
pellets, oolites and nodules, and skeletal, shell and bone fragments.

- **Source:**
HallsworthandKnox 1999, Jackson 1997

- Concept URI token: Phosphorite


[]{#tuffite}

####  Tuffite
* `tuffit`
* `tuffite`


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

- **Alternate labels:**
Volcaniclastic rock


- **Source:**
LeMaitre et al. 2002; Murawski and Meyer 1998

- Concept URI token: Tuffite


[]{#composite_genesis_rock}

####  Composite genesis rock


- Child of:
 [`rock`](#rock)

- Rock formed by geological modification of pre-existing rocks outside
the realm of igneous and sedimentary processes. Includes rocks formed
by impact metamorphism, standard dynamothermal metamorphism, brittle
deformation, weathering, metasomatism and hydrothermal alteration
(diagenesis is a sedimentary process in this context).

- **Source:**
SLTTm 2004

- Concept URI token: Composite_Genesis_Rock


[]{#cataclasite_series}

#####  cataclasite series


- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)
 [`Composite_Genesis_Rock`](#Composite_Genesis_Rock)

- Fault-related rock that maintained primary cohesion during
deformation, with matrix comprising greater than 10 percent of rock
mass; matrix is fine-grained material formed through grain size
reduction by fracture as opposed to crystal plastic process that
operate in mylonitic rock. Includes cataclasite, protocataclasite and
ultracataclasite.

- **Source:**
Sibson, 1977; Scholz, 1990; Snoke and Tullis, 1998; Barker, 1998 Appendix II; NADM SLTTm, 2004

- Concept URI token: Cataclasite_Series


[]{#metamorphic_rock}

#####  Metamorphic rock
* `metamorphic rock`


- Child of:
 [`Composite_Genesis_Rock`](#Composite_Genesis_Rock)

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

- **Source:**
Jackson 1997

- Concept URI token: Metamorphic_Rock


[]{#amphibolite}

######  amphibolite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock mainly consisting of green, brown or black
amphibole and plagioclase (including albite), which combined form 75
percent or more of the rock, and both of which are present as major
constituents. The amphibole constitutes 50 percent or more of the
total mafic constituents and is present in an amount of 30 percent or
more; other common minerals include quartz, clinopyroxene, garnet,
epidote-group minerals, biotite, titanite and scapolite.

- **Source:**
Coutinho et al. 2007, IUGS SCMR chapter 8 (http://www.bgs.ac.uk/SCMR/)

- Concept URI token: Amphibolite


[]{#argillite}

######  Argillite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- A weakly metamorphosed argillaceous rock (Flawn, 1953, AAPG Bull v37
p.563-664).  Rock is very fine-grained to aphanitic, compact,
indurated, and massive (lacks fissility or cleavage) (Neuendorf et al,
2004). Claystone and Siltstone are related, non-metamorphosed
sedimentary rocks. Like Aphanite but sedimentary protolith is
determined. In contact metamorphic environments would be Hornfels.

- **Source:**
Neuendorf et al, 2004, provisional SMR 2020-06-11

- Concept URI token: Argillite


[]{#calcsilicate_metamorphic_rock}

######  calc silicate metamorphic rock


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Overlaps into metasomatic rocks because of high mobility of Ca
carbonates. Typically rich in epidote, diopside, tremolite, calcic-
amphibole, talc, with quartz and calcite. Might be gneiss or
granofels; lower metamorphic grade than granulite.
- metamorphic rock containing abundant calcium-silicate minerals

- **Source:**
This vocabulary

- Concept URI token: Calcsilicate_Metamorphic_Rock


[]{#chlorite_actinolite_epidote_metamorphic_rock}

######  chlorite actinolite epidote metamorphic rock


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock characterized by 50 percent or more of combined
chlorite, actinolite and epidote. Category for rocks generally named
greenschist or greenstone.
- Rock classified as Greenschist is difficult to categorize in the CGI
SimpleLithology scheme. This stems in part from the variation in usage
and the general fuzzy definition of the term. The definition of
greenschist is generally something along the lines of 'metamorphosed
rock with a greenish colour, characterized by the presence of
actinolite, chlorite and epidote, and containing a planar or linear
fabric. The presence or absence of schistose fabric in rocks called
'greenschist' is problematic. The fabric present in many rocks called
greenschist is too weak or variably developed to meet the definition
of 'schist' per CGI SimpleLithology. Generally if the rock has
achieved metamorphic grade such that the term 'gneiss' is applicable,
it would not be called greenschist. Thus, 'greenschist' would
correspond most closely to a chlorite + actinolite rich 'Foliated
metamorphic rock', but if it actually meets the definition of 'Schist'
it would be a chlorite + actinolite 'Schist'.

- **Source:**
This vocabulary

- Concept URI token: Chlorite_Actinolite_Epidote_Metamorphic_Rock


[]{#eclogite}

######  eclogite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock composed of 75 percent or more (by volume)
omphacite and garnet, both of which are present as major constituents,
the amount of neither of them being higher than 75 percent (by
volume); the presence of plagioclase precludes classification as an
eclogite.

- **Source:**
IUGS SCMR 2007 (http://www.bgs.ac.uk/SCMR/)

- Concept URI token: Eclogite


[]{#foliated_metamorphic_rock}

######  foliated metamorphic rock


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock in which 10 percent or more of the contained
mineral grains are elements in a planar or linear fabric. Cataclastic
or glassy character precludes classification with this concept.

- **Source:**
based on NADM SLTT metamorphic

- Concept URI token: Foliated_Metamorphic_Rock


[]{#mylonitic_rock}

#######  mylonitic rock


- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)
 [`Foliated_Metamorphic_Rock`](#Foliated_Metamorphic_Rock)

- Metamorphic rock characterised by a foliation resulting from
tectonic grain size reduction, in which more than 10 percent of the
rock volume has undergone grain size reduction. Includes
protomylonite, mylonite, ultramylonite, and blastomylonite.

- **Source:**
Marshak and Mitra 1988

- Concept URI token: Mylonitic_Rock


[]{#phyllonite}

########  phyllonite


- Child of:
 [`Mylonitic_Rock`](#Mylonitic_Rock)

- Mylonitic rock composed largely of fine-grained mica that imparts a
sheen to foliation surfaces; may have flaser lamination, isoclinal
folding, and deformed veins, which indicate significant shearing.
Macroscopically resembles phyllite, but formed by mechanical
degradation of initially coarser rock.

- **Source:**
NADM metamorphic rock vocabulary SLTTm1.0; Marshak and Mitra 1988

- Concept URI token: Phyllonite


[]{#gneiss}

#######  gneiss


- Child of:
 [`Foliated_Metamorphic_Rock`](#Foliated_Metamorphic_Rock)

- Foliated metamorphic rock with bands or lenticles rich in granular
minerals alternating with bands or lenticles rich in minerals with a
flaky or elongate prismatic habit. Mylonitic foliation or well
developed, continuous schistosity (greater than 50 percent of the rock
consists of grains participate in a planar or linear fabric) precludes
classification with this concept.

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Gneiss


[]{#orthogneiss}

########  orthogneiss


- Child of:
 [`Gneiss`](#Gneiss)

- A gneiss with mineralogy and texture indicating derivation from a
phaneritic igneous rock protolith. Typically consists of abundant
feldspar, with quartz, and variable hornblende, biotite, and
muscovite, with a relatively homogeneous character.

- **Source:**
This vocabulary

- Concept URI token: Orthogneiss


[]{#paragneiss}

########  paragneiss


- Child of:
 [`Gneiss`](#Gneiss)

- A gneiss with mineralogy and texture indicating derivation from a
sedimentary rock protolith. Typically consists of abundant quartz,
mica, or calcsilicate minerals; aluminosilicate minerals or garnet
commonly present. composition of rock tends to be more variable on a
decimetric scale that in orthogneiss.

- **Source:**
This vocabulary

- Concept URI token: Paragneiss


[]{#phyllite}

#######  phyllite


- Child of:
 [`Foliated_Metamorphic_Rock`](#Foliated_Metamorphic_Rock)

- Rock with a well developed, continuous schistosity, an average grain
size between 0.1 and 0.5 millimeters, and a silvery sheen on cleavage
surfaces. Individual phyllosilicate grains are barely visible with the
unaided eye.

- **Source:**
IUGS SCMR 2007 (http://www.bgs.ac.uk/SCMR/)

- Concept URI token: Phyllite


[]{#schist}

#######  schist


- Child of:
 [`Foliated_Metamorphic_Rock`](#Foliated_Metamorphic_Rock)

- Foliated phaneritic metamorphic rock with well developed, continuous
schistosity, meaning that greater than 50 percent of the rock by
volume is mineral grains with a thin tabular, lamellar, or acicular
prismatic crystallographic habit that are oriented in a continuous
planar or linear fabric.

- **Source:**
SLTTm 2004; Neuendorf et al. 2005

- Concept URI token: Schist


[]{#mica_schist}

########  mica schist


- Child of:
 [`Schist`](#Schist)

- A schist that consists of more than 50 percent mica minerals,
typically muscovite or biotite. Special type included to distinguish
this common variety of schist.
- Include single subcategory of schist to indicate this common kind of
schist. 'Mica rich metamorphic rock' for compound use with schist
fabric term would be more compatible with treatment of blueschist
(Glaucophane lawsonite epidote metamorphic rock) and greenschist
(Chlorite actinolite epidote metamorphic rock), but based on the
assumption that schist is the only rock type that will meet the mica-
rich criteria, it seems reasonable to include as a subtype of schist.

- **Source:**
This vocabulary

- Concept URI token: Mica_Schist


[]{#slate}

#######  slate


- Child of:
 [`Foliated_Metamorphic_Rock`](#Foliated_Metamorphic_Rock)

- compact, fine grained rock with an average grain size less than
0.032 millimeter and a well developed schistosity (slaty cleavage),
and hence can be split into slabs or thin plates.

- **Source:**
NADM metamorphic rock vocabulary SLTTm1.0; Neuendorf et al. 2005

- Concept URI token: Slate


[]{#glaucophane_lawsonite_epidote_metamorphic_rock}

######  glaucophane lawsonite epidote metamorphic rock
* `glaukophanschiefer`


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- A metamorphic rock of roughly basaltic composition, defined by the
presence of glaucophane with lawsonite or epidote. Other minerals that
may be present include jadeite, albite, chlorite, garnet, and
muscovite (phengitic white mica). Typically fine-grained, dark
colored. Category for rocks commonly referred to as blueschist.
- Fabric is weakly developed in this rock in many cases, so the fabric
categories 'foliated metamorphic rock, 'schist' or 'granofels' may
apply.

- **Alternate labels:**
blauschiefer


- **Source:**
This vocabulary

- Concept URI token: Glaucophane_Lawsonite_Epidote_Metamorphic_Rock


[]{#granofels}

######  granofels


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock with granoblastic fabric and very little or no
foliation (less than 10 percent of the mineral grains in the rock are
elements in a planar or linear fabric). Grainsize not specified.

- **Source:**
SLTTm 2004

- Concept URI token: Granofels


[]{#hornfels}

#######  hornfels


- Child of:
 [`Granofels`](#Granofels)

- Granofels formed by contact metamorphism, composed of a mosaic of
equidimensional grains in a characteristically granoblastic or
decussate matrix; porphyroblasts or relict phenocrysts may be present.
Typically fine grained.

- **Source:**
IUGS SCMR 2007 (http://www.bgs.ac.uk/SCMR/)

- Concept URI token: Hornfels


[]{#granulite}

######  granulite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock of high metamorphic grade in which Fe-Mg silicate
minerals are dominantly hydroxl-free; feldspar must be present, and
muscovite is absent; rock contains less than 90 percent mafic
minerals, less than 75 percent calcite and/or dolomite, less than 75
percent quartz, less than 50 percent iron-bearing minerals (hematite,
magnetite, limonite-group, siderite, iron-sulfides), and less than 50
percent calc-silicate minerals.
- Wimmenauer (1985) requires granulite to consist of at least 20
percent feldspar. Garnet is frequently present; some hornblende or
biotite may be present. The rock has a granoblastic texture and
gneissose to massive structure; grain size and fabric may be variable
on a decimetric scale. Foliation is less well developed than in rock
that would typically be called gneiss. The minerals present in a
granulite vary depending on the protolith and the temperature and
pressure conditions experienced during metamorphism. According to
Fettes and Desmons (2007) the main calc-silicate minerals are calcic
garnet, calcic plagioclase, calcic scapolite, diopside-hedenbergite,
epidote group minerals, hydrogrossular, johannsenite, prehnite,
pumpellyite, titanite, vesuvianite, wollastonite. Note that the shale
and siltstone categories may apply to any of the mineralogically
defined mudstone categories.

- **Source:**
Fettes and Desmons (2007). See also Wimmenauer (1985), Winkler (1979) (D.R. Bowes (1989), The Encyclopedia of Igneous and Metamorphic Petrology; Van Nostrand Reinhold ISBN: 0-442-20623-2 ; wikipedia, http://en.wikipedia.org/wiki/Granulite accessed 5/30/09

- Concept URI token: Granulite


[]{#marble}

######  marble


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock consisting of greater than 75 percent fine- to
coarse-grained recrystallized calcite and/or dolomite; usually with a
granoblastic, saccharoidal texture.

- **Source:**
IUGS SCMR 2007 (http://www.bgs.ac.uk/SCMR/), SLTTm1.0 2004

- Concept URI token: Marble


[]{#metaplutonic_rock}

######  metaplutonic rock


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Rock formed by metamorphism of a plutonic igneous protolith.

- **Source:**
This vocabulary

- Concept URI token: Metaplutonic_Rock


[]{#metasedimentary_rock}

######  metasedimentary rock


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Rock formed by metamorphism of a sedimentary protolith.

- **Source:**
This vocabulary

- Concept URI token: Metasedimentary_Rock


[]{#metavolcanic_rock}

######  metavolcanic rock


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Rock formed by metamorphism of an extrusive igneous protolith.

- **Source:**
This vocabulary

- Concept URI token: Metavolcanic_Rock


[]{#migmatite}

######  migmatite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Silicate metamorphic rock that is pervasively heterogeneous on a
decimeter to meter scale that typically consists of darker and lighter
parts; the darker parts usually exhibit features of metamorphic rocks
whereas the lighter parts are of igneous-looking appearance.

- **Source:**
Fette and Desmons (2007) (http://www.bgs.ac.uk/SCMR/)

- Concept URI token: Migmatite


[]{#quartzite}

######  quartzite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Metamorphic rock consisting of greater than or equal to 75 percent
quartz; typically granoblastic texture.

- **Source:**
after Neuendorf et al. 2005

- Concept URI token: Quartzite


[]{#serpentinite}

######  serpentinite


- Child of:
 [`Metamorphic_Rock`](#Metamorphic_Rock)

- Rock consisting of more than 75 percent serpentine-group minerals,
eg. antigorite, chrysotile or lizardite; accessory chlorite, talc and
magnetite may be present; derived from hydration of ferromagnesian
silicate minerals such as olivine and pyroxene.

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Serpentinite


[]{#metasomatic_rock}

#####  metasomatic rock


- Child of:
 [`Composite_Genesis_Rock`](#Composite_Genesis_Rock)

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


[]{#hydrothermal_massive_sulphide}

######  Hydrothermal Massive Sulphide


- Child of:
 [`Massive_Sulphide`](#Massive_Sulphide)
 [`Metasomatic_Rock`](#Metasomatic_Rock)

- Rock consisting of greater that 50% sulphide or sulfosalt minerals
formed by hydrothermal mineralization processes.

- **Alternate labels:**
Hydrothermal Massive Sulfide


- **Source:**
provisional by SMR 2020-06-07

- Concept URI token: Hydrothermal_Massive_Sulphide


[]{#skarn}

######  skarn


- Child of:
 [`Metasomatic_Rock`](#Metasomatic_Rock)

- Metasomatic rock consisting mainly of Ca-, Mg-, Fe-, or Mn-silicate
minerals, which are free from or poor in water. Typically formed at
the contact between a silicate rock or magma and a carbonate rock.

- **Alternate labels:**
exoskarn, 
tactite, 


- **Source:**
Fettes and Desmons, 2007, p195

- Concept URI token: Skarn


[]{#spilite}

######  spilite


- Child of:
 [`Metasomatic_Rock`](#Metasomatic_Rock)

- Altered basic to intermediate composition fine-grained igneous rock
in which the feldspar is partially or completely composed of of
albite, typically accompanied by chlorite, calcite, quartz, epidote,
prehnite, and low-tempaerature hydrous crystallization products.
Preservation of eruptive volcanic features is typical.

- **Source:**
Fettes and Desmon, 2007; Best, M.G., 1982, Igneous and metamorphic petrology: New York, W.H. Freeman and company, p. 398; Neuendorf et al. 2005, p. 619.

- Concept URI token: Spilite


[]{#altered_rock}

######  Altered, type not specified


- Child of:
 [`Metasomatic_Rock`](#Metasomatic_Rock)

- Rock material has been changed by some subsurface alteration
process, but the nature of the alteration is not specified.
- Concept URI token: altered_rock


[]{#advanced_argillic_altered_rock}

#######  advanced argillic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- Advanced argillic alteration occurs under lower pH and higher
temperature conditions than argillic alteration. Kaolinite and dickite
occur at lower temperatures whereas pyrophyllite and andalusite occur
under high temperature conditions (T > 300°C). Quartz deposition is
common. Alunite, topaz, zunyite, tourmaline, enargite and tennantite
may also occur. In many cases, advanced argillic alteration zones, or
“lithocaps”, develop at shallow levels above porphyry Cu–Au deposits
(e.g., Lepanto-Far Southeast, Philippines; Maricunga, Chile). Advanced
argillic alteration mineral assemblages precipitate from SO2- and HCl-
rich magmatic vapor, which arises from an underlying intrusive source,
and can also form in supergene environments, due to post-hydrothermal
weathering and oxidation of pyrite, locally creating pH<1 liquid due
to high concentrations of H2SO4 within the vadose zone, where
kaolinite and alunite plus Fe hydroxides form.

- **Source:**
Antonio Arribas, Jeffrey Hedenquist, 2019, Environments of advanced argillic alteration: II) steam-heated, and exploration implications: Conference: Society of Resource Geology Annual SymposiumAt: University of Tokyo, Tokyo (Japan)Volume: 69, accessed at https://www.researchgate.net/publication/334230797_Environments_of_advanced_argillic_alteration_II_steam-heated_and_exploration_implications#fullTextFileContent; Constantinos Mavrogonatos et al., 2018, Mineralogical Study of the Advanced Argillic Alteration Zone at the Konos Hill Mo–Cu–Re–Au Porphyry Prospect, NE Greece: Minerals, 8, 479; doi:10.3390/min8110479;  https://en.wikipedia.org/wiki/Argillic_alteration

- Concept URI token: advanced_argillic_altered_rock


[]{#albitic_altered_rock}

#######  albitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: albitic_altered_rock


[]{#alunitic_altered_rock}

#######  alunitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: alunitic_altered_rock


[]{#argillic_altered_rock}

#######  argillic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- Argillic alteration is hydrothermal alteration of wall rock which
introduces clay minerals including kaolinite, smectite and illite. The
process generally occurs at low temperatures and may occur in
atmospheric conditions. Argillic alteration is representative of
supergene environments where low temperature groundwater becomes
acidic. Argillic assemblages include kaolinite replacing plagioclase
and montmorillonite replacing amphibole and plagioclase. Orthoclase is
generally stable and unaffected. Argillic grades into phyllic
alteration at higher temperatures in an ore deposit hydrothermal
system.

- **Source:**
https://en.wikipedia.org/wiki/Argillic_alteration

- Concept URI token: argillic_altered_rock


[]{#calcsilicate_altered_rock}

#######  calcsilicate altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: calcsilicate_altered_rock


[]{#carbonate_altered_rock}

#######  carbonate altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: carbonate_altered_rock


[]{#chloritic_altered_rock}

#######  chloritic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: chloritic_altered_rock


[]{#deuteric_altered_rock}

#######  deuteric altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: deuteric_altered_rock


[]{#epidote_altered_rock}

#######  epidote altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: epidote_altered_rock


[]{#greisen}

#######  greisen


- Child of:
 [`altered_rock`](#altered_rock)

- Greisen is a class of endoskarn,  formed by self-generated
alteration of a granite. Greisens appear as partly coarse, crystalline
granite, partly vuggy with miarolitic cavities, disseminated halide
minerals such as fluorite, and occasionally metallic oxide and sulfide
ore minerals, borate minerals (tourmaline) and accessory phases such
as sphene, beryl or topaz.

- **Source:**
https://en.wikipedia.org/wiki/Greisen

- Concept URI token: greisen


[]{#hematitic_altered_rock}

#######  hematitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: hematitic_altered_rock


[]{#kaolinitic_altered_rock}

#######  kaolinitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: kaolinitic_altered_rock


[]{#phyllic_altered_rock}

#######  phyllic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- Altered rock characterised by the assemblage of quartz + sericite +
pyrite, and occurs at high temperatures and moderately acidic (low pH)
conditions. Typically associated with copper porphyry ore deposits in
calc-alkaline rocks.

- **Source:**
https://en.wikipedia.org/wiki/Phyllic_alteration

- Concept URI token: phyllic_altered_rock


[]{#potassic_altered_rock}

#######  potassic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: potassic_altered_rock


[]{#propylitic_altered_rock}

#######  propylitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: propylitic_altered_rock


[]{#pyritic_altered_rock}

#######  pyritic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: pyritic_altered_rock


[]{#red_rock_altered_rock}

#######  red rock altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- Alteration characterized by finely dispersed hematite

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24, 
Williams, P.J., 1994, Aust. J. Earth Science, v41, p381-382, 

- Concept URI token: red_rock_altered_rock


[]{#saussuritised_rock}

#######  saussuritised rock


- Child of:
 [`altered_rock`](#altered_rock)

- Rock in which calcium-bearing plagioclase feldspar is altered to an
assemblage of minerals called saussurite, typically including zoisite,
chlorite, amphibole, and carbonate minerals. Residual fluids present
during the late stages of magmatic crystallization can react with
previously formed plagioclase feldspar to form saussurite; the
saussurite will be spread through the plagioclase or located near its
outer margin. The plagioclase may be reconstituted into a more sodium-
rich variety (albite), although the original form of the crystal is
retained. Later hydrothermal alteration can produce the same result.
Mafic rocks are especially susceptible to saussuritization owing to
their high calcium content; the more calcium-rich portions of
plagioclase in acidic rocks also are often saussuritized.

- **Source:**
https://www.britannica.com/science/saussuritization

- Concept URI token: saussuritised_rock


[]{#sericitic_altered_rock}

#######  sericitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- Rock in which plagioclase feldspar has been converted to sericite,
an informal term for  fine-grained white phyllosilicate minerals.
Commonly associated with phyllic altered rocks, used to describe less
intense alteration.

- **Source:**
https://en.wikipedia.org/wiki/Sericitic_alteration

- Concept URI token: sericitic_altered_rock


[]{#serpentinised_rock}

#######  serpentinised rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: serpentinised_rock


[]{#silicified_rock}

#######  silicificed rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: silicified_rock


[]{#uralitised_rock}

#######  uralitised rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: uralitised_rock


[]{#zeolitic_altered_rock}

#######  zeolitic altered rock


- Child of:
 [`altered_rock`](#altered_rock)

- definition missing

- **Source:**
CGI alterationtype SKOS vocabulary 2012-11-24

- Concept URI token: zeolitic_altered_rock


[]{#duricrust}

#####  Duricrust


- Child of:
 [`Composite_Genesis_Rock`](#Composite_Genesis_Rock)
 [`material_formed_in_surficial_environment`](#material_formed_in_surficial_environment)

- Rock forming a hard crust or layer at or near the Earth's surface at
the time of formation, e.g. in the upper horizons of a soil,
characterized by structures indicative of pedogenic origin.

- **Source:**
This vocabulary

- Concept URI token: Duricrust


[]{#anthropogenic_material}

###  Anthropogenic material


- Child of:
 [`Rock_Material`](#Rock_Material)

- Material known to have artificial (human-related) origin;
insufficient information to classify in more detail.

- **Source:**
This vocabulary

- Concept URI token: Anthropogenic_Material


[]{#anthropogenic_unconsolidated_material}

####  Anthropogenic unconsolidated material


- Child of:
 [`Anthropogenic_Material`](#Anthropogenic_Material)
 [`Unconsolidated_Material`](#Unconsolidated_Material)

- Unconsolidated material known to have artificial (human-related)
origin.

- **Source:**
This vocabulary

- Concept URI token: Anthropogenic_Unconsolidated_Material


[]{#breccia}

###  Breccia


- Child of:
 [`Rock_Material`](#Rock_Material)


- **Source:**
Neuendorf et al. 2005

- Concept URI token: Breccia


[]{#composite_genesis_material}

###  Composite genesis material


- Child of:
 [`Rock_Material`](#Rock_Material)

- Material of unspecified consolidation state formed by geological
modification of pre-existing materials outside the realm of igneous
and sedimentary processes. Includes rocks formed by impact
metamorphism, standard dynamothermal metamorphism, brittle
deformation, weathering, metasomatism and hydrothermal alteration
(diagenesis is a sedimentary process in this context).

- **Source:**
SLTTm 2004

- Concept URI token: Composite_Genesis_Material


[]{#fault_related_material}

####  Fault related material
* `fault related material`


- Child of:
 [`Composite_Genesis_Material`](#Composite_Genesis_Material)

- Material formed as a result brittle faulting, composed of greater
than 10 percent matrix; matrix is fine-grained material caused by
tectonic grainsize reduction. Includes cohesive (cataclasite series,
mylonitic rocks) and non-cohesive (breccia-gouge series) material.

- **Source:**
This vocabulary; SLTTm 2004

- Concept URI token: Fault_Related_Material


[]{#cataclasite_series}

#####  cataclasite series


- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)
 [`Composite_Genesis_Rock`](#Composite_Genesis_Rock)

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

#####  mylonitic rock


- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)
 [`Foliated_Metamorphic_Rock`](#Foliated_Metamorphic_Rock)

- Metamorphic rock characterised by a foliation resulting from
tectonic grain size reduction, in which more than 10 percent of the
rock volume has undergone grain size reduction. Includes
protomylonite, mylonite, ultramylonite, and blastomylonite.

- **Source:**
Marshak and Mitra 1988

- Concept URI token: Mylonitic_Rock


[]{#phyllonite}

######  phyllonite


- Child of:
 [`Mylonitic_Rock`](#Mylonitic_Rock)

- Mylonitic rock composed largely of fine-grained mica that imparts a
sheen to foliation surfaces; may have flaser lamination, isoclinal
folding, and deformed veins, which indicate significant shearing.
Macroscopically resembles phyllite, but formed by mechanical
degradation of initially coarser rock.

- **Source:**
NADM metamorphic rock vocabulary SLTTm1.0; Marshak and Mitra 1988

- Concept URI token: Phyllonite


[]{#breccia_gouge_series}

#####  breccia gouge series


- Child of:
 [`Fault_Related_Material`](#Fault_Related_Material)

- Fault-related material with features such as void spaces (filled or
unfilled), or unconsolidated matrix material between fragments,
indicating loss of cohesion during deformation. Includes fault-related
breccia and gouge.

- **Source:**
SLTTm 2004

- Concept URI token: breccia_gouge_series


[]{#impact_generated_material}

####  Impact generated material
* `impact generated material`


- Child of:
 [`Composite_Genesis_Material`](#Composite_Genesis_Material)

- Material that contains features indicative of shock metamorphism,
such as microscopic planar deformation features within grains or
shatter cones, interpreted to be the result of extraterrestrial bolide
impact. Includes breccias and melt rocks.

- **Source:**
Stöffler and Grieve 2007; Jackson 1997

- Concept URI token: Impact_Generated_Material


[]{#material_formed_in_surficial_environment}

####  material formed in surficial environment


- Child of:
 [`Composite_Genesis_Material`](#Composite_Genesis_Material)

- Material that is the product of weathering processes operating on
pre-existing rocks or deposits, analogous to hydrothermal or
metasomatic rocks, but formed at ambient Earth surface temperature and
pressure.

- **Source:**
This vocabulary

- Concept URI token: material_formed_in_surficial_environment


[]{#residual_material}

#####  residual material


- Child of:
 [`material_formed_in_surficial_environment`](#material_formed_in_surficial_environment)

- Material of composite origin resulting from weathering processes at
the Earth's surface, with genesis dominated by removal of chemical
constituents by aqueous leaching. Miinor clastic, chemical, or organic
input may also contribute. Consolidation state is not inherent in
definition, but typically material is unconsolidated or weakly
consolidated.

- **Source:**
This vocabulary

- Concept URI token: residual_material


[]{#duricrust}

#####  Duricrust


- Child of:
 [`Composite_Genesis_Rock`](#Composite_Genesis_Rock)
 [`material_formed_in_surficial_environment`](#material_formed_in_surficial_environment)

- Rock forming a hard crust or layer at or near the Earth's surface at
the time of formation, e.g. in the upper horizons of a soil,
characterized by structures indicative of pedogenic origin.

- **Source:**
This vocabulary

- Concept URI token: Duricrust


[]{#bauxite}

#####  bauxite


- Child of:
 [`material_formed_in_surficial_environment`](#material_formed_in_surficial_environment)

- Highly aluminous material containing abundant aluminium hydroxides
(gibbsite, less commonly boehmite, diaspore) and aluminium-substituted
iron oxides or hydroxides and generally minor or negligible kaolin
minerals; may contain up to 20 percent quartz. commonly has a
pisolitic or nodular texture, and may be cemented.

- **Source:**
Eggleton 2001

- Concept URI token: bauxite


[]{#igneous_material}

###  Igneous material


- Child of:
 [`Rock_Material`](#Rock_Material)

- Earth material formed as a result of igneous processes, eg.
intrusion and cooling of magma in the crust, volcanic eruption.

- **Source:**
This vocabulary

- Concept URI token: Igneous_Material


[]{#igneous_rock}

####  Igneous rock
* `igneous rock`


- Child of:
 [`rock`](#rock)
 [`Igneous_Material`](#Igneous_Material)


- **Source:**
Neuendorf et al 2005

- Concept URI token: Igneous_Rock


[]{#acidic_igneous_rock}

#####  acidic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Acidic_Igneous_Material`](#Acidic_Igneous_Material)

- Igneous rock with more than 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Acidic_Igneous_Rock


[]{#dacite}

######  dacite


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

######  granitoid


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

#######  alkali feldspar granite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

#######  granite


- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#monzogranite}

########  monzogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.35
and 0.65. QAPF field 3b.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzogranite


[]{#syenogranite}

########  syenogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.10
and 0.35. QAPF field 3a.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenogranite


[]{#granodiorite}

#######  granodiorite


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

#######  tonalite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#quartz_rich_igneous_rock}

######  quartz rich igneous rock


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

######  rhyolitoid


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


[]{#alkali_feldspar_rhyolite}

#######  alkali feldspar rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- Rhyolitoid in which the ratio of plagioclase to total feldspar is
less than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Rhyolite


[]{#rhyolite}

#######  rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- rhyolitoid in which the ratio of plagioclase to total feldspar is
between 0.1 and 0.65.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolite


[]{#basic_igneous_rock}

#####  basic igneous rock
* `doleritic rock`


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Basic_Igneous_Material`](#Basic_Igneous_Material)

- Dark colored gabbroic (basaltic) or dioritic (andesitic) rock
intermediate in grain size between basalt and gabbro and composed of
plagioclase, pyroxene and opaque minerals; often with ophitic texture.
Typically occurs as hypabyssal intrusions. Includes dolerite,
microdiorite, diabase and microgabbro.
- Igneous rock with between 45 and 52 percent SiO2.

- **Source:**
Neuendorf et al 2005; LeMaitre et al. 2002; Gillespie and Styles 1999, 
after LeMaitre et al. 2002, 

- Concept URI token: Basic_Igneous_Rock


[]{#basalt}

######  basalt


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


[]{#alkali-olivine_basalt}

#######  alkali olivine basalt


- Child of:
 [`Basalt`](#Basalt)

- Alkali olivine basalt is silica-undersaturated, characterized by the
absence of orthopyroxene, absence of quartz, presence of olivine, and
typically contains some feldspathoid mineral, alkali feldspar or
phlogopite in the groundmass. Feldspar phenocrysts typically are
labradorite to andesine in composition. Augite is rich in titanium
compared to augite in tholeiitic basalt. Alkali olivine basalt is
relatively rich in sodium.
- The definition of tholeiite and alkali basalt here are more
prescriptive than those found in most reference authorities. This is
to actually provide some descriptive criteria to allow assignment of
rocks on a hand sample basis to the tholeiite or alkali basalt
categories if detailed petrographic or chemical data are available.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Alkali-Olivine_Basalt


[]{#tholeiitic_basalt}

#######  tholeiitic basalt


- Child of:
 [`Basalt`](#Basalt)

- Definition of tholeiite and alkali basalt here are more proscriptive
than those found in most reference authorities. This is to actually
provide some descriptive criteria to allow assignment of rocks on a
hand sample basis to the tholeiite or alkali basalt categories if
detailed petrographic or chemical data are available.
- Tholeiitic basalt is defined here to contain 2 pyroxene phases and
interstitial quartz or tridymite or cristobalite in the groundmass.
Pyroxene (augite and orthopyroxene or pigeonite) and calcium-rich
plagioclase are common phenocryst minerals. Olivine may also be a
phenocryst, and when present, may have rims of pigeonite. Only in
tholeiitic basalt is olivine in reaction relationship with melt.
Interstitial siliceous residue may be present, and is often glassy.
Tholeiitic basalt is relatively poor in sodium. This category includes
most basalts of the ocean floor, most large oceanic islands, and
continental flood basalts such as the Columbia River Plateau.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Tholeiitic_Basalt


[]{#gabbroic_rock}

######  gabbroic rock


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


[]{#foid_bearing_gabbro}

#######  foid bearing gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains 0-10 percent feldspathoid minerals and
no quartz in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Gabbro


[]{#gabbro}

#######  gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF Field 10 as gabbro.
- Note that this category includes gabbro (sensu stricto) of LeMaitre
et al. 2002, but is broader, including the other rock types defined by
orthopyroxene-clinopyroxene-olivine-hornblende mineral ratios.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbro


[]{#quartz_gabbro}

#######  quartz gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Gabbro


[]{#exotic_composition_igneous_rock}

#####  exotic composition igneous rock


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


[]{#carbonatite}

######  carbonatite


- Child of:
 [`Exotic_Composition_Igneous_Rock`](#Exotic_Composition_Igneous_Rock)

- Igneous rock composed of more than 50 percent modal carbonate
minerals.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Carbonatite


[]{#exotic_alkaline_rock}

######  exotic alkaline rock


- Child of:
 [`Exotic_Composition_Igneous_Rock`](#Exotic_Composition_Igneous_Rock)

- Kimberlite, lamproite, or lamprophyre. Generally are potassic, mafic
or ultramafic rocks. Olivine (commonly serpentinized in kimberlite),
and phlogopite are significant constituents.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Exotic_Alkaline_Rock


[]{#kalsilitic_and_melilitic_rock}

######  kalsilitic and melilitic rocks


- Child of:
 [`Exotic_Composition_Igneous_Rock`](#Exotic_Composition_Igneous_Rock)

- Igneous rock containing greater than 10 percent melilite or
kalsilite. Typically undersaturated, ultrapotassic (kalsilitic rocks)
or calcium-rich (melilitic rocks) mafic or ultramafic rocks.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Kalsilitic_And_Melilitic_Rock


[]{#fine_grained_igneous_rock}

#####  fine grained igneous rock


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

######  andesite


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


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#basalt}

######  basalt


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


[]{#alkali-olivine_basalt}

#######  alkali olivine basalt


- Child of:
 [`Basalt`](#Basalt)

- Alkali olivine basalt is silica-undersaturated, characterized by the
absence of orthopyroxene, absence of quartz, presence of olivine, and
typically contains some feldspathoid mineral, alkali feldspar or
phlogopite in the groundmass. Feldspar phenocrysts typically are
labradorite to andesine in composition. Augite is rich in titanium
compared to augite in tholeiitic basalt. Alkali olivine basalt is
relatively rich in sodium.
- The definition of tholeiite and alkali basalt here are more
prescriptive than those found in most reference authorities. This is
to actually provide some descriptive criteria to allow assignment of
rocks on a hand sample basis to the tholeiite or alkali basalt
categories if detailed petrographic or chemical data are available.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Alkali-Olivine_Basalt


[]{#tholeiitic_basalt}

#######  tholeiitic basalt


- Child of:
 [`Basalt`](#Basalt)

- Definition of tholeiite and alkali basalt here are more proscriptive
than those found in most reference authorities. This is to actually
provide some descriptive criteria to allow assignment of rocks on a
hand sample basis to the tholeiite or alkali basalt categories if
detailed petrographic or chemical data are available.
- Tholeiitic basalt is defined here to contain 2 pyroxene phases and
interstitial quartz or tridymite or cristobalite in the groundmass.
Pyroxene (augite and orthopyroxene or pigeonite) and calcium-rich
plagioclase are common phenocryst minerals. Olivine may also be a
phenocryst, and when present, may have rims of pigeonite. Only in
tholeiitic basalt is olivine in reaction relationship with melt.
Interstitial siliceous residue may be present, and is often glassy.
Tholeiitic basalt is relatively poor in sodium. This category includes
most basalts of the ocean floor, most large oceanic islands, and
continental flood basalts such as the Columbia River Plateau.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Tholeiitic_Basalt


[]{#dacite}

######  dacite


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

######  foiditoid


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


[]{#basanitic_foidite}

#######  basanitic foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains less than 90 percent feldspathoid minerals
in the QAPF fraction, and has a plagioclase to total feldspar ratio
that is greater than 0.5, with greater than 10 percent normative
olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Basanitic_Foidite


[]{#foidite}

#######  foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains greater than 90 percent feldspathoid
minerals in the QAPF fraction.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foidite


[]{#phonolitic_foidite}

#######  phonolitic foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains less than 90 percent feldspathoid minerals
in the QAPF fraction, and has a plagioclase to total feldspar ratio
that is less than 0.5

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitic_Foidite


[]{#tephritic_foidite}

#######  tephritic foidite


- Child of:
 [`Foiditoid`](#Foiditoid)

- Foiditoid that contains less than 90 percent feldspathoid minerals
in the QAPF fraction, and has a plagioclase to total feldspar ratio
that is greater than 0.5, with less than 10 percent normative olivine

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephritic_Foidite


[]{#high_magnesium_fine_grained_igneous_rock}

######  high magnesium fine grained igneous rock


- Child of:
 [`Fine_Grained_Igneous_Rock`](#Fine_Grained_Igneous_Rock)

- fine-grained igneous rock that contains unusually high concentration
of MgO. For rocks that contain greater than 52 percent silica, MgO
must be greater than 8 percent. For rocks containing less than 52
percent silica, MgO must be greater than 12 percent.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: High_Magnesium_Fine_Grained_Igneous_Rock


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#komatiitic_rock}

#######  komatiitic rock


- Child of:
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic, magnesium-rich volcanic rock, typically with spinifex
texture of intergrown skeletal and bladed olivine and pyroxene
crystals set in abundant glass. Includes komatiite and meimechite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Komatiitic_Rock


[]{#phonolitoid}

######  phonolitoid


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


[]{#phonolilte}

#######  phonolite


- Child of:
 [`Phonolitoid`](#Phonolitoid)

- Phonolitoid in which the plagioclase to total feldspar ratio is less
than 0.1. Rock consists of alkali feldspar, feldspathoid minerals, and
mafic minerals.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolilte


[]{#tephritic_phonolite}

#######  tephritic phonolite


- Child of:
 [`Phonolitoid`](#Phonolitoid)

- Phonolitoid that has a plagioclase to total feldspar ratio between
0.1 and 0.5. Broadly corresponds to TAS tephriphonolite of TAS field
U3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephritic_Phonolite


[]{#rhyolitoid}

######  rhyolitoid


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


[]{#alkali_feldspar_rhyolite}

#######  alkali feldspar rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- Rhyolitoid in which the ratio of plagioclase to total feldspar is
less than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Rhyolite


[]{#rhyolite}

#######  rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- rhyolitoid in which the ratio of plagioclase to total feldspar is
between 0.1 and 0.65.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolite


[]{#tephritoid}

######  tephritoid


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


[]{#basanite}

#######  basanite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio greater
than 0.9, and contains more than 10 percent normative (CIPW) olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Basanite


[]{#phonolitic_basanite}

#######  phonolitic basanite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio between
0.5 and 0.9, and contains more than 10 percent normative (CIPW)
olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitic_Basanite


[]{#phonolitic_tephrite}

#######  phonolitic tephrite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio between
0.5 and 0.9, and contains less than 10 percent normative (CIPW)
olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Phonolitic_Tephrite


[]{#tephrite}

#######  tephrite


- Child of:
 [`Tephritoid`](#Tephritoid)

- Tephritoid that has a plagioclase to total feldspar ratio greater
than 0.9, and contains less than 10 percent normative (CIPW) olivine.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tephrite


[]{#trachytoid}

######  trachytoid


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


[]{#alkali_feldspar_trachytic_rock}

#######  alkali feldspar trachytic rock


- Child of:
 [`Trachytoid`](#Trachytoid)

- Trachytoid that has a plagioclase to total feldspar ratio less than
0.1. QAPF fields 6, 6', and 6*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Trachytic_Rock


[]{#alkali_feldspar_trachyte}

########  alkali feldspar trachyte


- Child of:
 [`Alkali_Feldspar_Trachytic_Rock`](#Alkali_Feldspar_Trachytic_Rock)

- Trachytoid that has a plagioclase to total feldspar ratio less than
0.1, between 0 and 5 percent quartz in the QAPF fraction, and no
feldspathoid minerals. QAPF field 6.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Trachyte


[]{#foid_bearing_alkali_feldspar_trachyte}

########  foid bearing alkali feldspar trachyte


- Child of:
 [`Alkali_Feldspar_Trachytic_Rock`](#Alkali_Feldspar_Trachytic_Rock)

- Alkali feldspar trachytic rock that contains no quartz and between 0
and 10 percent feldspathoid mineral in the QAPF fraction. QAPF field
6'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Alkali_Feldspar_Trachyte


[]{#quartz_alkali_feldspar_trachyte}

########  quartz alkali feldspar trachyte


- Child of:
 [`Alkali_Feldspar_Trachytic_Rock`](#Alkali_Feldspar_Trachytic_Rock)

- Alkali feldspar trachytic rock that contains and between 5 and 20
percent quartz mineral in the QAPF fraction. QAPF field 6*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Alkali_Feldspar_Trachyte


[]{#latitic_rock}

#######  latitic rock


- Child of:
 [`Trachytoid`](#Trachytoid)

- Trachytoid that has a plagioclase to total feldspar ratio between
0.35 and 0.65. QAPF fields 8, 8' and 8*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Latitic_Rock


[]{#foid_bearing_latite}

########  foid bearing latite


- Child of:
 [`Latitic_Rock`](#Latitic_Rock)

- Latitic rock that contains no quartz and between 0 and 10 percent
feldspathoid minerals in the QAPF fraction. QAPF field 8'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Latite


[]{#latite}

########  latite


- Child of:
 [`Latitic_Rock`](#Latitic_Rock)

- Latitic rock that contains between 0 and 5 percent quartz and no
feldspathoid in the QAPF fraction. QAPF field 8.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Latite


[]{#quartz_latite}

########  quartz latite


- Child of:
 [`Latitic_Rock`](#Latitic_Rock)

- Latitic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 8*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Latite


[]{#trachytic_rock}

#######  trachytic rock


- Child of:
 [`Trachytoid`](#Trachytoid)

- LeMaitre et al. (2002) used 'trachyte' to refer to QAPF fields 7,
7', and 7* in the text (p. 30) as well as to the more restrictive
category (QAPF field 7 only). The term Trachytic rock is introduced
here to label this more general category of trachyte.
- Trachytoid that has a plagioclase to total feldspar ratio between
0.1 and 0.35. QAPF fields 7, 7', and 7*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Trachytic_Rock


[]{#foid_bearing_trachyte}

########  foid bearing trachyte


- Child of:
 [`Trachytic_Rock`](#Trachytic_Rock)

- Trachytic rock that contains between 0 and 10 percent feldspathoid
in the QAPF fraction, and no quartz. QAPF field 7'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Trachyte


[]{#quartz_trachyte}

########  quartz trachyte


- Child of:
 [`Trachytic_Rock`](#Trachytic_Rock)

- Trachytic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 7*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Trachyte


[]{#trachyte}

########  trachyte


- Child of:
 [`Trachytic_Rock`](#Trachytic_Rock)

- Trachytoid that has a plagioclase to total feldspar ratio between
0.1 and 0.35, between 0 and 5 percent quartz in the QAPF fraction, and
no feldspathoid minerals. QAPF field 7.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Trachyte


[]{#fragmental_igneous_rock}

#####  fragmental igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Fragmental_Igneous_Material`](#Fragmental_Igneous_Material)

- Igneous rock in which greater than 75 percent of the rock consists
of fragments produced as a result of igneous rock-forming process.
Includes pyroclastic rocks, autobreccia associated with lava flows and
intrusive breccias. Excludes deposits reworked by epiclastic processes
(see Tuffite)

- **Source:**
This vocabulary

- Concept URI token: Fragmental_Igneous_Rock


[]{#glass_rich_igneous_rock}

#####  glass rich igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that contains greater than 50 percent massive glass.

- **Source:**
This vocabulary, based on Gillespie and Styles 1999

- Concept URI token: Glass_Rich_Igneous_Rock


[]{#glassy_igneous_rock}

######  glassy igneous rock


- Child of:
 [`Glass_Rich_Igneous_Rock`](#Glass_Rich_Igneous_Rock)

- Igneous rock that consists of greater than 80 percent massive glass.
- Note that this category is used for massive glassy rocks. Much of
the pyroclastic material in a pyroclastic rock may be composed of
glass, but the rock is named based on its fragmental nature.

- **Source:**
This vocabulary

- Concept URI token: Glassy_Igneous_Rock


[]{#hypabyssal_intrusive_rock}

#####  hypabyssal intrusive rock


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

#####  intermediate composition igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Intermediate_Composition_Igneous_Material`](#Intermediate_Composition_Igneous_Material)

- Igneous rock with between 52 and 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Intermediate_Composition_Igneous_Rock


[]{#andesite}

######  andesite


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


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#dioritoid}

######  dioritoid


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


[]{#dioritic_rock}

#######  dioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline rock with M less than 90, consisting of
intermediate plagioclase, commonly with hornblende and often with
biotite or augite. A dioritoid with a plagioclase to total feldspar
ratio (in the QAPF fraction) greater than 0.9. Includes rocks defined
modally in QAPF fields 10, 10' and 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritic_Rock


[]{#diorite}

########  diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Phaneritic crystalline rock consisting of intermediate plagioclase,
commonly with hornblende and often with biotite or augite; colour
index M less than 90, sodic plagioclase (An0-An50), no feldspathoid,
and between 0 and 5 percent quartz. Includes rocks defined modally in
QAPF field 10 as diorite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Diorite


[]{#foid_bearing_diorite}

########  foid bearing diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 0 and 10 percent feldspathoid
minerals in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Diorite


[]{#quartz_diorite}

########  quartz diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 5 to 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Diorite


[]{#monzodioritic_rock}

#######  monzodioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 10 percent feldspathoid or 0 to 20 percent
quartz in the QAPF fraction. Plagioclase to total feldspar ratio in
the QAPF fraction is between 0.65 and 0.9. Includes rocks defined
modally in QAPF field 9, 9' and 9* as monzodiorite, foid-beaing
monzodiorite, and quartz monzodiorite.

- **Source:**
This vocabulary; LeMaitre et al. 2002

- Concept URI token: Monzodioritic_Rock


[]{#foid_bearing_monzodiorite}

########  foid bearing monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 0 and 10 percent
feldspathoid mineral.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzodiorite


[]{#monzodiorite}

########  monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 5 percent quartz. Includes rocks defined
modally in QAPF field 9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzodiorite


[]{#quartz_monzodiorite}

########  quartz monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 5 and 20 percent quartz.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzodiorite


[]{#phaneritic_igneous_rock}

#####  phaneritic igneous rock


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

######  anorthositic rock


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


[]{#anorthosite}

#######  anorthosite


- Child of:
 [`Anorthositic_Rock`](#Anorthositic_Rock)

- Anorthositic rock that contains between 0 and 5 percent quartz and
no feldspathoid mineral in the QAPF fraction. QAPF field 10.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Anorthosite


[]{#foid_bearing_anorthosite}

#######  foid bearing anorthosite


- Child of:
 [`Anorthositic_Rock`](#Anorthositic_Rock)

- Anorthositic rock that contains between 0 and 10 percent
feldspathoid mineral and no quartz in the QAPF fraction. QAPF field
10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Anorthosite


[]{#quartz_anorthosite}

#######  quartz anorthosite


- Child of:
 [`Anorthositic_Rock`](#Anorthositic_Rock)

- Anorthositic rock that contains between 5 and 20 percent quartz in
the QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Anorthosite


[]{#aplite}

######  aplite


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

######  dioritoid


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


[]{#dioritic_rock}

#######  dioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline rock with M less than 90, consisting of
intermediate plagioclase, commonly with hornblende and often with
biotite or augite. A dioritoid with a plagioclase to total feldspar
ratio (in the QAPF fraction) greater than 0.9. Includes rocks defined
modally in QAPF fields 10, 10' and 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritic_Rock


[]{#diorite}

########  diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Phaneritic crystalline rock consisting of intermediate plagioclase,
commonly with hornblende and often with biotite or augite; colour
index M less than 90, sodic plagioclase (An0-An50), no feldspathoid,
and between 0 and 5 percent quartz. Includes rocks defined modally in
QAPF field 10 as diorite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Diorite


[]{#foid_bearing_diorite}

########  foid bearing diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 0 and 10 percent feldspathoid
minerals in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Diorite


[]{#quartz_diorite}

########  quartz diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 5 to 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Diorite


[]{#monzodioritic_rock}

#######  monzodioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 10 percent feldspathoid or 0 to 20 percent
quartz in the QAPF fraction. Plagioclase to total feldspar ratio in
the QAPF fraction is between 0.65 and 0.9. Includes rocks defined
modally in QAPF field 9, 9' and 9* as monzodiorite, foid-beaing
monzodiorite, and quartz monzodiorite.

- **Source:**
This vocabulary; LeMaitre et al. 2002

- Concept URI token: Monzodioritic_Rock


[]{#foid_bearing_monzodiorite}

########  foid bearing monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 0 and 10 percent
feldspathoid mineral.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzodiorite


[]{#monzodiorite}

########  monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 5 percent quartz. Includes rocks defined
modally in QAPF field 9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzodiorite


[]{#quartz_monzodiorite}

########  quartz monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 5 and 20 percent quartz.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzodiorite


[]{#foid_dioritoid}

######  foid dioritoid


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


[]{#foid_diorite}

#######  foid diorite


- Child of:
 [`Foid_Dioritoid`](#Foid_Dioritoid)

- Foid dioritoid in which the plagioclase to total feldspar ratio is
greater than 0.9. Includes rocks defined modally in QAPF field 14.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Diorite


[]{#foid_monzodiorite}

#######  foid monzodiorite


- Child of:
 [`Foid_Dioritoid`](#Foid_Dioritoid)

- Foid dioritoid in which the plagioclase to total feldspar ratio is
between 0.1 and 0.9. Includes rocks defined modally in QAPF field 13.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Monzodiorite


[]{#foid_gabbroid}

######  foid gabbroid


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


[]{#foid_gabbro}

#######  foid gabbro


- Child of:
 [`Foid_Gabbroid`](#Foid_Gabbroid)

- Foid gabbroid that has a plagioclase to total feldspar ratio greater
than 0.9. Includes rocks defined modally in QAPF field 14.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Gabbro


[]{#foid_monzogabbro}

#######  foid monzogabbro


- Child of:
 [`Foid_Gabbroid`](#Foid_Gabbroid)

- Foid gabbroid that has a plagioclase to total feldspar ratio between
0.5 and 0.9. Includes rocks defined modally in QAPF field 13.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Monzogabbro


[]{#foid_syenitoid}

######  foid syenitoid


- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline igneous rock with M less than 90, contains
between 10 and 60 percent feldspathoid mineral in the QAPF fraction,
and has a plagioclase to total feldspar ratio less than 0.5. Includes
QAPF fields 11 and 12.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Syenitoid


[]{#foid_monzosyenite}

#######  foid monzosyenite


- Child of:
 [`Foid_Syenitoid`](#Foid_Syenitoid)

- Foid syenitoid rock that has a plagioclase to total feldspar ratio
of between 0.1 and 0.5. Includes rocks defined modally in QAPF Field
12.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Monzosyenite


[]{#foid_syenite}

#######  foid syenite


- Child of:
 [`Foid_Syenitoid`](#Foid_Syenitoid)

- Foid syenitoid that has a plagioclase to total feldspar ratio of
less than 0.1. Includes rocks defined modally in QAPF field 11.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Syenite


[]{#foidolite}

######  foidolite


- Child of:
 [`Phaneritic_Igneous_Rock`](#Phaneritic_Igneous_Rock)

- Phaneritic crystalline rock containing more than 60 percent
feldspathoid minerals in the QAPF fraction. Includes rocks defined
modally in QAPF field 15

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foidolite


[]{#gabbroid}

######  gabbroid


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

#######  gabbroic rock


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


[]{#foid_bearing_gabbro}

########  foid bearing gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains 0-10 percent feldspathoid minerals and
no quartz in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Gabbro


[]{#gabbro}

########  gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF Field 10 as gabbro.
- Note that this category includes gabbro (sensu stricto) of LeMaitre
et al. 2002, but is broader, including the other rock types defined by
orthopyroxene-clinopyroxene-olivine-hornblende mineral ratios.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbro


[]{#quartz_gabbro}

########  quartz gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Gabbro


[]{#monzogabbroic_rock}

#######  monzogabbroic rock


- Child of:
 [`Gabbroid`](#Gabbroid)

- Gabbroid with a plagioclase to total feldspar ratio between 0.65 and
0.9. QAPF field 9, 9 prime and 9 asterisk

- **Source:**
LeMaitre et al. 2002, This vocabulary

- Concept URI token: Monzogabbroic_Rock


[]{#foid_bearing_monzogabbro}

########  foid bearing monzogabbro


- Child of:
 [`Monzogabbroic_Rock`](#Monzogabbroic_Rock)

- Monzogabbroic rock that contains 0 to 10 percent feldspathoid
mineral in the QAPF fraction. QAPF field 9'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzogabbro


[]{#monzogabbro}

########  monzogabbro


- Child of:
 [`Monzogabbroic_Rock`](#Monzogabbroic_Rock)

- Monzogabbroic rock that contains between 0 an 5 percent quartz and
no feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF field 9 .

- **Source:**
LeMaitre et al. 2002, This vocabulary

- Concept URI token: Monzogabbro


[]{#quartz_monzogabbro}

########  quartz monzogabbro


- Child of:
 [`Monzogabbroic_Rock`](#Monzogabbroic_Rock)

- Monzogabbroic rock that contains between 5 and 20 percent quartz in
the QAPF fraction. QAPF field 9*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzogabbro


[]{#granitoid}

######  granitoid


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

#######  alkali feldspar granite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

#######  granite


- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#monzogranite}

########  monzogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.35
and 0.65. QAPF field 3b.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzogranite


[]{#syenogranite}

########  syenogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.10
and 0.35. QAPF field 3a.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenogranite


[]{#granodiorite}

#######  granodiorite


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

#######  tonalite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#hornblendite}

######  hornblendite


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

######  pegmatite


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

######  peridotite


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

######  pyroxenite


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

######  quartz rich igneous rock


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

######  syenitoid


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


[]{#alkali_feldspar_syenitic_rock}

#######  alkali feldspar syenitic rock


- Child of:
 [`Syenitoid`](#Syenitoid)

- Syenitoid with a plagioclase to total feldspar ratio of less than
0.1. QAPF fields 6, 6*, and 6'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Syenitic_Rock


[]{#alkali_feldspar_syenite}

########  alkali feldspar syenite


- Child of:
 [`Alkali_Feldspar_Syenitic_Rock`](#Alkali_Feldspar_Syenitic_Rock)

- Alkali feldspar syenitic rock that contains 0-5 percent quartz and
no feldspathoid in the QAPF fraction. QAPF field 6.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Syenite


[]{#foid_bearing_alkali_feldspar_syenite}

########  foid bearing alkali feldspar syenite


- Child of:
 [`Alkali_Feldspar_Syenitic_Rock`](#Alkali_Feldspar_Syenitic_Rock)

- Alkali feldspar syenitic rock that contains 0-10 percent
feldspathoid mineral and no quartz in the QAPF fraction. QAPF field
6'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Alkali_Feldspar_Syenite


[]{#quartz_alkali_feldspar_syenite}

########  quartz alkali feldspar syenite


- Child of:
 [`Alkali_Feldspar_Syenitic_Rock`](#Alkali_Feldspar_Syenitic_Rock)

- Alkali feldspar syenitic rock that contains 5 to 20 percent quartz
and no feldspathoid in the QAPF fraction. QAPF field 6*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Alkali_Feldspar_Syenite


[]{#monzonitic_rock}

#######  monzonitic rock


- Child of:
 [`Syenitoid`](#Syenitoid)

- Syenitoid with a plagioclase to total feldspar ratio between 0.35
and 0.65. Includes rocks in QAPF fields 8, 8*, and 8'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzonitic_Rock


[]{#foid_bearing_monzonite}

########  foid bearing monzonite


- Child of:
 [`Monzonitic_Rock`](#Monzonitic_Rock)

- Monzonitic rock that contains 0-10 percent feldspathoid mineral and
no quartz in the QAPF fraction. Includes rocks defined modally in QAPF
Field 8'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzonite


[]{#monzonite}

########  monzonite


- Child of:
 [`Monzonitic_Rock`](#Monzonitic_Rock)

- Monzonitic rock that contains 0-5 percent quartz and no feldspathoid
mineral in the QAPF fraction. Includes rocks defined modally in QAPF
Field 8.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzonite


[]{#quartz_monzonite}

########  quartz monzonite


- Child of:
 [`Monzonitic_Rock`](#Monzonitic_Rock)

- Monzonitic rock that contains 5-20 percent quartz iin the QAPF
fraction. Includes rocks defined modally in QAPF Field 8*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzonite


[]{#syenitic_rock}

#######  syenitic rock


- Child of:
 [`Syenitoid`](#Syenitoid)

- Syenitoid with a plagioclase to total feldspar ratio between 0.1 and
0.35. Includes rocks in QAPF fields 7, 7*, and 7'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenitic_Rock


[]{#foid_bearing_syenite}

########  foid bearing syenite


- Child of:
 [`Syenitic_Rock`](#Syenitic_Rock)

- Syenitic rock that contains between 0 and 10 percent feldspathoid
mineral and no quartz in the QAPF fraction. Defined modally in QAPF
Field 7'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Syenite


[]{#quartz_syenite}

########  quartz syenite


- Child of:
 [`Syenitic_Rock`](#Syenitic_Rock)

- Syenitic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. Defined modally in QAPF Field 7*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Syenite


[]{#syenite}

########  syenite


- Child of:
 [`Syenitic_Rock`](#Syenitic_Rock)

- Syenitic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Defined modally in QAPF
Field 7.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenite


[]{#plutonic_igneous_rock}

#####  plutonic rock


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

#####  porphyry


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that contains conspicuous phenocrysts in a finer
grained groundmass; groundmass itself may be phaneritic or fine-
grained.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Porphyry


[]{#ultrabasic_igneous_rock}

#####  ultrabasic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock with less than 45 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Ultrabasic_Igneous_Rock


[]{#ultramafic_igneous_rock}

#####  ultramafic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)

- Igneous rock that consists of greater than 90 percent mafic
minerals.

- **Source:**
LeMaitre et al. 2002; Gillespie and Styles 1999

- Concept URI token: Ultramafic_Igneous_Rock


[]{#hornblendite}

######  hornblendite


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

######  peridotite


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

######  pyroxenite


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


[]{#komatiitic_rock}

######  komatiitic rock


- Child of:
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)
 [`Ultramafic_Igneous_Rock`](#Ultramafic_Igneous_Rock)

- Ultramafic, magnesium-rich volcanic rock, typically with spinifex
texture of intergrown skeletal and bladed olivine and pyroxene
crystals set in abundant glass. Includes komatiite and meimechite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Komatiitic_Rock


[]{#acidic_igneous_material}

####  acidic igneous material


- Child of:
 [`Igneous_Material`](#Igneous_Material)

- Igneous material with more than 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Acidic_Igneous_Material


[]{#acidic_igneous_rock}

#####  acidic igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Acidic_Igneous_Material`](#Acidic_Igneous_Material)

- Igneous rock with more than 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Acidic_Igneous_Rock


[]{#dacite}

######  dacite


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

######  granitoid


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

#######  alkali feldspar granite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitic rock that has a plagioclase to total feldspar ratio less
than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Granite


[]{#granite}

#######  granite


- Child of:
 [`Granitoid`](#Granitoid)

- Phaneritic crystalline rock consisting of quartz, alkali feldspar
and plagioclase (typically sodic) in variable amounts, usually with
biotite and/or hornblende. Includes rocks defined modally in QAPF
Field 3.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Granite


[]{#monzogranite}

########  monzogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.35
and 0.65. QAPF field 3b.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzogranite


[]{#syenogranite}

########  syenogranite


- Child of:
 [`Granite`](#Granite)

- Granite that has a plagiolcase to total feldspar ratio between 0.10
and 0.35. QAPF field 3a.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Syenogranite


[]{#granodiorite}

#######  granodiorite


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

#######  tonalite


- Child of:
 [`Granitoid`](#Granitoid)

- Granitoid consisting of quartz and intermediate plagioclase, usually
with biotite and amphibole. Includes rocks defined modally in QAPF
field 5; ratio of plagioclase to total feldspar is greater than 0.9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Tonalite


[]{#quartz_rich_igneous_rock}

######  quartz rich igneous rock


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

######  rhyolitoid


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


[]{#alkali_feldspar_rhyolite}

#######  alkali feldspar rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- Rhyolitoid in which the ratio of plagioclase to total feldspar is
less than 0.1. QAPF field 2.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Alkali_Feldspar_Rhyolite


[]{#rhyolite}

#######  rhyolite


- Child of:
 [`Rhyolitoid`](#Rhyolitoid)

- rhyolitoid in which the ratio of plagioclase to total feldspar is
between 0.1 and 0.65.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Rhyolite


[]{#basic_igneous_material}

####  basic igneous material


- Child of:
 [`Igneous_Material`](#Igneous_Material)

- Igneous material with between 45 and 52 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Basic_Igneous_Material


[]{#basic_igneous_rock}

#####  basic igneous rock
* `doleritic rock`


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Basic_Igneous_Material`](#Basic_Igneous_Material)

- Dark colored gabbroic (basaltic) or dioritic (andesitic) rock
intermediate in grain size between basalt and gabbro and composed of
plagioclase, pyroxene and opaque minerals; often with ophitic texture.
Typically occurs as hypabyssal intrusions. Includes dolerite,
microdiorite, diabase and microgabbro.
- Igneous rock with between 45 and 52 percent SiO2.

- **Source:**
Neuendorf et al 2005; LeMaitre et al. 2002; Gillespie and Styles 1999, 
after LeMaitre et al. 2002, 

- Concept URI token: Basic_Igneous_Rock


[]{#basalt}

######  basalt


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


[]{#alkali-olivine_basalt}

#######  alkali olivine basalt


- Child of:
 [`Basalt`](#Basalt)

- Alkali olivine basalt is silica-undersaturated, characterized by the
absence of orthopyroxene, absence of quartz, presence of olivine, and
typically contains some feldspathoid mineral, alkali feldspar or
phlogopite in the groundmass. Feldspar phenocrysts typically are
labradorite to andesine in composition. Augite is rich in titanium
compared to augite in tholeiitic basalt. Alkali olivine basalt is
relatively rich in sodium.
- The definition of tholeiite and alkali basalt here are more
prescriptive than those found in most reference authorities. This is
to actually provide some descriptive criteria to allow assignment of
rocks on a hand sample basis to the tholeiite or alkali basalt
categories if detailed petrographic or chemical data are available.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Alkali-Olivine_Basalt


[]{#tholeiitic_basalt}

#######  tholeiitic basalt


- Child of:
 [`Basalt`](#Basalt)

- Definition of tholeiite and alkali basalt here are more proscriptive
than those found in most reference authorities. This is to actually
provide some descriptive criteria to allow assignment of rocks on a
hand sample basis to the tholeiite or alkali basalt categories if
detailed petrographic or chemical data are available.
- Tholeiitic basalt is defined here to contain 2 pyroxene phases and
interstitial quartz or tridymite or cristobalite in the groundmass.
Pyroxene (augite and orthopyroxene or pigeonite) and calcium-rich
plagioclase are common phenocryst minerals. Olivine may also be a
phenocryst, and when present, may have rims of pigeonite. Only in
tholeiitic basalt is olivine in reaction relationship with melt.
Interstitial siliceous residue may be present, and is often glassy.
Tholeiitic basalt is relatively poor in sodium. This category includes
most basalts of the ocean floor, most large oceanic islands, and
continental flood basalts such as the Columbia River Plateau.

- **Source:**
http://en.wikipedia.org/wiki/Basalt; Carmichael, I.S. Turner, F.J., Verhoogen, John, 1974, Igneous petrology: New York, McGraw HIll Book Co., p.42-43.

- Concept URI token: Tholeiitic_Basalt


[]{#gabbroic_rock}

######  gabbroic rock


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


[]{#foid_bearing_gabbro}

#######  foid bearing gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains 0-10 percent feldspathoid minerals and
no quartz in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Gabbro


[]{#gabbro}

#######  gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 0 and 5 percent quartz and no
feldspathoid mineral in the QAPF fraction. Includes rocks defined
modally in QAPF Field 10 as gabbro.
- Note that this category includes gabbro (sensu stricto) of LeMaitre
et al. 2002, but is broader, including the other rock types defined by
orthopyroxene-clinopyroxene-olivine-hornblende mineral ratios.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Gabbro


[]{#quartz_gabbro}

#######  quartz gabbro


- Child of:
 [`Gabbroic_Rock`](#Gabbroic_Rock)

- Gabbroic rock that contains between 5 and 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Gabbro


[]{#fragmental_igneous_material}

####  fragmental igneous material


- Child of:
 [`Igneous_Material`](#Igneous_Material)

- igneous_material of unspecified consolidation state in which greater
than 75 percent of the rock consists of fragments produced as a result
of igneous rock-forming process.

- **Source:**
CGI concept definition task group

- Concept URI token: Fragmental_Igneous_Material


[]{#fragmental_igneous_rock}

#####  fragmental igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Fragmental_Igneous_Material`](#Fragmental_Igneous_Material)

- Igneous rock in which greater than 75 percent of the rock consists
of fragments produced as a result of igneous rock-forming process.
Includes pyroclastic rocks, autobreccia associated with lava flows and
intrusive breccias. Excludes deposits reworked by epiclastic processes
(see Tuffite)

- **Source:**
This vocabulary

- Concept URI token: Fragmental_Igneous_Rock


[]{#pyroclastic_material}

#####  pyroclastic material


- Child of:
 [`Fragmental_Igneous_Material`](#Fragmental_Igneous_Material)
 [`Volcanic_Material`](#Volcanic_Material)

- Fragmental igneous material that consists of more than 75 percent of
particles formed by disruption as a direct result of volcanic action.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Material


[]{#pyroclastic_rock}

######  pyroclastic rock


- Child of:
 [`Volcanic_Rock`](#Volcanic_Rock)
 [`Pyroclastic_Material`](#Pyroclastic_Material)

- Fragmental igneous rock that consists of greater than 75 percent
fragments produced as a direct result of eruption or extrusion of
magma from within the earth onto its surface. Includes autobreccia
associated with lava flows and excludes deposits reworked by
epiclastic processes.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Rock


[]{#ash_tuff_lapillistone_and_lapilli_tuff}

#######  ash tuff lapillistone and lapilli tuff


- Child of:
 [`Pyroclastic_Rock`](#Pyroclastic_Rock)

- Pyroclastic rock in which less than 25 percent of rock by volume are
more than 64 mm in longest diameter. Includes tuff, lapilli tuff, and
lapillistone.

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_Tuff_Lapillistone_And_Lapilli_Tuff


[]{#tuff_breccia_agglomerate_or_pyroclastic_breccia}

#######  tuff breccia agglomerate or pyroclastic breccia


- Child of:
 [`Pyroclastic_Rock`](#Pyroclastic_Rock)

- Pyroclastic rock in which greater than 25 percent of particles are
greater than 64 mm in largest dimension. Includes agglomerate,
pyroclastic breccia of Gillespie and Styles (1999)

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Tuff_Breccia_Agglomerate_Or_Pyroclastic_Breccia


[]{#tephra}

######  Tephra
* `tephra`


- Child of:
 [`Natural_Unconsolidated_Material`](#Natural_Unconsolidated_Material)
 [`Pyroclastic_Material`](#Pyroclastic_Material)


- **Source:**
Hallsworth and Knox 1999; LeMaitre et al. 2002

- Concept URI token: Tephra


[]{#ash_and_lapilli}

#######  ash and lapilli


- Child of:
 [`Tephra`](#Tephra)

- Tephra in which less than 25 percent of fragments are greater than
64 mm in longest dimension

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_And_Lapilli


[]{#ash_breccia_bomb_or_block_tephra}

#######  ash breccia bomb or block tephra


- Child of:
 [`Tephra`](#Tephra)

- Tephra in which more than 25 percent of particles are greater than
64 mm in largest dimension. Includes ash breccia, bomb tephra and
block tephra of Gillespie and Styles (1999)

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_Breccia_Bomb_Or_Block_Tephra


[]{#intermediate_composition_igneous_material}

####  intermediate composition igneous material


- Child of:
 [`Igneous_Material`](#Igneous_Material)

- Igneous material with between 52 and 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Intermediate_Composition_Igneous_Material


[]{#intermediate_composition_igneous_rock}

#####  intermediate composition igneous rock


- Child of:
 [`Igneous_Rock`](#Igneous_Rock)
 [`Intermediate_Composition_Igneous_Material`](#Intermediate_Composition_Igneous_Material)

- Igneous rock with between 52 and 63 percent SiO2.

- **Source:**
after LeMaitre et al. 2002

- Concept URI token: Intermediate_Composition_Igneous_Rock


[]{#andesite}

######  andesite


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


[]{#boninite}

#######  boninite


- Child of:
 [`Andesite`](#Andesite)
 [`High_Magnesium_Fine_Grained_Igneous_Rock`](#High_Magnesium_Fine_Grained_Igneous_Rock)

- andesitic rock that contains more than 8 percent MgO. Typically
consists of phenocrysts of protoenstatite, orthopyroxene,
clinopyroxene, and olivine in a glassy base full of crystallites, and
exhibits textures characterisitc of rapid crystal growth.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Boninite


[]{#dioritoid}

######  dioritoid


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


[]{#dioritic_rock}

#######  dioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline rock with M less than 90, consisting of
intermediate plagioclase, commonly with hornblende and often with
biotite or augite. A dioritoid with a plagioclase to total feldspar
ratio (in the QAPF fraction) greater than 0.9. Includes rocks defined
modally in QAPF fields 10, 10' and 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Dioritic_Rock


[]{#diorite}

########  diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Phaneritic crystalline rock consisting of intermediate plagioclase,
commonly with hornblende and often with biotite or augite; colour
index M less than 90, sodic plagioclase (An0-An50), no feldspathoid,
and between 0 and 5 percent quartz. Includes rocks defined modally in
QAPF field 10 as diorite.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Diorite


[]{#foid_bearing_diorite}

########  foid bearing diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 0 and 10 percent feldspathoid
minerals in the QAPF fraction. QAPF field 10'.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Diorite


[]{#quartz_diorite}

########  quartz diorite


- Child of:
 [`Dioritic_Rock`](#Dioritic_Rock)

- Dioritic rock that contains between 5 to 20 percent quartz in the
QAPF fraction. QAPF field 10*.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Diorite


[]{#monzodioritic_rock}

#######  monzodioritic rock


- Child of:
 [`Dioritoid`](#Dioritoid)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 10 percent feldspathoid or 0 to 20 percent
quartz in the QAPF fraction. Plagioclase to total feldspar ratio in
the QAPF fraction is between 0.65 and 0.9. Includes rocks defined
modally in QAPF field 9, 9' and 9* as monzodiorite, foid-beaing
monzodiorite, and quartz monzodiorite.

- **Source:**
This vocabulary; LeMaitre et al. 2002

- Concept URI token: Monzodioritic_Rock


[]{#foid_bearing_monzodiorite}

########  foid bearing monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 0 and 10 percent
feldspathoid mineral.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Foid_Bearing_Monzodiorite


[]{#monzodiorite}

########  monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Phaneritic crystalline igneous rock consisting of sodic plagioclase
(An0 to An50), alkali feldspar, hornblende and biotite, with or
without pyroxene, and 0 to 5 percent quartz. Includes rocks defined
modally in QAPF field 9.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Monzodiorite


[]{#quartz_monzodiorite}

########  quartz monzodiorite


- Child of:
 [`Monzodioritic_Rock`](#Monzodioritic_Rock)

- Monzodioritic rock that contains between 5 and 20 percent quartz.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Quartz_Monzodiorite


[]{#volcanic_material}

####  Volcanic Material
* `Volcanic Material`


- Child of:
 [`Igneous_Material`](#Igneous_Material)

- Material exhibiting features demonstrating an extrusive igneous
origin. Consolidated or non-consolidated {@en}
- Concept URI token: Volcanic_Material


[]{#volcanic_rock}

#####  volcanic rock


- Child of:
 [`Volcanic_Material`](#Volcanic_Material)

- Concept URI token: Volcanic_Rock


[]{#pyroclastic_rock}

######  pyroclastic rock


- Child of:
 [`Volcanic_Rock`](#Volcanic_Rock)
 [`Pyroclastic_Material`](#Pyroclastic_Material)

- Fragmental igneous rock that consists of greater than 75 percent
fragments produced as a direct result of eruption or extrusion of
magma from within the earth onto its surface. Includes autobreccia
associated with lava flows and excludes deposits reworked by
epiclastic processes.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Rock


[]{#ash_tuff_lapillistone_and_lapilli_tuff}

#######  ash tuff lapillistone and lapilli tuff


- Child of:
 [`Pyroclastic_Rock`](#Pyroclastic_Rock)

- Pyroclastic rock in which less than 25 percent of rock by volume are
more than 64 mm in longest diameter. Includes tuff, lapilli tuff, and
lapillistone.

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_Tuff_Lapillistone_And_Lapilli_Tuff


[]{#tuff_breccia_agglomerate_or_pyroclastic_breccia}

#######  tuff breccia agglomerate or pyroclastic breccia


- Child of:
 [`Pyroclastic_Rock`](#Pyroclastic_Rock)

- Pyroclastic rock in which greater than 25 percent of particles are
greater than 64 mm in largest dimension. Includes agglomerate,
pyroclastic breccia of Gillespie and Styles (1999)

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Tuff_Breccia_Agglomerate_Or_Pyroclastic_Breccia


[]{#lava}

######  Lava
* `Lava`


- Child of:
 [`Volcanic_Rock`](#Volcanic_Rock)

- Volcanic Rock with features indicating origin by extrusive lava
flow.
- Concept URI token: Lava


[]{#pyroclastic_material}

#####  pyroclastic material


- Child of:
 [`Fragmental_Igneous_Material`](#Fragmental_Igneous_Material)
 [`Volcanic_Material`](#Volcanic_Material)

- Fragmental igneous material that consists of more than 75 percent of
particles formed by disruption as a direct result of volcanic action.

- **Source:**
LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Material


[]{#pyroclastic_rock}

######  pyroclastic rock


- Child of:
 [`Volcanic_Rock`](#Volcanic_Rock)
 [`Pyroclastic_Material`](#Pyroclastic_Material)

- Fragmental igneous rock that consists of greater than 75 percent
fragments produced as a direct result of eruption or extrusion of
magma from within the earth onto its surface. Includes autobreccia
associated with lava flows and excludes deposits reworked by
epiclastic processes.

- **Source:**
based on LeMaitre et al. 2002

- Concept URI token: Pyroclastic_Rock


[]{#ash_tuff_lapillistone_and_lapilli_tuff}

#######  ash tuff lapillistone and lapilli tuff


- Child of:
 [`Pyroclastic_Rock`](#Pyroclastic_Rock)

- Pyroclastic rock in which less than 25 percent of rock by volume are
more than 64 mm in longest diameter. Includes tuff, lapilli tuff, and
lapillistone.

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_Tuff_Lapillistone_And_Lapilli_Tuff


[]{#tuff_breccia_agglomerate_or_pyroclastic_breccia}

#######  tuff breccia agglomerate or pyroclastic breccia


- Child of:
 [`Pyroclastic_Rock`](#Pyroclastic_Rock)

- Pyroclastic rock in which greater than 25 percent of particles are
greater than 64 mm in largest dimension. Includes agglomerate,
pyroclastic breccia of Gillespie and Styles (1999)

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Tuff_Breccia_Agglomerate_Or_Pyroclastic_Breccia


[]{#tephra}

######  Tephra
* `tephra`


- Child of:
 [`Natural_Unconsolidated_Material`](#Natural_Unconsolidated_Material)
 [`Pyroclastic_Material`](#Pyroclastic_Material)


- **Source:**
Hallsworth and Knox 1999; LeMaitre et al. 2002

- Concept URI token: Tephra


[]{#ash_and_lapilli}

#######  ash and lapilli


- Child of:
 [`Tephra`](#Tephra)

- Tephra in which less than 25 percent of fragments are greater than
64 mm in longest dimension

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_And_Lapilli


[]{#ash_breccia_bomb_or_block_tephra}

#######  ash breccia bomb or block tephra


- Child of:
 [`Tephra`](#Tephra)

- Tephra in which more than 25 percent of particles are greater than
64 mm in largest dimension. Includes ash breccia, bomb tephra and
block tephra of Gillespie and Styles (1999)

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_Breccia_Bomb_Or_Block_Tephra


[]{#sedimentary_material}

###  Sedimentary material


- Child of:
 [`Rock_Material`](#Rock_Material)

- Material formed by accumulation of solid fragmental material
deposited by air, water or ice, or material that accumulated by other
natural agents such as chemical precipitation from solution or
secretion by organisms. Includes both sediment and sedimentary rock.
Includes epiclastic deposits. All stated composition criteria are
based on the mineral/ compound material (GeoSciML term)/particulate
fraction of the material, irrespective of porosity or the pore-fluid.
No distinctions are made based on porosity or pore fluid composition
(except organic rich sediment in which liquid hydrocarbon content may
be considered).

- **Source:**
SLTTs 2004

- Concept URI token: Sedimentary_Material


[]{#chemical_sedimentary_material}

####  chemical sedimentary material


- Child of:
 [`Sedimentary_Material`](#Sedimentary_Material)

- Sedimentary material that consists of at least 50 percent material
produced by inorganic chemical processes within the basin of
deposition. Includes inorganic siliceous, carbonate, evaporite, iron-
rich, and phosphatic sediment classes.

- **Source:**
SLTTs 2004

- Concept URI token: Chemical_Sedimentary_Material


[]{#evaporite}

#####  evaporite


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)

- Nonclastic sedimentary rock composed of at least 50 percent non-
carbonate salts, including chloride, sulfate or borate minerals;
formed through precipitation of mineral salts from a saline solution
(non-carbonate salt rock).

- **Source:**
Jackson 1997; SLTTs 2004

- Concept URI token: Evaporite


[]{#exotic_evaporite}

######  exotic evaporite


- Child of:
 [`Evaporite`](#Evaporite)

- Category represents evaporite material that is not mostly
gypsum/anhydrite or halite. These are generally not very common, thus
the 'exotic' name
- Evaporite that is not 50 percent halite or 50 percent gypsum or
anhydrite.

- **Source:**
This vocabulary

- Concept URI token: Exotic_Evaporite


[]{#rock_gypsum_or_anhydrite}

######  gypsum or anhydrite


- Child of:
 [`Evaporite`](#Evaporite)

- Evaporite composed of at least 50 percent gypsum or anhydrite.

- **Source:**
This vocabulary

- Concept URI token: Rock_Gypsum_Or_Anhydrite


[]{#rock_salt}

######  rock salt


- Child of:
 [`Evaporite`](#Evaporite)

- Evaporite composed of at least 50 percent halite.

- **Source:**
This vocabulary

- Concept URI token: Rock_Salt


[]{#iron_rich_sedimentary_material}

#####  iron rich sedimentary material


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)

- Sedimentary material of unspecified consolidation state that
consists of at least 50 percent iron-bearing minerals (hematite,
magnetite, limonite-group, siderite, iron-sulfides), as determined by
hand-lens or petrographic analysis. Corresponds to a rock typically
containing 15 percent iron by weight.

- **Source:**
SLTTs 2004

- Concept URI token: Iron_Rich_Sedimentary_Material


[]{#iron_rich_sediment}

######  iron rich sediment


- Child of:
 [`sediment`](#sediment)
 [`Iron_Rich_Sedimentary_Material`](#Iron_Rich_Sedimentary_Material)

- Sediment that consists of at least 50 percent iron-bearing minerals
(hematite, magnetite, limonite-group, siderite, iron-sulfides), as
determined by hand-lens or petrographic analysis. Corresponds to a
rock typically containing 15 percent iron by weight.

- **Source:**
SLTTs 2004

- Concept URI token: Iron_Rich_Sediment


[]{#iron_rich_sedimentary_rock}

######  iron rich sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Iron_Rich_Sedimentary_Material`](#Iron_Rich_Sedimentary_Material)

- Sedimentary rock that consists of at least 50 percent iron-bearing
minerals (hematite, magnetite, limonite-group, siderite, iron-
sulfides), as determined by hand-lens or petrographic analysis.
Corresponds to a rock typically containing 15 percent iron by weight.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Iron_Rich_Sedimentary_Rock


[]{#sedimentary_massive_sulphide}

#####  Sedimentary Massive Sulphide


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Massive_Sulphide`](#Massive_Sulphide)

- rock consisting of greater than 50% sulphide or sulfosalt minerals
formed by sedimentary exhalative processes.

- **Alternate labels:**
Sedimentary Massive Sulfide


- **Source:**
smr provisional 2020-06-07

- Concept URI token: Sedimentary_Massive_Sulphide


[]{#travertine}

#####  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#sedimentary_rock}

####  Sedimentary rock
* `sedimentary rock`


- Child of:
 [`rock`](#rock)
 [`Sedimentary_Material`](#Sedimentary_Material)


- **Source:**
SLTTs 2004

- Concept URI token: Sedimentary_Rock


[]{#carbonate_sedimentary_rock}

#####  carbonate sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

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


[]{#boundstone}

######  boundstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary carbonate rock with preserved biogenic texture, whose
original components were bound and encrusted together during
deposition by the action of plants and animals during deposition, and
remained substantially in the position of growth.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Boundstone


[]{#calcareous_carbonate_sedimentary_rock}

######  calcareous carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
SLTTs 2004; Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sedimentary_Rock


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#carbonate_mudstone}

######  carbonate mudstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that consists of greater than 50 percent carbonate minerals
of any origin in the mud size fraction.
- Not a subcategory of carbonate sedimentary rock because definition
does not specify 'carbonate minerals of intrabasinal origin', but is
agnostic on origin of carbonate. Schnurrenberger et al. 2003 point out
that it is very difficult (at least in lacustrine rocks) to
distinguish chemically precipitated or diagenetic carbonate from
primary biogenic carbonate. This distinction between biogenic,
detrital, and pedogenic or authigenic carbonate material is thus not a
good one to use in a general purpose classification system.
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Mudstone


[]{#carbonate_wackestone}

######  carbonate wackestone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with discernible mud supported
depositional texture and containing greater than 10 percent allochems,
and constituent particles are of intrabasinal origin. If particles are
not intrabasinal, categorization as a mudstone or wackestone should be
considered.

- **Source:**
Dunham 1962

- Concept URI token: Carbonate_Wackestone


[]{#crystalline_carbonate}

######  crystalline carbonate


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate rock of indeterminate mineralogy in which diagenetic
processes have obliterated any original depositional texture.

- **Source:**
SLTTs 2004

- Concept URI token: Crystalline_Carbonate


[]{#dolomitic_or_magnesian_sedimentary_rock}

######  dolomitic or magnesian sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sedimentary rock with a ratio of magnesium carbonate to
calcite (plus aragonite) greater than 1 to 1. Includes dolostone, lime
dolostone and magnesite-stone.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Or_Magnesian_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#framestone}

######  framestone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate reef rock consisting of a rigid framework of colonies,
shells or skeletons, with internal cavities filled with fine sediment;
usually created through the activities of colonial organisms.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004, Table 15-3-1

- Concept URI token: Framestone


[]{#grainstone}

######  grainstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with recognizable depositional fabric
that is grain-supported, and constituent particles are of intrabasinal
origin; contains little or no mud matrix. Distinction from sandstone
is based on interpretation of intrabasinal origin of clasts and grain-
supported fabric, but grainstone definition does not include a grain
size criteria.

- **Alternate labels:**
carbonate grainstone


- **Source:**
Dunham 1962

- Concept URI token: Grainstone


[]{#impure_carbonate_sedimentary_rock}

######  impure carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary rock in which between 50 and 90 percent of the primary
and/or recrystallized constituents are composed of carbonate minerals.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Carbonate_Sedimentary_Rock


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#packstone}

######  packstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with discernible grain supported
depositional texture, containing greater than 10 percent grains, and
constituent particles are of intrabasinal origin; intergranular spaces
are filled by matrix.
- Note that this category overlaps with 'carbonate mudstone'.

- **Source:**
Hallsworth and Knox 1999

- Concept URI token: Packstone


[]{#pure_carbonate_sedimentary_rock}

######  pure carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary rock in which greater than 90 percent of the primary
and/or recrystallized constituents are carbonate minerals.

- **Source:**
This vocabulary

- Concept URI token: Pure_Carbonate_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#pure_carbonate_mudstone}

#######  pure carbonate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Mudstone that consists of greater than 90 percent carbonate minerals
of intrabasinal orign in the mud fraction, and contains less than 10
percent allochems. The original depositional texture is preserved and
fabric is matrix supported. Carbonate mudstone of Dunham (1962)

- **Source:**
Dunham 1962

- Concept URI token: Pure_Carbonate_Mudstone


[]{#clastic_sedimentary_rock}

#####  clastic sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Clastic_Sedimentary_Material`](#Clastic_Sedimentary_Material)

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

######  diamictite


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


[]{#clastic_conglomerate}

######  conglomerate


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Conglomerate`](#Generic_Conglomerate)

- Clastic sedimentary rock composed of at least 30 percent rounded to
subangular fragments larger than 2 mm in diameter; typically contains
finer grained material in interstices between larger fragments. If
more than 15 percent of the fine grained matrix is of indeterminant
clastic or diagenetic origin and the fabric is matrix supported, may
also be categorized as wackestone. If rock has unsorted or poorly
sorted texture with a wide range of particle sizes, may also be
categorized as diamictite.
- Note this category is equivlanet to category labeled 'Conglomeratic
rock in SLTTs (2004), not to the category labeled 'Conglomerate' in
that system.

- **Alternate labels:**
conglomeratic rock


- **Source:**
Neuendorf et al. 2005; SLTTs 2004

- Concept URI token: Clastic_Conglomerate


[]{#clastic_mudstone}

######  mudstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Clastic sedimentary rock consisting of less than 30 percent gravel-
size (2 mm) particles and with a mud to sand ratio greater than 1.
- Distinction of intrabasinal, diagenetic, or clastic genesis for very
fine-grained carbonate minerals is interpretive in many cases. If
there is uncertainty on the mudstone category based on intrabasinal vs
epiclastic distinction required for clastic sedimentary rock-carbonate
sedimentary rock categorization in this system, it is recommended to
use the generic_mudstone category. This category is the union of the
various fields labeled 'mudstone' with various qualifiers in Folk,
1954, Figure 1a, although Folk's (1954) category labeled 'mudstone' is
a much more restricted category. The CGI category is equivalent to
category labeled 'Mudrock' in SLTTs (2004), not to the category
labeled 'Mudstone' adopted by that system from Folk (1954).
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
clastic mudstone, 
mudrock, 


- **Source:**
Pettijohn et al. 1987 referenced in Hallsworth and Knox 1999.

- Concept URI token: Clastic_Mudstone


[]{#claystone}

#######  claystone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains no detectable silt, inferred to consist
virtually entirely of clay-size particles.

- **Source:**
This vocabulary

- Concept URI token: Claystone


[]{#shale}

#######  shale


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Laminated mudstone that will part or break along thin, closely
spaced layers parallel to stratification.
- Note definition does not specify carbonate vs. siliclastic nature of
mud.

- **Source:**
NADM SLTT sedimentary, 2004

- Concept URI token: Shale


[]{#siltstone}

#######  siltstone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains detectable silt. (see comments)
- Use of 'dectable silt' in the criteria for this category is based on
the observation that in practice, distinction of claystone from
'siltstone' is typically based on a qualitative assessment of
'grittiness' (e.g. rubbing with fingers, or chewing); the property
that these tests can determine is the presence or absence of silty
particles in the material. Quantitative grain size analysis in the the
clay/silt fraction of a lithified sediment is difficult at best, and
of questionable significance because diagensis has altered the size
and mineralogy of original sedimentary particles.

- **Alternate labels:**
Silt bearing mudstone


- **Source:**
This vocabulary

- Concept URI token: Siltstone


[]{#clastic_sandstone}

######  sandstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Sandstone`](#Generic_Sandstone)

- Clastic sedimentary rock in which less than 30 percent of particles
are greater than 2 mm in diameter (gravel) and the sand to mud ratio
is at least 1.
- Note this category is equivalent to cagetory labeled 'sandy rock' in
SLTTs (2004), not to the much more restricted category labeled
'Sandstone' in that system.

- **Alternate labels:**
clastic sandstone, 
sandy rock, 


- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clastic_Sandstone


[]{#arenite}

#######  arenit
* `arenite`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone that contains less than 10 percent matrix. Matrix
is mud-size silicate minerals (clay, feldspar, quartz, rock fragments,
and alteration products) of detrital or diagenetic nature.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Arenite


[]{#wacke}

#######  piedra
* `wacke`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone with more than 10 percent matrix of indeterminate
detrital or diagenetic nature. Matrix is mud size silicate minerals
(clay, feldspar, quartz, rock fragments, and alteration products).
- Distinction from mudstone is based on inference that less that 50
percent of the mud size fraction (matrix) is original mud size
detrital particles. May also grade into diamictite or conglomerate
based on size distribution of discernible particles. If more than 50
percent of rock is detrital particles of intrabasinal orgin and
carbonate composition, categorize as carbonate wackestone. Term is
typically applied to diagenetically altered volcanic-lithic clastic
rocks in which the definition of the original clasts has been
obscured. Suggested boundaries between wacke and arenite range from 5
to 15 percent matrix. See Dickinson (1970) for discussion of
interpretation of undiscernible matrix in diagenetically altered
lithic clastic rocks. Dickinson, W.R., 1970, Interpreting detrital
modes of graywacke and arkose: Journal of Sedimentary Petrology, v.
40, p. 695-707.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Wacke


[]{#generic_conglomerate}

#####  generic conglomerate


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


[]{#clastic_conglomerate}

######  conglomerate


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Conglomerate`](#Generic_Conglomerate)

- Clastic sedimentary rock composed of at least 30 percent rounded to
subangular fragments larger than 2 mm in diameter; typically contains
finer grained material in interstices between larger fragments. If
more than 15 percent of the fine grained matrix is of indeterminant
clastic or diagenetic origin and the fabric is matrix supported, may
also be categorized as wackestone. If rock has unsorted or poorly
sorted texture with a wide range of particle sizes, may also be
categorized as diamictite.
- Note this category is equivlanet to category labeled 'Conglomeratic
rock in SLTTs (2004), not to the category labeled 'Conglomerate' in
that system.

- **Alternate labels:**
conglomeratic rock


- **Source:**
Neuendorf et al. 2005; SLTTs 2004

- Concept URI token: Clastic_Conglomerate


[]{#generic_mudstone}

#####  generic mudstone


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


[]{#carbonate_mudstone}

######  carbonate mudstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that consists of greater than 50 percent carbonate minerals
of any origin in the mud size fraction.
- Not a subcategory of carbonate sedimentary rock because definition
does not specify 'carbonate minerals of intrabasinal origin', but is
agnostic on origin of carbonate. Schnurrenberger et al. 2003 point out
that it is very difficult (at least in lacustrine rocks) to
distinguish chemically precipitated or diagenetic carbonate from
primary biogenic carbonate. This distinction between biogenic,
detrital, and pedogenic or authigenic carbonate material is thus not a
good one to use in a general purpose classification system.
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Mudstone


[]{#carbonate_rich_mudstone}

######  carbonate rich mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)

- Carbonate-rich mudstone' definition limits carbonate to mud-size
fraction to avoid overlap with 'impure carbonate sedimentary rock'. If
carbonate minerals are in sand or gravel size fractions, use 'impure
carbonate sedimentary rock'. The operational test typically used to
identify this category is if the rock fizzes when hydrochloric acid is
applied. The '10 percent carbonate' criteria is a fuzzy boundary.
- Mudstone that contains between 10 and 50 percent carbonate minerals
in the mud size fraction. Carbonate origin is not specified.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Rich_Mudstone


[]{#clastic_mudstone}

######  mudstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Clastic sedimentary rock consisting of less than 30 percent gravel-
size (2 mm) particles and with a mud to sand ratio greater than 1.
- Distinction of intrabasinal, diagenetic, or clastic genesis for very
fine-grained carbonate minerals is interpretive in many cases. If
there is uncertainty on the mudstone category based on intrabasinal vs
epiclastic distinction required for clastic sedimentary rock-carbonate
sedimentary rock categorization in this system, it is recommended to
use the generic_mudstone category. This category is the union of the
various fields labeled 'mudstone' with various qualifiers in Folk,
1954, Figure 1a, although Folk's (1954) category labeled 'mudstone' is
a much more restricted category. The CGI category is equivalent to
category labeled 'Mudrock' in SLTTs (2004), not to the category
labeled 'Mudstone' adopted by that system from Folk (1954).
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
clastic mudstone, 
mudrock, 


- **Source:**
Pettijohn et al. 1987 referenced in Hallsworth and Knox 1999.

- Concept URI token: Clastic_Mudstone


[]{#claystone}

#######  claystone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains no detectable silt, inferred to consist
virtually entirely of clay-size particles.

- **Source:**
This vocabulary

- Concept URI token: Claystone


[]{#shale}

#######  shale


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Laminated mudstone that will part or break along thin, closely
spaced layers parallel to stratification.
- Note definition does not specify carbonate vs. siliclastic nature of
mud.

- **Source:**
NADM SLTT sedimentary, 2004

- Concept URI token: Shale


[]{#siltstone}

#######  siltstone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains detectable silt. (see comments)
- Use of 'dectable silt' in the criteria for this category is based on
the observation that in practice, distinction of claystone from
'siltstone' is typically based on a qualitative assessment of
'grittiness' (e.g. rubbing with fingers, or chewing); the property
that these tests can determine is the presence or absence of silty
particles in the material. Quantitative grain size analysis in the the
clay/silt fraction of a lithified sediment is difficult at best, and
of questionable significance because diagensis has altered the size
and mineralogy of original sedimentary particles.

- **Alternate labels:**
Silt bearing mudstone


- **Source:**
This vocabulary

- Concept URI token: Siltstone


[]{#organic_bearing_mudstone}

######  organic bearing mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that contains a significant amount of organic carbon,
typically kerogen. commonly finely laminated, brown or black in color.

- **Alternate labels:**
oil shale


- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Oil_shale

- Concept URI token: Organic_Bearing_Mudstone


[]{#pure_carbonate_mudstone}

######  pure carbonate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Mudstone that consists of greater than 90 percent carbonate minerals
of intrabasinal orign in the mud fraction, and contains less than 10
percent allochems. The original depositional texture is preserved and
fabric is matrix supported. Carbonate mudstone of Dunham (1962)

- **Source:**
Dunham 1962

- Concept URI token: Pure_Carbonate_Mudstone


[]{#silicate_mudstone}

######  silicate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that contains less than 10 percent carbonate minerals.
- Operational distinction of this category will typically be based on
whether or not the rock fizzes when hydrochloric acid is applied--the
rock is silicate mudstone if it does not fizz. The quantitative '10
percent' criteria is fuzzy.

- **Source:**
This vocabulary

- Concept URI token: Silicate_Mudstone


[]{#generic_sandstone}

#####  Generic sandstone
* `generic sandstone`


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)

- Sedimentary rock in which less than 30 percent of particles are
greater than 2 mm in diameter (gravel) and the sand to mud ratio is at
least 1.

- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Generic_Sandstone


[]{#clastic_sandstone}

######  sandstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Sandstone`](#Generic_Sandstone)

- Clastic sedimentary rock in which less than 30 percent of particles
are greater than 2 mm in diameter (gravel) and the sand to mud ratio
is at least 1.
- Note this category is equivalent to cagetory labeled 'sandy rock' in
SLTTs (2004), not to the much more restricted category labeled
'Sandstone' in that system.

- **Alternate labels:**
clastic sandstone, 
sandy rock, 


- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clastic_Sandstone


[]{#arenite}

#######  arenit
* `arenite`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone that contains less than 10 percent matrix. Matrix
is mud-size silicate minerals (clay, feldspar, quartz, rock fragments,
and alteration products) of detrital or diagenetic nature.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Arenite


[]{#wacke}

#######  piedra
* `wacke`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone with more than 10 percent matrix of indeterminate
detrital or diagenetic nature. Matrix is mud size silicate minerals
(clay, feldspar, quartz, rock fragments, and alteration products).
- Distinction from mudstone is based on inference that less that 50
percent of the mud size fraction (matrix) is original mud size
detrital particles. May also grade into diamictite or conglomerate
based on size distribution of discernible particles. If more than 50
percent of rock is detrital particles of intrabasinal orgin and
carbonate composition, categorize as carbonate wackestone. Term is
typically applied to diagenetically altered volcanic-lithic clastic
rocks in which the definition of the original clasts has been
obscured. Suggested boundaries between wacke and arenite range from 5
to 15 percent matrix. See Dickinson (1970) for discussion of
interpretation of undiscernible matrix in diagenetically altered
lithic clastic rocks. Dickinson, W.R., 1970, Interpreting detrital
modes of graywacke and arkose: Journal of Sedimentary Petrology, v.
40, p. 695-707.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Wacke


[]{#hybrid_sedimentary_rock}

#####  hybrid sedimentary rock


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

#####  iron rich sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Iron_Rich_Sedimentary_Material`](#Iron_Rich_Sedimentary_Material)

- Sedimentary rock that consists of at least 50 percent iron-bearing
minerals (hematite, magnetite, limonite-group, siderite, iron-
sulfides), as determined by hand-lens or petrographic analysis.
Corresponds to a rock typically containing 15 percent iron by weight.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Iron_Rich_Sedimentary_Rock


[]{#non_clastic_siliceous_sedimentary_rock}

#####  non clastic siliceous sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Non_Clastic_Siliceous_Sedimentary_Material`](#Non_Clastic_Siliceous_Sedimentary_Material)

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


[]{#biogenic_silica_sedimentary_rock}

######  biogenic silica sedimentary rock


- Child of:
 [`Non_Clastic_Siliceous_Sedimentary_Rock`](#Non_Clastic_Siliceous_Sedimentary_Rock)

- Sedimentary rock that consists of at least 50 percent silicate
mineral material, deposited directly by biological processes at the
depositional surface, or in particles formed by biological processes
within the basin of deposition. Includes radiolarian chert, diatomite,
novaculite.

- **Source:**
based on NADM SLTT sedimentary; Hallsworth and Knox 1999

- Concept URI token: Biogenic_Silica_Sedimentary_Rock


[]{#organic_rich_sedimentary_rock}

#####  organic rich sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Organic_Rich_Sedimentary_Material`](#Organic_Rich_Sedimentary_Material)

- Sapropelic coal, and asphaltite are not differentiated in This
vocabulary
- Sedimentary rock with color, composition, texture and apparent
density indicating greater than 50 percent organic content by weight
on a moisture-free basis.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sedimentary_Rock


[]{#coal}

######  coal
* `kohle`


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


[]{#anthracite_coal}

#######  anthracite
* `anthrazit`


- Child of:
 [`Coal`](#Coal)

- Coal that has vitrinite mean random reflectance greater than 2.0%
(determined in conformance with ISO 7404-5). Less than 12-14 percent
volatiles (dry, ash free), greater than 91 percent fixed carbon (dry,
ash free basis). The highest rank coal; very hard, glossy, black, with
semimetallic luster, semi conchoidal fracture.

- **Alternate labels:**
High rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp; see also Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Coal#Types_of_coal; Eberhard Lindner; Chemie für Ingenieure; Lindner Verlag Karlsruhe, S. 258

- Concept URI token: Anthracite_Coal


[]{#bituminous_coal}

#######  bituminous coal


- Child of:
 [`Coal`](#Coal)

- Coal that has vitrinite mean random reflectance greater than 0.6%
and less than 2.0% (determined in conformance with ISO 7404-5), or has
a gross calorific value greater than 24 MJ/kg (determined in
conformance with ISO 1928). Hard, black, organic rich sedimentary
rock; contains less than 91 percent fixed carbon on a dry, mineral-
matter-free basis, and greater than 13-14 percent volatiles (dry, ash
free). Formed from the compaction or induration of variously altered
plant remains similar to those of peaty deposits.

- **Alternate labels:**
medium rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp; see also http://en.wikipedia.org/wiki/Coal#Types_of_coal; Eberhard Lindner; Chemie für Ingenieure; Lindner Verlag Karlsruhe, S. 258

- Concept URI token: Bituminous_Coal


[]{#lignite}

#######  lignite


- Child of:
 [`Coal`](#Coal)

- Coal that has a gross calorific value less than 24 MJ/kg (determined
in conformance with ISO 1928), and vitrinite mean random reflectance
less than 0.6% (determined in conformance with ISO 7404-5). Gross
calorific value is recalculated to a moist, ash free basis using bed
moisture (determined according to ISO 1015 or ISO 5068). Includes all
low-rank coals, including sub-bitiminous coal. A consolidated, dull,
soft brown to black coal having many readily discernible plant
fragments set in a finer grained organic matrix. Tends to crack and
fall apart on drying. Operationally sub-bituminous and bitiminous coal
are qualitatively distinguished based on brown streak for sub-
bitiminous coal and black streak for bituminous coal.

- **Alternate labels:**
low rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp.

- Concept URI token: Lignite


[]{#phosphorite}

#####  phosphorite


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Phosphate_Rich_Sedimentary_Material`](#Phosphate_Rich_Sedimentary_Material)

- Sedimentary rock in which at least 50 percent of the primary or
recrystallized constituents are phosphate minerals. Most commonly
occurs as a bedded primary or reworked secondary marine rock, composed
of microcrystalline carbonate fluorapatite in the form of lamina,
pellets, oolites and nodules, and skeletal, shell and bone fragments.

- **Source:**
HallsworthandKnox 1999, Jackson 1997

- Concept URI token: Phosphorite


[]{#sediment}

####  sediment


- Child of:
 [`Natural_Unconsolidated_Material`](#Natural_Unconsolidated_Material)
 [`Sedimentary_Material`](#Sedimentary_Material)

- Unconsolidated material consisting of an aggregation of particles
transported or deposited by air, water or ice, or that accumulated by
other natural agents, such as chemical precipitation, and that forms
in layers on the Earth's surface. Includes epiclastic deposits.

- **Source:**
SLTTs 2004

- Concept URI token: sediment


[]{#biogenic_sediment}

#####  biogenic sediment


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


[]{#ooze}

######  ooze


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Biogenic sediment consisting of less than 1 percent gravel-size
(greater than or equal to 2 mm) particles, with a sand to mud ratio
less than 1 to 9, and less than 50 percent carbonate minerals.
- Neuendorf et al. 2005 put cutoff at 30 percent skeletal remains;
this is raised to 50 percent in This vocabulary for consistency with
definition of other Biogenic sediment category

- **Alternate labels:**
biogenic mud


- **Source:**
based on Bates and Jackson 1987 and Hallsworth and Knox 1999

- Concept URI token: Ooze


[]{#carbonate_ooze}

#######  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#siliceous_ooze}

#######  siliceous ooze


- Child of:
 [`Ooze`](#Ooze)
 [`Silicate_Mud`](#Silicate_Mud)

- ooze that consists of more than 50 percent siliceous skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Siliceous_Ooze


[]{#organic_rich_sediment}

######  organic rich sediment


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Organic_Rich_Sedimentary_Material`](#Organic_Rich_Sedimentary_Material)

- Sediment with color, composition, texture and apparent density
indicating greater than 50 percent organic content by weight on a
moisture-free basis.
- The broader relation from organic rich sediment to biogenic sediment
is based on the inference that organic rich material is always
biogenic in origin. Biogenic is a broader category because not all
biogenic materials are organic rich, for example shells or phosphatic
bone.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sediment


[]{#peat}

#######  peat


- Child of:
 [`Organic_Rich_Sediment`](#Organic_Rich_Sediment)

- Unconsolidated organic-rich sediment composed of at least 50 percent
semi-carbonised plant remains; individual remains commonly seen with
unaided eye; yellowish brown to brownish black; generally fibrous
texture; can be plastic or friable. In its natural state it can be
readily cut and has a very high moisture content, generally greater
than 90 percent. Liptinite to Inertinite ratio is less than one
(Economic commission for Europe, committee on Sustainable Energy-
United Nations (ECE-UN), 1998, International Classification of in-Seam
Coals: Energy 19, 41 pp.)

- **Source:**
Hallsworth and Knox 1999

- Concept URI token: Peat


[]{#sapropel}

#######  sapropel


- Child of:
 [`Organic_Rich_Sediment`](#Organic_Rich_Sediment)

- Jelly like organic rich sediment composed of plant remains, usually
algal. Liptinite to Inertinite ratio is greater than one (Economic
commission for Europe, committee on Sustainable Energy- United Nations
(ECE-UN), 1998, International Classification of in-Seam Coals: Energy
19, 41 pp.)

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Sapropel


[]{#carbonate_sediment}

#####  carbonate sediment


- Child of:
 [`sediment`](#sediment)
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

- Sediment in which at least 50 percent of the primary and/or
recrystallized constituents are composed of one (or more) of the
carbonate minerals calcite, aragonite and dolomite, in particles of
intrabasinal origin.

- **Source:**
SLTTs 2004

- Concept URI token: Carbonate_Sediment


[]{#calcareous_carbonate_sediment}

######  calcareous carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sediment with a calcite (plus aragonite) to dolomite ratio
greater than 1 to 1. Includes lime-sediments.

- **Source:**
after Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

#######  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

#######  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#carbonate_mud}

######  carbonate mud


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Carbonate sediment composed of less than 25 percent clasts that have
a maximum diameter more than 2 mm, and the ratio of sand size to mud
size clasts is less than one.

- **Alternate labels:**
marl


- **Source:**
follow pattern used for clastic sand and mud categories, based on SLTTs 2004

- Concept URI token: Carbonate_Mud


[]{#carbonate_ooze}

#######  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#dolomitic_sediment}

######  dolomitic sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sediment with a ratio of magnesium carbonate to calcite
(plus aragonite) greater than 1 to 1.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Sediment


[]{#impure_dolomitic_sediment}

#######  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_dolomitic_sediment}

#######  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#impure_carbonate_sediment}

######  impure carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin.

- **Alternate labels:**
marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

#######  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#impure_dolomitic_sediment}

#######  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_carbonate_sediment}

######  pure carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin.

- **Source:**
This vocabulary

- Concept URI token: Pure_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

#######  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#pure_dolomitic_sediment}

#######  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#clastic_sediment}

#####  clastic sediment


- Child of:
 [`sediment`](#sediment)
 [`Clastic_Sedimentary_Material`](#Clastic_Sedimentary_Material)

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

######  diamicton


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


[]{#gravel}

######  gravel


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Clastic sediment containing greater than 30 percent gravel-size
particles (greater than 2.0 mm diameter). Gravel in which more than
half of the particles are of epiclastic origin

- **Source:**
definition of gravel from SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel


[]{#mud}

######  mud


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Clastic sediment consisting of less than 30 percent gravel-size (2
mm) particles and with a mud-size to sand-size particle ratio greater
than 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of mud from SLTTs 2004 muddy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud


[]{#clay}

#######  clay


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent particles with grain
size less than 0.004 mm

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clay


[]{#silt}

#######  silt


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent silt-size grains.

- **Alternate labels:**
loess


- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Silt


[]{#sand}

######  sand


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Sand_Size_Sediment`](#Sand_Size_Sediment)

- Clastic sediment in which less than 30 percent of particles are
gravel (greater than 2 mm in diameter) and the sand to mud ratio is at
least 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of sand from SLTTs 2004 sandy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand


[]{#gravel_size_sediment}

#####  gravel size sediment


- Child of:
 [`sediment`](#sediment)

- Sediment containing greater than 30 percent gravel-size particles
(greater than 2.0 mm diameter). Composition or gensis of clasts not
specified.

- **Source:**
SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel_Size_Sediment


[]{#boulder_gravel_size_sediment}

######  boulder gravel size sediment


- Child of:
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Sediment containing greater than 30 percent boulder-size particles
(greater than 256 mm in diameter)

- **Source:**
Wentworth size scale

- Concept URI token: Boulder_Gravel_Size_Sediment


[]{#cobble_gravel_size_sediment}

######  cobble gravel size sediment


- Child of:
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Sediment containing greater than 30 percent cobble-size particles
(64-256 mm in diameter)

- **Source:**
Wentworth size scale

- Concept URI token: Cobble_Gravel_Size_Sediment


[]{#gravel}

######  gravel


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Clastic sediment containing greater than 30 percent gravel-size
particles (greater than 2.0 mm diameter). Gravel in which more than
half of the particles are of epiclastic origin

- **Source:**
definition of gravel from SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel


[]{#pebble_gravel_size_sediment}

######  pebble gravel size sediment


- Child of:
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Sediment containing greater than 30 percent pebble-size particles
(2.0 -64 mm in diameter)

- **Source:**
Wentworth size scale

- Concept URI token: Pebble_Gravel_Size_Sediment


[]{#hybrid_sediment}

#####  Hybrid sediment
* `hybrid sediment`


- Child of:
 [`sediment`](#sediment)


- **Source:**
Hallsworth and Knox, 1999

- Concept URI token: Hybrid_Sediment


[]{#iron_rich_sediment}

#####  iron rich sediment


- Child of:
 [`sediment`](#sediment)
 [`Iron_Rich_Sedimentary_Material`](#Iron_Rich_Sedimentary_Material)

- Sediment that consists of at least 50 percent iron-bearing minerals
(hematite, magnetite, limonite-group, siderite, iron-sulfides), as
determined by hand-lens or petrographic analysis. Corresponds to a
rock typically containing 15 percent iron by weight.

- **Source:**
SLTTs 2004

- Concept URI token: Iron_Rich_Sediment


[]{#mud_size_sediment}

#####  mud size sediment


- Child of:
 [`sediment`](#sediment)

- Sediment consisting of less than 30 percent gravel-size (2 mm)
particles and with a mud-size to sand-size particle ratio greater than
1. Clasts may be of any composition or origin.

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud_Size_Sediment


[]{#carbonate_mud}

######  carbonate mud


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Carbonate sediment composed of less than 25 percent clasts that have
a maximum diameter more than 2 mm, and the ratio of sand size to mud
size clasts is less than one.

- **Alternate labels:**
marl


- **Source:**
follow pattern used for clastic sand and mud categories, based on SLTTs 2004

- Concept URI token: Carbonate_Mud


[]{#carbonate_ooze}

#######  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#carbonate_rich_mud}

######  carbonate rich mud


- Child of:
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Mud size sediment that contains between 10 and 50 percent carbonate
minerals in any size fraction. Carbonate origin is not specified.

- **Alternate labels:**
carbonate rich loess, 
marl, 


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Rich_Mud


[]{#mud}

######  mud


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Clastic sediment consisting of less than 30 percent gravel-size (2
mm) particles and with a mud-size to sand-size particle ratio greater
than 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of mud from SLTTs 2004 muddy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud


[]{#clay}

#######  clay


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent particles with grain
size less than 0.004 mm

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clay


[]{#silt}

#######  silt


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent silt-size grains.

- **Alternate labels:**
loess


- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Silt


[]{#ooze}

######  ooze


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Biogenic sediment consisting of less than 1 percent gravel-size
(greater than or equal to 2 mm) particles, with a sand to mud ratio
less than 1 to 9, and less than 50 percent carbonate minerals.
- Neuendorf et al. 2005 put cutoff at 30 percent skeletal remains;
this is raised to 50 percent in This vocabulary for consistency with
definition of other Biogenic sediment category

- **Alternate labels:**
biogenic mud


- **Source:**
based on Bates and Jackson 1987 and Hallsworth and Knox 1999

- Concept URI token: Ooze


[]{#carbonate_ooze}

#######  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#siliceous_ooze}

#######  siliceous ooze


- Child of:
 [`Ooze`](#Ooze)
 [`Silicate_Mud`](#Silicate_Mud)

- ooze that consists of more than 50 percent siliceous skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Siliceous_Ooze


[]{#silicate_mud}

######  silicate mud


- Child of:
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Mud size sediment that consists of less than 50 percent carbonate
minerals.

- **Source:**
This vocabulary

- Concept URI token: Silicate_Mud


[]{#siliceous_ooze}

#######  siliceous ooze


- Child of:
 [`Ooze`](#Ooze)
 [`Silicate_Mud`](#Silicate_Mud)

- ooze that consists of more than 50 percent siliceous skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Siliceous_Ooze


[]{#non_clastic_siliceous_sediment}

#####  non clastic siliceous sediment


- Child of:
 [`sediment`](#sediment)
 [`Non_Clastic_Siliceous_Sedimentary_Material`](#Non_Clastic_Siliceous_Sedimentary_Material)


- **Source:**
NGMDB 2008; Hallsworth and Knox 1999

- Concept URI token: Non_Clastic_Siliceous_Sediment


[]{#phosphate_rich_sediment}

#####  phosphate rich sediment


- Child of:
 [`sediment`](#sediment)
 [`Phosphate_Rich_Sedimentary_Material`](#Phosphate_Rich_Sedimentary_Material)


- **Source:**
SLTTs 2004

- Concept URI token: Phosphate_Rich_Sediment


[]{#sand_size_sediment}

#####  sand size sediment


- Child of:
 [`sediment`](#sediment)


- **Source:**
Neuendorf et al. 2005 ; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand_Size_Sediment


[]{#sand}

######  sand


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Sand_Size_Sediment`](#Sand_Size_Sediment)

- Clastic sediment in which less than 30 percent of particles are
gravel (greater than 2 mm in diameter) and the sand to mud ratio is at
least 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of sand from SLTTs 2004 sandy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand


[]{#carbonate_sedimentary_material}

####  Carbonate sedimentary material


- Child of:
 [`Sedimentary_Material`](#Sedimentary_Material)

- Should carbonate sedimentary material be considered a kind of
chemical sedimentary material? Is biogenic precipitation a chemical
sedimentary process?
- Sedimentary material in which at least 50 percent of the primary
and/or recrystallized constituents are composed of one (or more) of
the carbonate minerals calcite, aragonite and dolomite, in particles
of intrabasinal origin.

- **Source:**
SLTTs 2004

- Concept URI token: Carbonate_Sedimentary_Material


[]{#carbonate_sediment}

#####  carbonate sediment


- Child of:
 [`sediment`](#sediment)
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

- Sediment in which at least 50 percent of the primary and/or
recrystallized constituents are composed of one (or more) of the
carbonate minerals calcite, aragonite and dolomite, in particles of
intrabasinal origin.

- **Source:**
SLTTs 2004

- Concept URI token: Carbonate_Sediment


[]{#calcareous_carbonate_sediment}

######  calcareous carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sediment with a calcite (plus aragonite) to dolomite ratio
greater than 1 to 1. Includes lime-sediments.

- **Source:**
after Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

#######  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

#######  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#carbonate_mud}

######  carbonate mud


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Carbonate sediment composed of less than 25 percent clasts that have
a maximum diameter more than 2 mm, and the ratio of sand size to mud
size clasts is less than one.

- **Alternate labels:**
marl


- **Source:**
follow pattern used for clastic sand and mud categories, based on SLTTs 2004

- Concept URI token: Carbonate_Mud


[]{#carbonate_ooze}

#######  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#dolomitic_sediment}

######  dolomitic sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sediment with a ratio of magnesium carbonate to calcite
(plus aragonite) greater than 1 to 1.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Sediment


[]{#impure_dolomitic_sediment}

#######  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_dolomitic_sediment}

#######  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#impure_carbonate_sediment}

######  impure carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin.

- **Alternate labels:**
marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

#######  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#impure_dolomitic_sediment}

#######  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_carbonate_sediment}

######  pure carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin.

- **Source:**
This vocabulary

- Concept URI token: Pure_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

#######  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#pure_dolomitic_sediment}

#######  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#carbonate_sedimentary_rock}

#####  carbonate sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

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


[]{#boundstone}

######  boundstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary carbonate rock with preserved biogenic texture, whose
original components were bound and encrusted together during
deposition by the action of plants and animals during deposition, and
remained substantially in the position of growth.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004

- Concept URI token: Boundstone


[]{#calcareous_carbonate_sedimentary_rock}

######  calcareous carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
SLTTs 2004; Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sedimentary_Rock


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#carbonate_mudstone}

######  carbonate mudstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Mudstone that consists of greater than 50 percent carbonate minerals
of any origin in the mud size fraction.
- Not a subcategory of carbonate sedimentary rock because definition
does not specify 'carbonate minerals of intrabasinal origin', but is
agnostic on origin of carbonate. Schnurrenberger et al. 2003 point out
that it is very difficult (at least in lacustrine rocks) to
distinguish chemically precipitated or diagenetic carbonate from
primary biogenic carbonate. This distinction between biogenic,
detrital, and pedogenic or authigenic carbonate material is thus not a
good one to use in a general purpose classification system.
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Mudstone


[]{#carbonate_wackestone}

######  carbonate wackestone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with discernible mud supported
depositional texture and containing greater than 10 percent allochems,
and constituent particles are of intrabasinal origin. If particles are
not intrabasinal, categorization as a mudstone or wackestone should be
considered.

- **Source:**
Dunham 1962

- Concept URI token: Carbonate_Wackestone


[]{#crystalline_carbonate}

######  crystalline carbonate


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate rock of indeterminate mineralogy in which diagenetic
processes have obliterated any original depositional texture.

- **Source:**
SLTTs 2004

- Concept URI token: Crystalline_Carbonate


[]{#dolomitic_or_magnesian_sedimentary_rock}

######  dolomitic or magnesian sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sedimentary rock with a ratio of magnesium carbonate to
calcite (plus aragonite) greater than 1 to 1. Includes dolostone, lime
dolostone and magnesite-stone.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Or_Magnesian_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#framestone}

######  framestone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate reef rock consisting of a rigid framework of colonies,
shells or skeletons, with internal cavities filled with fine sediment;
usually created through the activities of colonial organisms.

- **Source:**
Hallsworth and Knox 1999; SLTTs 2004, Table 15-3-1

- Concept URI token: Framestone


[]{#grainstone}

######  grainstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with recognizable depositional fabric
that is grain-supported, and constituent particles are of intrabasinal
origin; contains little or no mud matrix. Distinction from sandstone
is based on interpretation of intrabasinal origin of clasts and grain-
supported fabric, but grainstone definition does not include a grain
size criteria.

- **Alternate labels:**
carbonate grainstone


- **Source:**
Dunham 1962

- Concept URI token: Grainstone


[]{#impure_carbonate_sedimentary_rock}

######  impure carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary rock in which between 50 and 90 percent of the primary
and/or recrystallized constituents are composed of carbonate minerals.

- **Alternate labels:**
marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Carbonate_Sedimentary_Rock


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#packstone}

######  packstone


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Carbonate sedimentary rock with discernible grain supported
depositional texture, containing greater than 10 percent grains, and
constituent particles are of intrabasinal origin; intergranular spaces
are filled by matrix.
- Note that this category overlaps with 'carbonate mudstone'.

- **Source:**
Hallsworth and Knox 1999

- Concept URI token: Packstone


[]{#pure_carbonate_sedimentary_rock}

######  pure carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)

- Sedimentary rock in which greater than 90 percent of the primary
and/or recrystallized constituents are carbonate minerals.

- **Source:**
This vocabulary

- Concept URI token: Pure_Carbonate_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#pure_carbonate_mudstone}

#######  pure carbonate mudstone


- Child of:
 [`Generic_Mudstone`](#Generic_Mudstone)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Mudstone that consists of greater than 90 percent carbonate minerals
of intrabasinal orign in the mud fraction, and contains less than 10
percent allochems. The original depositional texture is preserved and
fabric is matrix supported. Carbonate mudstone of Dunham (1962)

- **Source:**
Dunham 1962

- Concept URI token: Pure_Carbonate_Mudstone


[]{#calcareous_carbonate_sedimentary_material}

#####  calcareous carbonate sedimentary material


- Child of:
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

- Carbonate sedimentary material of unspecified consolidation state
with a calcite (plus aragonite) to dolomite ratio greater than 1 to 1.
Includes lime-sediments, limestone and dolomitic limestone.

- **Source:**
after Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sedimentary_Material


[]{#calcareous_carbonate_sediment}

######  calcareous carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sediment with a calcite (plus aragonite) to dolomite ratio
greater than 1 to 1. Includes lime-sediments.

- **Source:**
after Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

#######  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

#######  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#calcareous_carbonate_sedimentary_rock}

######  calcareous carbonate sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
SLTTs 2004; Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sedimentary_Rock


[]{#impure_limestone}

#######  impure limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marlstone


- **Source:**
This vocabulary

- Concept URI token: Impure_Limestone


[]{#limestone}

#######  limestone


- Child of:
 [`Calcareous_Carbonate_Sedimentary_Rock`](#Calcareous_Carbonate_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1. Includes limestone and dolomitic
limestone.

- **Source:**
This vocabulary

- Concept URI token: Limestone


[]{#chalk}

########  chalk


- Child of:
 [`Limestone`](#Limestone)

- A generally soft, white, very fine-grained, extremely pure, porous
limestone. It forms under marine conditions from the gradual
accumulation of skeletal elements from minute planktonic green algae
(cocoliths), associated with varying proportions of larger microscopic
fragments of bivalves, foraminifera and ostracods. It is common to
find flint and chert nodules embedded in chalk.

- **Source:**
http://en.wikipedia.org/wiki/Chalk; C.S. Harris, 2009, unpublished web page, http://www.geologyshop.co.uk/chalk.htm

- Concept URI token: Chalk


[]{#travertine}

########  travertine


- Child of:
 [`Chemical_Sedimentary_Material`](#Chemical_Sedimentary_Material)
 [`Limestone`](#Limestone)

- Biotically or abiotically precipitated calcium carbonate, from
spring-fed, heated, or ambient-temperature water. May be white and
spongy, various shades of orange, tan or gray, and ranges to dense,
banded or laminated rock. Macrophytes, bryophytes, algae,
cyanobacteria and other organisms often colonize the surface of
travertine and may be preserved, to produce the porous varieties.

- **Source:**
Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Travertine; Chafetz, H.S., and Folk, R.L., 1984, Travertine: Depositional morphology an dthe bacterially constructed constituents: J. Sed. Petrology, v. 126, p.57-74.

- Concept URI token: Travertine


[]{#dolomitic_or_magnesian_sedimentary_material}

#####  dolomitic or magnesian sedimentary material


- Child of:
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

- Carbonate sedimentary material of unspecified consolidation degree
with a ratio of magnesium carbonate to calcite (plus aragonite)
greater than 1 to 1. Includes dolomite sediment, dolostone, lime
dolostone and magnesite-stone.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Or_Magnesian_Sedimentary_Material


[]{#dolomitic_or_magnesian_sedimentary_rock}

######  dolomitic or magnesian sedimentary rock


- Child of:
 [`Carbonate_Sedimentary_Rock`](#Carbonate_Sedimentary_Rock)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sedimentary rock with a ratio of magnesium carbonate to
calcite (plus aragonite) greater than 1 to 1. Includes dolostone, lime
dolostone and magnesite-stone.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Or_Magnesian_Sedimentary_Rock


[]{#dolostone}

#######  dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Pure_Carbonate_Sedimentary_Rock`](#Pure_Carbonate_Sedimentary_Rock)

- Pure carbonate sedimentary rock with a ratio of magnesium carbonate
to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolostone, 
pure dolomitic or magnesian carbonate sedimentary rock, 


- **Source:**
This vocabulary

- Concept URI token: Dolostone


[]{#impure_dolostone}

#######  impure dolomite


- Child of:
 [`Dolomitic_Or_Magnesian_Sedimentary_Rock`](#Dolomitic_Or_Magnesian_Sedimentary_Rock)
 [`Impure_Carbonate_Sedimentary_Rock`](#Impure_Carbonate_Sedimentary_Rock)

- Impure carbonate sedimentary rock with a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marlstone, 
impure dolomitic or magnesian carbonate sedimentary rock, 
impure dolostone, 


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolostone


[]{#dolomitic_sediment}

######  dolomitic sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sediment with a ratio of magnesium carbonate to calcite
(plus aragonite) greater than 1 to 1.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Sediment


[]{#impure_dolomitic_sediment}

#######  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_dolomitic_sediment}

#######  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#clastic_sedimentary_material}

####  clastic sedimentary material


- Child of:
 [`Sedimentary_Material`](#Sedimentary_Material)

- Sedimentary material of unspecified consolidation state in which at
least 50 percent of the constituent particles were derived from
erosion, weathering, or mass-wasting of pre-existing earth materials,
and transported to the place of deposition by mechanical agents such
as water, wind, ice and gravity.

- **Source:**
SLTTs 2004; Neuendorf et al. 2005

- Concept URI token: Clastic_Sedimentary_Material


[]{#clastic_sediment}

#####  clastic sediment


- Child of:
 [`sediment`](#sediment)
 [`Clastic_Sedimentary_Material`](#Clastic_Sedimentary_Material)

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

######  diamicton


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


[]{#gravel}

######  gravel


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Clastic sediment containing greater than 30 percent gravel-size
particles (greater than 2.0 mm diameter). Gravel in which more than
half of the particles are of epiclastic origin

- **Source:**
definition of gravel from SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel


[]{#mud}

######  mud


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Clastic sediment consisting of less than 30 percent gravel-size (2
mm) particles and with a mud-size to sand-size particle ratio greater
than 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of mud from SLTTs 2004 muddy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud


[]{#clay}

#######  clay


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent particles with grain
size less than 0.004 mm

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clay


[]{#silt}

#######  silt


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent silt-size grains.

- **Alternate labels:**
loess


- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Silt


[]{#sand}

######  sand


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Sand_Size_Sediment`](#Sand_Size_Sediment)

- Clastic sediment in which less than 30 percent of particles are
gravel (greater than 2 mm in diameter) and the sand to mud ratio is at
least 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of sand from SLTTs 2004 sandy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand


[]{#clastic_sedimentary_rock}

#####  clastic sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Clastic_Sedimentary_Material`](#Clastic_Sedimentary_Material)

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

######  diamictite


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


[]{#clastic_conglomerate}

######  conglomerate


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Conglomerate`](#Generic_Conglomerate)

- Clastic sedimentary rock composed of at least 30 percent rounded to
subangular fragments larger than 2 mm in diameter; typically contains
finer grained material in interstices between larger fragments. If
more than 15 percent of the fine grained matrix is of indeterminant
clastic or diagenetic origin and the fabric is matrix supported, may
also be categorized as wackestone. If rock has unsorted or poorly
sorted texture with a wide range of particle sizes, may also be
categorized as diamictite.
- Note this category is equivlanet to category labeled 'Conglomeratic
rock in SLTTs (2004), not to the category labeled 'Conglomerate' in
that system.

- **Alternate labels:**
conglomeratic rock


- **Source:**
Neuendorf et al. 2005; SLTTs 2004

- Concept URI token: Clastic_Conglomerate


[]{#clastic_mudstone}

######  mudstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Mudstone`](#Generic_Mudstone)

- Clastic sedimentary rock consisting of less than 30 percent gravel-
size (2 mm) particles and with a mud to sand ratio greater than 1.
- Distinction of intrabasinal, diagenetic, or clastic genesis for very
fine-grained carbonate minerals is interpretive in many cases. If
there is uncertainty on the mudstone category based on intrabasinal vs
epiclastic distinction required for clastic sedimentary rock-carbonate
sedimentary rock categorization in this system, it is recommended to
use the generic_mudstone category. This category is the union of the
various fields labeled 'mudstone' with various qualifiers in Folk,
1954, Figure 1a, although Folk's (1954) category labeled 'mudstone' is
a much more restricted category. The CGI category is equivalent to
category labeled 'Mudrock' in SLTTs (2004), not to the category
labeled 'Mudstone' adopted by that system from Folk (1954).
Schnurrenberger, D., Russell, J. and Kelts, K., 2003, Classification
of lacustrine sediments based on sedimentary components: Journal of
Paleolimnology, v.29, p141-154.

- **Alternate labels:**
clastic mudstone, 
mudrock, 


- **Source:**
Pettijohn et al. 1987 referenced in Hallsworth and Knox 1999.

- Concept URI token: Clastic_Mudstone


[]{#claystone}

#######  claystone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains no detectable silt, inferred to consist
virtually entirely of clay-size particles.

- **Source:**
This vocabulary

- Concept URI token: Claystone


[]{#shale}

#######  shale


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Laminated mudstone that will part or break along thin, closely
spaced layers parallel to stratification.
- Note definition does not specify carbonate vs. siliclastic nature of
mud.

- **Source:**
NADM SLTT sedimentary, 2004

- Concept URI token: Shale


[]{#siltstone}

#######  siltstone


- Child of:
 [`Clastic_Mudstone`](#Clastic_Mudstone)

- Mudstone that contains detectable silt. (see comments)
- Use of 'dectable silt' in the criteria for this category is based on
the observation that in practice, distinction of claystone from
'siltstone' is typically based on a qualitative assessment of
'grittiness' (e.g. rubbing with fingers, or chewing); the property
that these tests can determine is the presence or absence of silty
particles in the material. Quantitative grain size analysis in the the
clay/silt fraction of a lithified sediment is difficult at best, and
of questionable significance because diagensis has altered the size
and mineralogy of original sedimentary particles.

- **Alternate labels:**
Silt bearing mudstone


- **Source:**
This vocabulary

- Concept URI token: Siltstone


[]{#clastic_sandstone}

######  sandstone


- Child of:
 [`Clastic_Sedimentary_Rock`](#Clastic_Sedimentary_Rock)
 [`Generic_Sandstone`](#Generic_Sandstone)

- Clastic sedimentary rock in which less than 30 percent of particles
are greater than 2 mm in diameter (gravel) and the sand to mud ratio
is at least 1.
- Note this category is equivalent to cagetory labeled 'sandy rock' in
SLTTs (2004), not to the much more restricted category labeled
'Sandstone' in that system.

- **Alternate labels:**
clastic sandstone, 
sandy rock, 


- **Source:**
SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clastic_Sandstone


[]{#arenite}

#######  arenit
* `arenite`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone that contains less than 10 percent matrix. Matrix
is mud-size silicate minerals (clay, feldspar, quartz, rock fragments,
and alteration products) of detrital or diagenetic nature.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Arenite


[]{#wacke}

#######  piedra
* `wacke`


- Child of:
 [`Clastic_Sandstone`](#Clastic_Sandstone)

- Clastic sandstone with more than 10 percent matrix of indeterminate
detrital or diagenetic nature. Matrix is mud size silicate minerals
(clay, feldspar, quartz, rock fragments, and alteration products).
- Distinction from mudstone is based on inference that less that 50
percent of the mud size fraction (matrix) is original mud size
detrital particles. May also grade into diamictite or conglomerate
based on size distribution of discernible particles. If more than 50
percent of rock is detrital particles of intrabasinal orgin and
carbonate composition, categorize as carbonate wackestone. Term is
typically applied to diagenetically altered volcanic-lithic clastic
rocks in which the definition of the original clasts has been
obscured. Suggested boundaries between wacke and arenite range from 5
to 15 percent matrix. See Dickinson (1970) for discussion of
interpretation of undiscernible matrix in diagenetically altered
lithic clastic rocks. Dickinson, W.R., 1970, Interpreting detrital
modes of graywacke and arkose: Journal of Sedimentary Petrology, v.
40, p. 695-707.

- **Source:**
Pettijohn, Potter, Siever, 1972, Sand and Sandstone: New York, Springer Verlag, 681 p.

- Concept URI token: Wacke


[]{#non_clastic_siliceous_sedimentary_material}

####  non clastic siliceous sedimentary material


- Child of:
 [`Sedimentary_Material`](#Sedimentary_Material)

- Sedimentary material that consists of at least 50 percent silicate
mineral material, deposited directly by chemical or biological
processes at the depositional surface, or in particles formed by
chemical or biological processes within the basin of deposition.

- **Source:**
SLTTs 2004

- Concept URI token: Non_Clastic_Siliceous_Sedimentary_Material


[]{#non_clastic_siliceous_sediment}

#####  non clastic siliceous sediment


- Child of:
 [`sediment`](#sediment)
 [`Non_Clastic_Siliceous_Sedimentary_Material`](#Non_Clastic_Siliceous_Sedimentary_Material)


- **Source:**
NGMDB 2008; Hallsworth and Knox 1999

- Concept URI token: Non_Clastic_Siliceous_Sediment


[]{#non_clastic_siliceous_sedimentary_rock}

#####  non clastic siliceous sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Non_Clastic_Siliceous_Sedimentary_Material`](#Non_Clastic_Siliceous_Sedimentary_Material)

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


[]{#biogenic_silica_sedimentary_rock}

######  biogenic silica sedimentary rock


- Child of:
 [`Non_Clastic_Siliceous_Sedimentary_Rock`](#Non_Clastic_Siliceous_Sedimentary_Rock)

- Sedimentary rock that consists of at least 50 percent silicate
mineral material, deposited directly by biological processes at the
depositional surface, or in particles formed by biological processes
within the basin of deposition. Includes radiolarian chert, diatomite,
novaculite.

- **Source:**
based on NADM SLTT sedimentary; Hallsworth and Knox 1999

- Concept URI token: Biogenic_Silica_Sedimentary_Rock


[]{#organic_rich_sedimentary_material}

####  organic rich sedimentary material


- Child of:
 [`Sedimentary_Material`](#Sedimentary_Material)

- Sedimentary material in which 50 percent or more of the primary
sedimentary material is organic carbon.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sedimentary_Material


[]{#organic_rich_sedimentary_rock}

#####  organic rich sedimentary rock


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Organic_Rich_Sedimentary_Material`](#Organic_Rich_Sedimentary_Material)

- Sapropelic coal, and asphaltite are not differentiated in This
vocabulary
- Sedimentary rock with color, composition, texture and apparent
density indicating greater than 50 percent organic content by weight
on a moisture-free basis.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sedimentary_Rock


[]{#coal}

######  coal
* `kohle`


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


[]{#anthracite_coal}

#######  anthracite
* `anthrazit`


- Child of:
 [`Coal`](#Coal)

- Coal that has vitrinite mean random reflectance greater than 2.0%
(determined in conformance with ISO 7404-5). Less than 12-14 percent
volatiles (dry, ash free), greater than 91 percent fixed carbon (dry,
ash free basis). The highest rank coal; very hard, glossy, black, with
semimetallic luster, semi conchoidal fracture.

- **Alternate labels:**
High rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp; see also Neuendorf et al. 2005; http://en.wikipedia.org/wiki/Coal#Types_of_coal; Eberhard Lindner; Chemie für Ingenieure; Lindner Verlag Karlsruhe, S. 258

- Concept URI token: Anthracite_Coal


[]{#bituminous_coal}

#######  bituminous coal


- Child of:
 [`Coal`](#Coal)

- Coal that has vitrinite mean random reflectance greater than 0.6%
and less than 2.0% (determined in conformance with ISO 7404-5), or has
a gross calorific value greater than 24 MJ/kg (determined in
conformance with ISO 1928). Hard, black, organic rich sedimentary
rock; contains less than 91 percent fixed carbon on a dry, mineral-
matter-free basis, and greater than 13-14 percent volatiles (dry, ash
free). Formed from the compaction or induration of variously altered
plant remains similar to those of peaty deposits.

- **Alternate labels:**
medium rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp; see also http://en.wikipedia.org/wiki/Coal#Types_of_coal; Eberhard Lindner; Chemie für Ingenieure; Lindner Verlag Karlsruhe, S. 258

- Concept URI token: Bituminous_Coal


[]{#lignite}

#######  lignite


- Child of:
 [`Coal`](#Coal)

- Coal that has a gross calorific value less than 24 MJ/kg (determined
in conformance with ISO 1928), and vitrinite mean random reflectance
less than 0.6% (determined in conformance with ISO 7404-5). Gross
calorific value is recalculated to a moist, ash free basis using bed
moisture (determined according to ISO 1015 or ISO 5068). Includes all
low-rank coals, including sub-bitiminous coal. A consolidated, dull,
soft brown to black coal having many readily discernible plant
fragments set in a finer grained organic matrix. Tends to crack and
fall apart on drying. Operationally sub-bituminous and bitiminous coal
are qualitatively distinguished based on brown streak for sub-
bitiminous coal and black streak for bituminous coal.

- **Alternate labels:**
low rank coal


- **Source:**
Economic commission for Europe, committee on Sustainable Energy- United Nations (ECE-UN), 1998, International Classification of in-Seam Coals: Energy 19, 41 pp.

- Concept URI token: Lignite


[]{#organic_rich_sediment}

#####  organic rich sediment


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Organic_Rich_Sedimentary_Material`](#Organic_Rich_Sedimentary_Material)

- Sediment with color, composition, texture and apparent density
indicating greater than 50 percent organic content by weight on a
moisture-free basis.
- The broader relation from organic rich sediment to biogenic sediment
is based on the inference that organic rich material is always
biogenic in origin. Biogenic is a broader category because not all
biogenic materials are organic rich, for example shells or phosphatic
bone.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sediment


[]{#peat}

######  peat


- Child of:
 [`Organic_Rich_Sediment`](#Organic_Rich_Sediment)

- Unconsolidated organic-rich sediment composed of at least 50 percent
semi-carbonised plant remains; individual remains commonly seen with
unaided eye; yellowish brown to brownish black; generally fibrous
texture; can be plastic or friable. In its natural state it can be
readily cut and has a very high moisture content, generally greater
than 90 percent. Liptinite to Inertinite ratio is less than one
(Economic commission for Europe, committee on Sustainable Energy-
United Nations (ECE-UN), 1998, International Classification of in-Seam
Coals: Energy 19, 41 pp.)

- **Source:**
Hallsworth and Knox 1999

- Concept URI token: Peat


[]{#sapropel}

######  sapropel


- Child of:
 [`Organic_Rich_Sediment`](#Organic_Rich_Sediment)

- Jelly like organic rich sediment composed of plant remains, usually
algal. Liptinite to Inertinite ratio is greater than one (Economic
commission for Europe, committee on Sustainable Energy- United Nations
(ECE-UN), 1998, International Classification of in-Seam Coals: Energy
19, 41 pp.)

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Sapropel


[]{#phosphate_rich_sedimentary_material}

####  phosphate rich sedimentary material


- Child of:
 [`Sedimentary_Material`](#Sedimentary_Material)

- Sedimentary material in which at least 50 percent of the primary
and/or recrystallized constituents are phosphate minerals.

- **Source:**
SLTTs 2004

- Concept URI token: Phosphate_Rich_Sedimentary_Material


[]{#phosphate_rich_sediment}

#####  phosphate rich sediment


- Child of:
 [`sediment`](#sediment)
 [`Phosphate_Rich_Sedimentary_Material`](#Phosphate_Rich_Sedimentary_Material)


- **Source:**
SLTTs 2004

- Concept URI token: Phosphate_Rich_Sediment


[]{#phosphorite}

#####  phosphorite


- Child of:
 [`Sedimentary_Rock`](#Sedimentary_Rock)
 [`Phosphate_Rich_Sedimentary_Material`](#Phosphate_Rich_Sedimentary_Material)

- Sedimentary rock in which at least 50 percent of the primary or
recrystallized constituents are phosphate minerals. Most commonly
occurs as a bedded primary or reworked secondary marine rock, composed
of microcrystalline carbonate fluorapatite in the form of lamina,
pellets, oolites and nodules, and skeletal, shell and bone fragments.

- **Source:**
HallsworthandKnox 1999, Jackson 1997

- Concept URI token: Phosphorite


[]{#unconsolidated_material}

###  Unconsolidated material


- Child of:
 [`Rock_Material`](#Rock_Material)

- compoundMaterial composed of an aggregation of particles that do not
adhere to each other strongly enough that the aggregate can be
considered a solid in its own right.

- **Source:**
This vocabulary

- Concept URI token: Unconsolidated_Material


[]{#anthropogenic_unconsolidated_material}

####  Anthropogenic unconsolidated material


- Child of:
 [`Anthropogenic_Material`](#Anthropogenic_Material)
 [`Unconsolidated_Material`](#Unconsolidated_Material)

- Unconsolidated material known to have artificial (human-related)
origin.

- **Source:**
This vocabulary

- Concept URI token: Anthropogenic_Unconsolidated_Material


[]{#natural_unconsolidated_material}

####  Natural unconsolidated material


- Child of:
 [`Unconsolidated_Material`](#Unconsolidated_Material)

- Unconsolidated material known to have natural, ie. not human-made,
origin.

- **Source:**
This vocabulary

- Concept URI token: Natural_Unconsolidated_Material


[]{#tephra}

#####  Tephra
* `tephra`


- Child of:
 [`Natural_Unconsolidated_Material`](#Natural_Unconsolidated_Material)
 [`Pyroclastic_Material`](#Pyroclastic_Material)


- **Source:**
Hallsworth and Knox 1999; LeMaitre et al. 2002

- Concept URI token: Tephra


[]{#ash_and_lapilli}

######  ash and lapilli


- Child of:
 [`Tephra`](#Tephra)

- Tephra in which less than 25 percent of fragments are greater than
64 mm in longest dimension

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_And_Lapilli


[]{#ash_breccia_bomb_or_block_tephra}

######  ash breccia bomb or block tephra


- Child of:
 [`Tephra`](#Tephra)

- Tephra in which more than 25 percent of particles are greater than
64 mm in largest dimension. Includes ash breccia, bomb tephra and
block tephra of Gillespie and Styles (1999)

- **Source:**
Schmid 1981; LeMaitre et al. 2002

- Concept URI token: Ash_Breccia_Bomb_Or_Block_Tephra


[]{#sediment}

#####  sediment


- Child of:
 [`Natural_Unconsolidated_Material`](#Natural_Unconsolidated_Material)
 [`Sedimentary_Material`](#Sedimentary_Material)

- Unconsolidated material consisting of an aggregation of particles
transported or deposited by air, water or ice, or that accumulated by
other natural agents, such as chemical precipitation, and that forms
in layers on the Earth's surface. Includes epiclastic deposits.

- **Source:**
SLTTs 2004

- Concept URI token: sediment


[]{#biogenic_sediment}

######  biogenic sediment


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


[]{#ooze}

#######  ooze


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Biogenic sediment consisting of less than 1 percent gravel-size
(greater than or equal to 2 mm) particles, with a sand to mud ratio
less than 1 to 9, and less than 50 percent carbonate minerals.
- Neuendorf et al. 2005 put cutoff at 30 percent skeletal remains;
this is raised to 50 percent in This vocabulary for consistency with
definition of other Biogenic sediment category

- **Alternate labels:**
biogenic mud


- **Source:**
based on Bates and Jackson 1987 and Hallsworth and Knox 1999

- Concept URI token: Ooze


[]{#carbonate_ooze}

########  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#siliceous_ooze}

########  siliceous ooze


- Child of:
 [`Ooze`](#Ooze)
 [`Silicate_Mud`](#Silicate_Mud)

- ooze that consists of more than 50 percent siliceous skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Siliceous_Ooze


[]{#organic_rich_sediment}

#######  organic rich sediment


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Organic_Rich_Sedimentary_Material`](#Organic_Rich_Sedimentary_Material)

- Sediment with color, composition, texture and apparent density
indicating greater than 50 percent organic content by weight on a
moisture-free basis.
- The broader relation from organic rich sediment to biogenic sediment
is based on the inference that organic rich material is always
biogenic in origin. Biogenic is a broader category because not all
biogenic materials are organic rich, for example shells or phosphatic
bone.

- **Source:**
SLTTs 2004

- Concept URI token: Organic_Rich_Sediment


[]{#peat}

########  peat


- Child of:
 [`Organic_Rich_Sediment`](#Organic_Rich_Sediment)

- Unconsolidated organic-rich sediment composed of at least 50 percent
semi-carbonised plant remains; individual remains commonly seen with
unaided eye; yellowish brown to brownish black; generally fibrous
texture; can be plastic or friable. In its natural state it can be
readily cut and has a very high moisture content, generally greater
than 90 percent. Liptinite to Inertinite ratio is less than one
(Economic commission for Europe, committee on Sustainable Energy-
United Nations (ECE-UN), 1998, International Classification of in-Seam
Coals: Energy 19, 41 pp.)

- **Source:**
Hallsworth and Knox 1999

- Concept URI token: Peat


[]{#sapropel}

########  sapropel


- Child of:
 [`Organic_Rich_Sediment`](#Organic_Rich_Sediment)

- Jelly like organic rich sediment composed of plant remains, usually
algal. Liptinite to Inertinite ratio is greater than one (Economic
commission for Europe, committee on Sustainable Energy- United Nations
(ECE-UN), 1998, International Classification of in-Seam Coals: Energy
19, 41 pp.)

- **Source:**
Neuendorf et al. 2005

- Concept URI token: Sapropel


[]{#carbonate_sediment}

######  carbonate sediment


- Child of:
 [`sediment`](#sediment)
 [`Carbonate_Sedimentary_Material`](#Carbonate_Sedimentary_Material)

- Sediment in which at least 50 percent of the primary and/or
recrystallized constituents are composed of one (or more) of the
carbonate minerals calcite, aragonite and dolomite, in particles of
intrabasinal origin.

- **Source:**
SLTTs 2004

- Concept URI token: Carbonate_Sediment


[]{#calcareous_carbonate_sediment}

#######  calcareous carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Calcareous_Carbonate_Sedimentary_Material`](#Calcareous_Carbonate_Sedimentary_Material)

- Carbonate sediment with a calcite (plus aragonite) to dolomite ratio
greater than 1 to 1. Includes lime-sediments.

- **Source:**
after Hallsworth and Knox 1999

- Concept URI token: Calcareous_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

########  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

########  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#carbonate_mud}

#######  carbonate mud


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Carbonate sediment composed of less than 25 percent clasts that have
a maximum diameter more than 2 mm, and the ratio of sand size to mud
size clasts is less than one.

- **Alternate labels:**
marl


- **Source:**
follow pattern used for clastic sand and mud categories, based on SLTTs 2004

- Concept URI token: Carbonate_Mud


[]{#carbonate_ooze}

########  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#dolomitic_sediment}

#######  dolomitic sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Dolomitic_Or_Magnesian_Sedimentary_Material`](#Dolomitic_Or_Magnesian_Sedimentary_Material)

- Carbonate sediment with a ratio of magnesium carbonate to calcite
(plus aragonite) greater than 1 to 1.

- **Source:**
after SLTTs 2004, Hallsworth and Knox 1999

- Concept URI token: Dolomitic_Sediment


[]{#impure_dolomitic_sediment}

########  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_dolomitic_sediment}

########  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#impure_carbonate_sediment}

#######  impure carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin.

- **Alternate labels:**
marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Carbonate_Sediment


[]{#impure_calcareous_carbonate_sediment}

########  impure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
calcareous marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Calcareous_Carbonate_Sediment


[]{#impure_dolomitic_sediment}

########  impure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Impure_Carbonate_Sediment`](#Impure_Carbonate_Sediment)

- Carbonate sediment in which between 50 and 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and the ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Alternate labels:**
dolomitic marl


- **Source:**
This vocabulary

- Concept URI token: Impure_Dolomitic_Sediment


[]{#pure_carbonate_sediment}

#######  pure carbonate sediment


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin.

- **Source:**
This vocabulary

- Concept URI token: Pure_Carbonate_Sediment


[]{#pure_calcareous_carbonate_sediment}

########  pure calcareous carbonate sediment


- Child of:
 [`Calcareous_Carbonate_Sediment`](#Calcareous_Carbonate_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a calcite (plus aragonite) to
dolomite ratio greater than 1 to 1.

- **Alternate labels:**
lime sediment


- **Source:**
This vocabulary

- Concept URI token: Pure_Calcareous_Carbonate_Sediment


[]{#pure_dolomitic_sediment}

########  pure dolomitic sediment


- Child of:
 [`Dolomitic_Sediment`](#Dolomitic_Sediment)
 [`Pure_Carbonate_Sediment`](#Pure_Carbonate_Sediment)

- Carbonate sediment in which greater than 90 percent of the
constituents are composed of one (or more) of the carbonate minerals
in particles of intrabasinal origin, and a ratio of magnesium
carbonate to calcite (plus aragonite) greater than 1 to 1.

- **Source:**
This vocabulary

- Concept URI token: Pure_Dolomitic_Sediment


[]{#clastic_sediment}

######  clastic sediment


- Child of:
 [`sediment`](#sediment)
 [`Clastic_Sedimentary_Material`](#Clastic_Sedimentary_Material)

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

#######  diamicton


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


[]{#gravel}

#######  gravel


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Clastic sediment containing greater than 30 percent gravel-size
particles (greater than 2.0 mm diameter). Gravel in which more than
half of the particles are of epiclastic origin

- **Source:**
definition of gravel from SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel


[]{#mud}

#######  mud


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Clastic sediment consisting of less than 30 percent gravel-size (2
mm) particles and with a mud-size to sand-size particle ratio greater
than 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of mud from SLTTs 2004 muddy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud


[]{#clay}

########  clay


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent particles with grain
size less than 0.004 mm

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clay


[]{#silt}

########  silt


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent silt-size grains.

- **Alternate labels:**
loess


- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Silt


[]{#sand}

#######  sand


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Sand_Size_Sediment`](#Sand_Size_Sediment)

- Clastic sediment in which less than 30 percent of particles are
gravel (greater than 2 mm in diameter) and the sand to mud ratio is at
least 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of sand from SLTTs 2004 sandy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand


[]{#gravel_size_sediment}

######  gravel size sediment


- Child of:
 [`sediment`](#sediment)

- Sediment containing greater than 30 percent gravel-size particles
(greater than 2.0 mm diameter). Composition or gensis of clasts not
specified.

- **Source:**
SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel_Size_Sediment


[]{#boulder_gravel_size_sediment}

#######  boulder gravel size sediment


- Child of:
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Sediment containing greater than 30 percent boulder-size particles
(greater than 256 mm in diameter)

- **Source:**
Wentworth size scale

- Concept URI token: Boulder_Gravel_Size_Sediment


[]{#cobble_gravel_size_sediment}

#######  cobble gravel size sediment


- Child of:
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Sediment containing greater than 30 percent cobble-size particles
(64-256 mm in diameter)

- **Source:**
Wentworth size scale

- Concept URI token: Cobble_Gravel_Size_Sediment


[]{#gravel}

#######  gravel


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Clastic sediment containing greater than 30 percent gravel-size
particles (greater than 2.0 mm diameter). Gravel in which more than
half of the particles are of epiclastic origin

- **Source:**
definition of gravel from SLTTs 2004; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Gravel


[]{#pebble_gravel_size_sediment}

#######  pebble gravel size sediment


- Child of:
 [`Gravel_Size_Sediment`](#Gravel_Size_Sediment)

- Sediment containing greater than 30 percent pebble-size particles
(2.0 -64 mm in diameter)

- **Source:**
Wentworth size scale

- Concept URI token: Pebble_Gravel_Size_Sediment


[]{#hybrid_sediment}

######  Hybrid sediment
* `hybrid sediment`


- Child of:
 [`sediment`](#sediment)


- **Source:**
Hallsworth and Knox, 1999

- Concept URI token: Hybrid_Sediment


[]{#iron_rich_sediment}

######  iron rich sediment


- Child of:
 [`sediment`](#sediment)
 [`Iron_Rich_Sedimentary_Material`](#Iron_Rich_Sedimentary_Material)

- Sediment that consists of at least 50 percent iron-bearing minerals
(hematite, magnetite, limonite-group, siderite, iron-sulfides), as
determined by hand-lens or petrographic analysis. Corresponds to a
rock typically containing 15 percent iron by weight.

- **Source:**
SLTTs 2004

- Concept URI token: Iron_Rich_Sediment


[]{#mud_size_sediment}

######  mud size sediment


- Child of:
 [`sediment`](#sediment)

- Sediment consisting of less than 30 percent gravel-size (2 mm)
particles and with a mud-size to sand-size particle ratio greater than
1. Clasts may be of any composition or origin.

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud_Size_Sediment


[]{#carbonate_mud}

#######  carbonate mud


- Child of:
 [`Carbonate_Sediment`](#Carbonate_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Carbonate sediment composed of less than 25 percent clasts that have
a maximum diameter more than 2 mm, and the ratio of sand size to mud
size clasts is less than one.

- **Alternate labels:**
marl


- **Source:**
follow pattern used for clastic sand and mud categories, based on SLTTs 2004

- Concept URI token: Carbonate_Mud


[]{#carbonate_ooze}

########  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#carbonate_rich_mud}

#######  carbonate rich mud


- Child of:
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Mud size sediment that contains between 10 and 50 percent carbonate
minerals in any size fraction. Carbonate origin is not specified.

- **Alternate labels:**
carbonate rich loess, 
marl, 


- **Source:**
This vocabulary

- Concept URI token: Carbonate_Rich_Mud


[]{#mud}

#######  mud


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Clastic sediment consisting of less than 30 percent gravel-size (2
mm) particles and with a mud-size to sand-size particle ratio greater
than 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of mud from SLTTs 2004 muddy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Mud


[]{#clay}

########  clay


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent particles with grain
size less than 0.004 mm

- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Clay


[]{#silt}

########  silt


- Child of:
 [`Mud`](#Mud)

- Mud that consists of greater than 50 percent silt-size grains.

- **Alternate labels:**
loess


- **Source:**
based on SLTTs 2004; Neuendorf et al. 2005; particle size from Wentworth grade scale

- Concept URI token: Silt


[]{#ooze}

#######  ooze


- Child of:
 [`Biogenic_Sediment`](#Biogenic_Sediment)
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Biogenic sediment consisting of less than 1 percent gravel-size
(greater than or equal to 2 mm) particles, with a sand to mud ratio
less than 1 to 9, and less than 50 percent carbonate minerals.
- Neuendorf et al. 2005 put cutoff at 30 percent skeletal remains;
this is raised to 50 percent in This vocabulary for consistency with
definition of other Biogenic sediment category

- **Alternate labels:**
biogenic mud


- **Source:**
based on Bates and Jackson 1987 and Hallsworth and Knox 1999

- Concept URI token: Ooze


[]{#carbonate_ooze}

########  carbonate ooze


- Child of:
 [`Carbonate_Mud`](#Carbonate_Mud)
 [`Ooze`](#Ooze)

- ooze that consists of more than 50 percent carbonate skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Carbonate_Ooze


[]{#siliceous_ooze}

########  siliceous ooze


- Child of:
 [`Ooze`](#Ooze)
 [`Silicate_Mud`](#Silicate_Mud)

- ooze that consists of more than 50 percent siliceous skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Siliceous_Ooze


[]{#silicate_mud}

#######  silicate mud


- Child of:
 [`Mud_Size_Sediment`](#Mud_Size_Sediment)

- Mud size sediment that consists of less than 50 percent carbonate
minerals.

- **Source:**
This vocabulary

- Concept URI token: Silicate_Mud


[]{#siliceous_ooze}

########  siliceous ooze


- Child of:
 [`Ooze`](#Ooze)
 [`Silicate_Mud`](#Silicate_Mud)

- ooze that consists of more than 50 percent siliceous skeletal
remains

- **Source:**
This vocabulary

- Concept URI token: Siliceous_Ooze


[]{#non_clastic_siliceous_sediment}

######  non clastic siliceous sediment


- Child of:
 [`sediment`](#sediment)
 [`Non_Clastic_Siliceous_Sedimentary_Material`](#Non_Clastic_Siliceous_Sedimentary_Material)


- **Source:**
NGMDB 2008; Hallsworth and Knox 1999

- Concept URI token: Non_Clastic_Siliceous_Sediment


[]{#phosphate_rich_sediment}

######  phosphate rich sediment


- Child of:
 [`sediment`](#sediment)
 [`Phosphate_Rich_Sedimentary_Material`](#Phosphate_Rich_Sedimentary_Material)


- **Source:**
SLTTs 2004

- Concept URI token: Phosphate_Rich_Sediment


[]{#sand_size_sediment}

######  sand size sediment


- Child of:
 [`sediment`](#sediment)


- **Source:**
Neuendorf et al. 2005 ; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand_Size_Sediment


[]{#sand}

#######  sand


- Child of:
 [`Clastic_Sediment`](#Clastic_Sediment)
 [`Sand_Size_Sediment`](#Sand_Size_Sediment)

- Clastic sediment in which less than 30 percent of particles are
gravel (greater than 2 mm in diameter) and the sand to mud ratio is at
least 1. More than half of the particles are of epiclastic origin.

- **Source:**
definition of sand from SLTTs 2004 sandy sediment; particle sizes defined from Krumbein phi scale (W C Krumbein and L L Sloss, Stratigraphy and Sedimentation, 2nd edition, Freeman, San Francisco, 1963; Krumbein and Pettijohn, 1938, Manual of Sedimentary Petrography: New York, Appleton Century Co., Inc.)

- Concept URI token: Sand



