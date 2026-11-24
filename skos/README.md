# PGO SKOS release files

Pharma General Ontology (PGO), version 2.0, build date 2026-11-18.
A controlled vocabulary of 35 core pharmaceutical R&D concepts with approved definitions,
preferred sources, examples and external mappings, developed by experts in the Pistoia Alliance PGO project.

| File | Content |
| --- | --- |
| `pgo-skos.ttl` | Whole vocabulary, Turtle (use this one for BioPortal) |
| `pgo-skos.rdf` | Same content, RDF/XML |
| `pgo-skos.jsonld` | Same content, JSON-LD |
| `pgo-concepts.csv` | One row per concept: ID, IRI, label, definition, source, licence, synonyms, mappings |

Structure: one `skos:ConceptScheme` with one top concept, `PGO-00000000` (label PGO-ROOT, a technical root).
The list is flat: every concept has `skos:broader` pointing to the root.

Licence: CC BY 4.0, except where a concept states another licence (for example a definition adopted
from a source under CC BY-SA 4.0). Check `dcterms:license` on the concept.

Contact: info@pistoiaalliance.org or https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/issues

These files are generated. Do not edit them by hand. Validation: `pgo_validate_skos.py` (9 checks, all passed).
