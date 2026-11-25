# Pistoia-Alliance-PGO

## Pistoia Alliance Pharma General Ontology (PGO)

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), except where a concept states another license. Please see the [full license text](./LICENCE.md) for details.

<!-- TOC start  -->

- [Version 2.0](#version-20-november-2026)
- [Objective](#objective)
- [Rationale](#rationale)
- [Project webpage](#project-webpage)
- [Why PGO? Hear from the Steering Committee](#why-pgo-hear-from-the-steering-committee)
- [Version 1.0 outputs (Phase 1)](#version-10-outputs-phase-1)
- [Project Roadmap](#project-roadmap)
- [Project sponsors](#project-sponsors)
- [List of experts](#list-of-experts)
- [References](#references)
- [Site map](./sitemap.md)

<!-- TOC end -->

## Version 2.0 (November 2026)

PGO version 2.0 contains **35 core concepts** with approved definitions, preferred sources, examples, synonyms, and mappings to external terminologies. Read the [release notes](./RELEASE-NOTES.md) and the [repository guide](./README.md) first.

| What you need | Where to find it |
| --- | --- |
| One page per concept | [concepts folder](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/tree/main/concepts) |
| The vocabulary for your terminology tool (Turtle, RDF/XML, JSON-LD) | [skos folder](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/tree/main/skos) |
| The concept table as CSV or Excel | [CSV](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/tables/PGO_V2.0_concepts_2026-11-24.csv), [Excel](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/tables/PGO_V2.0_concepts_2026-11-24.xlsx) |
| How the concepts were developed in Phase 2 | [Simplified flow](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/process/PGO-process-phase-2.md), [detailed flow](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/process/PGO-process-phase-2-detailed.md) |
| The experts who contributed | [List of experts, version 2.0](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/experts/list-of-experts-PGO-V2.0.0.md) |

The identifiers of the concepts already in version 1.0 (`PGO-00000001` to `PGO-00000017`) have not changed.

**What comes next:** Phase 3 will expand the vocabulary, create the first models, and engage in dissemination to foster adoption.

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
The project team initial focus is on the research and early development (R&ED) phase. 

**The key objectives are therefore**:
- [x] Unambiguously identifying essential entities
- [x] Specifying, when applicable, value-sets for key attributes by relying on community-agreed controlled terminologies
- [x] Creating machine actionable documentation

On the issue of defining value-sets, PGO's intent is to provide clear mechanisms to enable unambiguous declaration of the resources used as well as capture the criteria used to select semantic artifacts. We will do so by following community best practices. 

## Project webpage
Additional documents from the project are accessible via the [Pharma General Ontology project webpage](https://www.pistoiaalliance.org/project/pharma-general-ontology/). A log in to access documents reserved to Pistoia Alliance member companies is required.


## Why PGO? Hear from the Steering Committee

Members of the PGO Steering Committee explain in short videos why a shared vocabulary for pharma R&D matters for data, AI, and the industry. Watch them on the [Why PGO? page](https://pistoiaalliance.org/why-pgo/):

- AI Requires a Common Data Language
- Optimize Your Data Lifecycle
- Why a Collective, Shared Solution?

## Version 1.0 outputs (Phase 1)

Version 1.0 stays in this repository, at the same locations as before, so existing links keep working. The releases are tagged `docs-public-V1.0.0` to `docs-public-V1.0.2`, see the [Releases page](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/releases).

### [List of core concepts](./2025_PGO_V1.0_core_concepts.md)

### [High level use case report](https://www.pistoiaalliance.org/resource-library/pharma-general-ontology-use-cases/)

### [Process (Phase 1)](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/wiki/2024%E2%80%90PGO-process)

## Project Roadmap
- 2023: initial scoping and identification of core concepts from the FAIR implementation project

*Phase 1*
- 2024: process flow, expert identification, core concept candidate definitions
- 2024: high level use case identification and definition [3]
- 2025: experts consultation and alignment, formalization of core concepts R&ED
- 2025: implementation and testing of the core concepts
- 2025: first release of the recommended core-concepts

*Phase 2*
- 2025: application and "field testing"
- 2025: complement core-concept vocabulary
- 2026: version 2.0 of the core-concept vocabulary, with 35 concepts
- 2026: machine-readable version of the PGO terminology (SKOS), released with version 2.0

*Phase 3 (planned)*
- Expand the vocabulary
- Create the first models
- Engage in dissemination to foster adoption


## Project sponsors

PGO is funded by member companies of the Pistoia Alliance.

| Sponsor | Phase 1 (2024 to 2025) | Phase 2 (2025 to 2026) |
| --- | :---: | :---: |
| AstraZeneca | ✓ | ✓ |
| Chiesi Group | ✓ | ✓ |
| GSK | ✓ | ✓ |
| Merck KGaA | ✓ | ✓ |
| Novo Nordisk | ✓ | ✓ |
| Pfizer | ✓ | ✓ |
| Roche | ✓ | ✓ |
| Vertex Pharmaceuticals |  | ✓ |

## List of PGO experts consulted
- [Version 2.0](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/experts/list-of-experts-PGO-V2.0.0.md)
- [Version 1.0](./list-of-experts.md)

## References:
1. [https://www.nature.com/articles/sdata201618](https://www.nature.com/articles/sdata201618)
2. [https://pubmed.ncbi.nlm.nih.gov/35066138/](https://pubmed.ncbi.nlm.nih.gov/35066138/)
3. [PGO deliverable D2.2-Use cases](https://www.pistoiaalliance.org/resource-library/pharma-general-ontology-use-cases/)
4. [The Pistoia Alliance Pharma General Ontology: Experience Using LinkML in Pharma](https://www.scopus.com/pages/publications/105040195906)


<div class="logoDiv"><img class="logo" src="Pistoia-Alliance-style/2024-08_Pistoia_Alliance_Logo_White.png"></div>
