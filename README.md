# Pistoia-Alliance-PGO - README

## Pistoia Alliance Pharma General Ontology (PGO)

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please see Terms of Use for details.

Project output page: [https://pistoia-alliance-inc.github.io/Pistoia-Alliance-PGO/](https://pistoia-alliance-inc.github.io/Pistoia-Alliance-PGO/)

Nptes:
* The documentation is a work in progress.
* Sources: the listed sources are not recommedation at this stage.
* Examples of instantiation: the examples are under revision.


### Objective
The first objective of PGO is to define a set of agreed-upon core entities, the PGO "core concepts",  and recommendations for associating controlled terminologies to service data exchange of Research & Development (R&D) information among Pharmaceutical Industry stakeholders.

### Rationale

Information exchange within and across organizations in the pharmaceutical industry is hampered by insufficient or ambiguous asset descriptions.
These descriptions should ideally allow for validation, facilitation of discovery and promotion of interoperability. 
All of these have the potential to deliver significant gains for data exploitation and value delivery in the drug development pipeline, ultimately bringing better treatments to patients.

*The remit of PGO, rather than mandate the use of a resource over another, is to enable clarity when declaring which controlled terminologies are used and why*.

True to the FAIR principles of data management [1] and their use in the Pharmaceutical Industry [2], the PGO aims to
*reuse* existing semantic resources (ontologies and controlled terminologies) as well as open source community software, rather than creating new ones.

The initial goal of PGO is to provide enough coverage to represent essential entities, most frequently used or referred to when exchanging data.

**The key objectives are therefore**:
- [x] Unambiguously identifying essential entities
- [x] Specifying, when applicable, value-sets for key attributes by relying on community-agreed controlled terminologies
- [x] Creating machine actionable documentation

On the issue of defining value-sets, PGO's intent is to provide clear mechanisms to enable unambiguous declaration of the resources used as well as capture the criteria used to select semantic artifacts. We will do so by following community best practices. 

## Project Outputs Phase 1

### [List of core concepts](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/development/2025_PGO_V1.0_core_concepts.md)

### [Process](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/wiki/2024%E2%80%90PGO-process)

### [List of experts](https://pistoia-alliance-inc.github.io/Pistoia-Alliance-PGO/list-of-experts.html)

### [Summaries of alignments meetings](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/wiki/2024_PGO_V1.0-_summary_meetings)

### [High level use case report- project webpage: see "deliverables and resources"](https://www.pistoiaalliance.org/project/pharma-general-ontology/)

### Technology
The project is currently using the [LinkML](https://linkml.io) for representing and documenting each of the types [3].


## Project Roadmap
- 2023: initial scoping and identification of core concepts FAIR implementation project

Phase 1
- 2024: process flow, expert identification, core concept candidate definitions
- 2024: high level use case identificaiton and definition [4]
- 2025: experts consultation and alignment, formalization of core concepts R&ED
- 2025: implementation and testing using LinkML
- 2025: first public release of the core-concepts

Phase 2
- 2025 application and "field testing"
- 2025 complement core-concept vocabulary
- 2026 updated version of core-concept vocabulary


## Project sponsors 
Phase 1
- Astrazeneca
- Chiesi Group
- Glaxo Smith Kline PLC
- Merck KgaA
- Novo Nordisk
- Pfizer
- Hoffman la Roche AG


## References:
1. [https://www.nature.com/articles/sdata201618](https://www.nature.com/articles/sdata201618)
2. [https://pubmed.ncbi.nlm.nih.gov/35066138/](https://pubmed.ncbi.nlm.nih.gov/35066138/)
3. [https://pubmed.ncbi.nlm.nih.gov/36125173/](https://pubmed.ncbi.nlm.nih.gov/36125173/)
4. [PGO deliverable D2.2-Use cases](https://www.pistoiaalliance.org/resource-library/pharma-general-ontology-use-cases/)
