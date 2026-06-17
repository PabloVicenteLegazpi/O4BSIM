# SIMBOTs Core Ontology and Reference Library

This repository contains the O4BSIM ontology and Reference library for **SIMBOTs** (Mathematical Simulation models for real-time). The ontology is built on top of the **CEN EN 17632-1:2022 (Semantic Modelling and Linking — SML)** framework to enable clear communication and   data reuse about mathematical simulations.
SIMBOT definition is following the specifications provided by the open CEN workshop 'Mathematical Simulation models for real time, SIMBOTs', which can be found in this link: https://www.cencenelec.eu/news-events/news/2026/workshop/20260408_hycool/
The intention of this ontology and reference library is to have a demonstration tool for future developments. Initially, SIMBOTs are developed for data centers of the pilots included in HYCOOL-IT EU project (GA No 101138623), and project DYMAN (GA No 101161930).

## Overview

- **Core Ontology File:** [`O4BSIM_SIMBOTs_core_ontology.ttl`](O4BSIM_SIMBOTs_core_ontology.ttl)
- **Reference Library File:** [`O4BSIM_SIMBOTs_Reference_Library.ttl`](O4BSIM_SIMBOTs_Reference_Library.ttl)
- **Interactive Documentation:** - [Ontology Structural Explanation](docs/ontology%20explanation.html)
  - [SIMBOT Methodology & Context Explanation](docs/SIMBOT%20explanation.html)

- **Interactive documentation should be visible in the browser dorectly, see Digichecks ontology//explanation, it is not publish yet**
   - **SERIALIZATIONS IN RDF, OWL, TTL...**
  - **Interactive documentation much follow the same format then digichecks ontology**

## Features

- Core classes and properties for mathematical simulation models for real time.
- SHACL shapes for data validation.
- Alignment with existing standards (SML, RDFS, OWL etc.).

**TO BE COMPLETED A BIT MORE**

## Getting Started

1. **Explore the ontology:**  
   Open the main ontology file or browse the documentation in [`docs/`](docs/).

2. **Use in your project:**  
   Import the ontology into your RDF/OWL tool or triple store.  
   Example (Turtle):
   ```
   @prefix simbot: <http://buildingdigitaltwin.org/simbot/def/> .
   @prefix sml: <https://w3id.org/sml/def#> .
   # ...other prefixes...
   ```
**Open ontology in protege and graphdb (free common tools, reference). Explain how to do it**
**The ontology was generated and populated with LACES (Semmtech), future possible availability of viewer**
   **Please explain this thinking on manufacturers and software developers, alignment with future DPPs, functional information, device ontology**
   **Intention of the SIMBOTs and KG:... to comunicate equipment data between manufacturers and software developers**
   **MANUFACTURERS: how to load your equipment.., implementation of a cathalogue, contact for help, testing and verification**
   **Software developers: how to download equipment data, where to find help, what you can do...**
   **THESE CAN BE A BRIEF EXPLANATION IN THE README FILE, AND LATER IN DETAILED DOCUMENTATION WE COULD ADDING EXAMPLES AND BETTER DESCRIPTION**

4. **Validate data:**  
   Use the SHACL shapes provided in the ontology to validate your data.

   **Note about SIMBOT (simulation) validation, testing, certifications, present as metadata in the simbot**

> [!NOTE]
> The onotlogy was Generated and populated using **[LACES (Semmtech)](https://laceshub.com/)**. A dedicated viewer tool is coming soon.
   
## FUNDING

This research has received funding from the European Union’s Horizon Research and Innovation Program under EU project Hycool-IT GA No 101138623 (CWA standardization process), and project DYMAN GA No 101161930 (development of ontologies for data centers).

## License

This ontology is licensed under [CC-BY](LICENSE). 

**PVL note: License CC BY-NC-ND 4.0 (to indicate details at files provided by Apostolis)**
**I mean, no links which may be broken**

## How to Cite

If you use this ontology, please cite as:
```
O4BSIM - Building Digital Twin Association ASBL 2026

A CEN/CENELEC public CWA has been initiated on the 20th of May 2026: 'Mathematical Simulation models for real time, SIMBOTs', and it can be visited here:
https://www.cencenelec.eu/news-events/news/2026/workshop/20260408_hycool/
```

## Contact

For questions or contributions, please open an issue or contact maintainers at p.legazpi@buildingdigitaltwin.org
Content of the **Knowledge Graph**: pm.demiguel@buildingdigitaltwin.org
General question please contact info@buildingdigitaltwin
https://buildingdigitaltwin.org/
BDTA address: Borsbeeksebrug 34/1 2600 Antwerpen, Belgium

*Add some details about Semmtech**

## Processes (BPMN)
**JUST A BRIEF DSCRIPTION ABOUT THIS**

**process 1: new manufacturer, model, new simbot, PACKAGE CONCEPT**

**SIMBOT status, adding info, modifing SIMBOT info**
**look up for a simbot, similar simbots, criteria (power, discipline, manufacturer,...**
**downloading/copying/transposing... a simbot for a developer - Massive download of SIMBOTs for a library**
**Defining a new discipline (only one now) - Compiling a discipline: abstracts and meta info FOR THE FUTURE, NOT NOW**

**we should be adding processes with tasks/responsible/roles for transparency**
**STAKEHOLDERS for process 1: Manufacturer agent, BDTA onto editor/operator, BDTA supervisor, BDTA simulation editor/operator, public**
**Maximum time response (about the processes), reporting, rules to comply**


---
