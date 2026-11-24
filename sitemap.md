---
title: Site map
permalink: /sitemap/
---

# Site map

This page is generated automatically at every publish. New pages added to the repository appear here without any edit.

{% assign all = site.pages | sort: "path" %}

## Main pages

{% for p in all %}{% unless p.path contains '/' %}{% if p.path contains '.md' or p.path contains '.html' %}{% unless p.url contains 'sitemap' %}
- [{{ p.title | default: p.name }}]({{ p.url | relative_url }})
{% endunless %}{% endif %}{% endunless %}{% endfor %}

## PGO V2.0 core concepts

{% for p in all %}{% assign head = p.path | slice: 0, 9 %}{% if head == 'concepts/' %}
- [{{ p.title | default: p.name }}]({{ p.url | relative_url }})
{% endif %}{% endfor %}

## PGO V2.0 vocabulary files

- [pgo-skos.ttl (Turtle)]({{ '/skos/pgo-skos.ttl' | relative_url }})
- [pgo-skos.rdf (RDF/XML)]({{ '/skos/pgo-skos.rdf' | relative_url }})
- [pgo-skos.jsonld (JSON-LD)]({{ '/skos/pgo-skos.jsonld' | relative_url }})
- [Concept table (CSV)]({{ '/tables/PGO_V2.0_concepts_2026-11-24.csv' | relative_url }})
- [Concept table (Excel)]({{ '/tables/PGO_V2.0_concepts_2026-11-24.xlsx' | relative_url }})

## PGO V2.0 process (Phase 2)

- [Simplified flow](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/process/PGO-process-phase-2.md)
- [Detailed flow](https://github.com/Pistoia-Alliance-Inc/Pistoia-Alliance-PGO/blob/main/process/PGO-process-phase-2-detailed.md)

## PGO V1.0 core concepts

{% for p in all %}{% if p.path contains 'PGOv1.0-core-concepts/' %}
- [{{ p.title | default: p.name }}]({{ p.url | relative_url }})
{% endif %}{% endfor %}

## Visualisation

- [PGO hex view]({{ '/viz/pgo-pub-types-hexagon.html' | relative_url }})

## Branding

{% for p in all %}{% if p.path contains 'Pistoia-Alliance-style/' %}
- [{{ p.title | default: p.name }}]({{ p.url | relative_url }})
{% endif %}{% endfor %}

## Machine-readable

- [sitemap.xml]({{ '/sitemap.xml' | relative_url }}) (for search engines)
