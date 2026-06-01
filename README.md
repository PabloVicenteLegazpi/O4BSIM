# SIMBOTs Core Ontology and Reference Library

This repository contains the semantic models, data shapes, and documentation for **SIMBOTs** (Mathematical Simulation models for real time). The ontology is built on top of the **CEN EN 17632-1:2022 (Semantic Modelling and Linking — SML)** framework to enable clear, vendor-neutral engineering data reuse and validation across simulation platforms.

## Overview

- **Core Ontology File:** [`SIMBOTs_core_ontology.ttl`](O4BSIM_SIMBOTs_core_ontology.ttl)
- **Reference Library File:** [`SIMBOTs_Reference_Library.ttl`](O4BSIM_SIMBOTs_Reference_Library.ttl)
- **Interactive Documentation:** - [Ontology Structural Explanation](docs/ontology%20explanation.html)
  - [SIMBOT Methodology & Context Explanation](docs/SIMBOT%20explanation.html)

## Features

- Core classes and properties for mathematical simulation models for real time.
- SHACL shapes for data validation.
- Alignment with existing standards (SML, RDFS, OWL etc.).

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

3. **Validate data:**  
   Use the SHACL shapes provided in the ontology to validate your data.


## License

This ontology is licensed under [CC-BY](LICENSE).

## How to Cite

If you use this ontology, please cite as:
```
European Committee for Standardization. (2026). Mathematical simulation models for real time, SIMBOTs (Draft CEN Workshop Agreement CWA XXXXX). UNE.
```

## Contact

For questions or contributions, please open an issue or contact maintainers at apostolisbarekas@semmtech.nl

---
