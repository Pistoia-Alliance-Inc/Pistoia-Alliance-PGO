
# Pharma General Ontology (PGO), version 2.0

The Pharma General Ontology (PGO) is a shared reference vocabulary for the pharmaceutical industry. It does not tell you which terminology to use. It helps you declare clearly which controlled terminologies you use, and why, so that organizations can exchange and combine data. PGO is developed by experts in the Pistoia Alliance PGO project.

Version 2.0 contains **35 core concepts** with approved definitions, preferred sources, examples, synonyms, and mappings to external terminologies.

## What is in this repository

| Folder | Content |
| --- | --- |
| `concepts/` | One Markdown page per concept, for example `PGO-00000001.md` |
| `skos/` | The whole vocabulary as a Simple Knowledge Organization System (SKOS) controlled vocabulary: `pgo-skos.ttl` (Turtle), `pgo-skos.rdf` (RDF/XML), `pgo-skos.jsonld` (JSON-LD), and `pgo-concepts.csv` (one row per concept) |
| `tables/` | The concept table, one row per concept, as `PGO_V2.0_concepts_2026-11-24.csv` (comma-separated values) and `PGO_V2.0_concepts_2026-11-24.xlsx` (Excel) |
| `experts/` | The list of experts who contributed to PGO |

## Using the vocabulary

- Browse the concept pages in `concepts/`.
- Load `skos/pgo-skos.ttl` into your terminology tool. The vocabulary is flat: every concept points to one technical top concept (`PGO-00000000`, label PGO-ROOT).
- Concept identifiers have the form `PGO-00000001`. The identifiers of concepts that were already in version 1.0 (`PGO-00000001` to `PGO-00000017`) have not changed.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0), except where a concept states another license. For example, the definition of Molecular_Target is adopted from the Drug Target Ontology and stays under CC BY-SA 4.0. Check the license on each concept.

## Earlier versions

PGO version 1.0 stays available in this repository, unchanged and in the same locations as before, for example in the folder `PGOv1.0-core-concepts/` in the repository root. It holds the 17 core concepts of version 1.0 (`PGO-00000001` to `PGO-00000017`) as Markdown pages. The identifiers did not change in version 2.0, but the concept pages, definitions, sources, and examples were revised. Use version 1.0 when you need to reproduce work that cites it.

| Version | Date | Release page |
| --- | --- | --- |
| 1.0.2 (last 1.0 release) | October 2026 | [docs-public-V1.0.2](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/releases/tag/docs-public-V1.0.2) |
| 1.0.1 | June 9, 2026 | [docs-public-V1.0.1](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/releases/tag/docs-public-V1.0.1) |
| 1.0.0 (first public release) | April 3, 2026 | [docs-public-V1.0.0](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/releases/tag/docs-public-V1.0.0) |


## How the files are produced

The concept pages and the SKOS files are generated from curated records, checked against the contributors' consent, and validated before release. Please do not edit them by hand. Send changes as an issue instead.

## Contact and feedback

Questions, corrections, and suggestions: open an issue in this repository or write to info@pistoiaalliance.org. 