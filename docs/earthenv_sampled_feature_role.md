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

[]{#EarthandEnvironmentalSciencesampledfeatureroleextension}

# **Concept scheme:** Earth and Environmental Science sampled feature role extension

Vocabulary last modified:  2023-11-17

subtitle: 
  Terms to categorize the relation of a sampled feature to its context. In the Earth Science realm this is typically relation of sampled feature to a containing rock body or rock body part.

Namespace: 
[`https://w3id.org/isample/1.0/sampledfeaturerole/sfrolevocabulary`](https://w3id.org/isample/1.0/sampledfeaturerole/sfrolevocabulary)

**History**

* 2023-11-17 SMR generate to account for sample classifications in SESAR

- [Resonance ionization mass spectrometry](#sampledfeaturepart)
    - [individual constituent](#individualconstituent)
        - [cement](#cement)
        - [groundmass](#groundmass)
        - [phenocryst](#phenocryst)
        - [porphyroblast](#porphyroblast)
    - [rock body](#rockbody)

**Concepts**

[]{#sampledfeaturepart}

##  Resonance ionization mass spectrometry


- a sample feature that is part of a larger sampled feature; Could be
improper part (e.g. the whole larger feature)

- **Source:**
this vocabulary

- Concept URI token: sampledfeaturepart


[]{#individualconstituent}

###  individual constituent


- Child of:
 [`sampledfeaturepart`](#sampledfeaturepart)

- sampled feature is a single particle or collection of particles that
share some characteristic, within or extracted from a larger sample.

- **Source:**
This vocabulary

- Concept URI token: individualconstituent


[]{#cement}

####  cement


- Child of:
 [`individualconstituent`](#individualconstituent)

- sampled feature is material that binds constituent particles
together in a sedimentary rock.

- **Source:**
This vocabulary

- Concept URI token: cement


[]{#groundmass}

####  groundmass


- Child of:
 [`individualconstituent`](#individualconstituent)

- sampled feature is fine-grained to aphanitic material that is
interstitial to larger crystals or particles in a sample.

- **Source:**
This vocabulary

- Concept URI token: groundmass


[]{#phenocryst}

####  phenocryst


- Child of:
 [`individualconstituent`](#individualconstituent)

- Sampled feature is a crystal that is significantly larger than
surrounding crystals in an igneous rock.

- **Source:**
This vocabulary

- Concept URI token: phenocryst


[]{#porphyroblast}

####  porphyroblast


- Child of:
 [`individualconstituent`](#individualconstituent)

- Sampled feature is a crystal that is significantly larger than
surrounding crystals in a metamorphic rock.

- **Source:**
This vocabulary

- Concept URI token: porphyroblast


[]{#rockbody}

###  rock body


- Child of:
 [`sampledfeaturepart`](#sampledfeaturepart)

- sampled feature is representative of a rock body, i.e. it represents
the whole of the sampled body.

- **Source:**
This vocabulary

- Concept URI token: rockbody



