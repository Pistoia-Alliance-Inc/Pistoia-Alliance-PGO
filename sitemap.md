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
