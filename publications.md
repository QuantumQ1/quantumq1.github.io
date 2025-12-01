---
layout: default
title: Publications
---

# Publications
This page lists our recent papers.


{% for paper in site.data.arxiv %}
- **{{ paper.year }}** — [{{ paper.title }}]({{ paper.link }}) — {{ paper.authors }}
{% endfor %}


