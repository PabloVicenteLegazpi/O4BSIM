# SIMBOTs Core Ontology and Reference Library

This repository contains the O4BSIM core model and Reference library for **SIMBOTs** (Mathematical Simulation models for real-time). The ontology is built on top of the **CEN EN 17632-1:2022 (Semantic Modelling and Linking — SML)** framework to enable clear communication and data reuse about mathematical simulations. It provides a standardized ontology designed to bridge the gap between equipment manufacturers and software developers. By establishing a shared semantic language, we enable seamless communication of functional equipment data, ensuring alignment with future Digital Product Passport (DPP) requirements.

SIMBOT definition is following the specifications provided by the open CEN workshop 'Mathematical Simulation models for real time, SIMBOTs', which can be found in this link: https://www.cencenelec.eu/news-events/news/2026/workshop/20260408_hycool/.

The intention of this ontology is to have a demonstration tool for future developments. Initially, SIMBOTs are developed for data centers of the pilots included in HYCOOL-IT EU project (GA No 101138623), and project DYMAN (GA No 101161930).

## Overview

- **Core Ontology File:** [`O4BSIM_SIMBOTs_core_ontology.ttl`](O4BSIM_SIMBOTs_core_ontology.ttl)
- **Reference Library File:** [`O4BSIM_SIMBOTs_Reference_Library.ttl`](O4BSIM_SIMBOTs_Reference_Library.ttl)
- **Interactive Documentation:** - 
  - [Ontology Structural Explanation](docs/ontology%20explanation.html)
  - [SIMBOT Methodology & Context Explanation](docs/SIMBOT%20explanation.html)


## Features

- Core classes and properties for mathematical simulation models for real time.
- SHACL shapes for data validation.
- Alignment with existing standards (SML, RDFS, OWL etc.).

This initial version delivers the core model (concepts, relations, and attributes) for modeling SIMBOT information. It includes a baseline reference library of manufacturer-derived concepts, which will be continuously expanded with new data and documentation in future updates.

## Getting Started

1. **Explore the ontology:**  
   Open the main ontology file or browse the documentation in [`docs/`](docs/).

2. **Use in your project:**  
   Import the ontology into your RDF tool or triple store.  
   Example (Turtle):
   ```
   @prefix simbot: <http://buildingdigitaltwin.org/simbot/def/> .
   @prefix sml: <https://w3id.org/sml/def#> .
   # ...other prefixes...
   ```
   **Guidelines**
   - Manufacturers can structure their equipment catalogs using the core model.
   - Developers can use the equipment data to build apps that work across different software vendors. 

> [!NOTE]
> The ontology was generated and populated using **[LACES](https://laceshub.com/)**. 

4. **Validate data:**  
   Use the SHACL shapes provided in the ontology to validate your data.

   **Note about SIMBOT (simulation) validation, testing, certifications, present as metadata in the simbot**

> [!NOTE]
> The onotlogy was Generated and populated using **[LACES (Semmtech)](https://laceshub.com/)**. A dedicated viewer tool is coming soon.
   
## FUNDING

This research has received funding from the European Union’s Horizon Research and Innovation Program under EU project Hycool-IT GA No 101138623 (CWA standardization process), and project DYMAN GA No 101161930 (development of ontologies for data centers).

## License

This ontology is licensed under [CC BY-NC-ND](LICENSE). 

## How to Cite

If you use this ontology, please cite as:
```
O4BSIM - Building Digital Twin Association ASBL 2026

A CEN/CENELEC public CWA has been initiated on the 20th of May 2026: 'Mathematical Simulation models for real time, SIMBOTs', and it can be visited here:
https://www.cencenelec.eu/news-events/news/2026/workshop/20260408_hycool/
```

## Contact

For questions or contributions, please open an issue or contact maintainers at p.legazpi@buildingdigitaltwin.org
- Content of the **Refence library**: pm.demiguel@buildingdigitaltwin.org
- General question please contact: info@buildingdigitaltwin
   - BDTA Website: https://buildingdigitaltwin.org/
   - BDTA address: Borsbeeksebrug 34/1 2600 Antwerpen, Belgium
- Data models questions please contact: apostolisbarekas@semmtech.nl
   - Semmtech website: https://semmtech.com/
   - Semmtech address: Scorpius 124, 2132 LR, Hoofddorp, The Netherlands

---
