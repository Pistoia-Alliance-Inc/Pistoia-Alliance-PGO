# PGO SKOS validation report

Folder: `../8-PGO-T-public-RDF/SKOS/merged`
Concepts (root excluded): 35  |  Triples: 2927  |  Version 2.0  |  Build date 2026-11-18

| # | Check | Result | Detail |
| --- | --- | --- | --- |
| 1 | Turtle, RDF/XML and JSON-LD hold the same graph | PASS |  |
| 2 | One skos:ConceptScheme with skos:hasTopConcept | PASS | 1 scheme(s), 1 top concept(s) |
| 3 | owl:Ontology with versionIRI and versionInfo | PASS | 1 ontology node(s); versionIRI https://spec.pistoiaalliance.org/PGO/ontology/releases/2026-11-18/pgo-skos |
| 4 | Scheme header complete | PASS |  |
| 5 | Every concept: label, definition, scheme, broader; no cycles | PASS |  |
| 6 | Preferred labels are unique | PASS | {} |
| 7 | Concept IRIs end with PGO-<8 digits> | PASS |  |
| 8 | No persons, no placeholders or internal IDs | PASS | 0 person(s); found: [] |
| 9 | CSV matches the concepts | PASS | csv 35, rdf 35 |

**Overall: PASSED**
