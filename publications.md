---
layout: default
title: Publications
---

# Publications

This page lists our recent papers. You can maintain this by hand or use the provided GitHub Action to auto-update `_data/arxiv.yml` and then render here.

{% for paper in site.data.arxiv %}
- **{{ paper.year }}** — [{{ paper.title }}]({{ paper.link }}) — {{ paper.authors }}
{% endfor %}


## Manual entry example

- , *Title of paper*, Journal (2025). arXiv:xxxx.xxxxx
