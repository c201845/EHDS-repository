# Legal and Regulatory Compliance Ontologies (RDF/SKOS Framework)

This is a central development repository for legal compliance ontologies. 
This repository is currently kept private as it represents active, ongoing academic research. The work is under continuous integration and will actively be expanded to incorporate multiple European legislative domains and national legal frameworks. 

## Current Focus: Simple EHDS Ontology

The primary artifact currently hosted in this repository is **`EHDS.ttl`**, an expressive, compliance-focused ontology mapping out the Actor, Rights, and Obligations established by the **European Health Data Space (EHDS)** regulation.

### Key Design Features:
* **Structural Paradigm:** Pure **RDF/SKOS** instance layer. The ontology deliberately avoids heavy OWL TBox logical inferences on individual concepts to ensure seamless integration with lightweight open-world data graphs.
* **Granular Legal Mapping:** Models specific statutory clauses (e.g., Article 27(1), Article 34) as individual `skos:Concept` primitives.
* **FOOPS! Validated:** Metadated using semantic web standards (e.g., `dcterms`, `bibo`, `vann`, `foaf`) to guarantee excellent score metrics in automated ontology evaluation.
