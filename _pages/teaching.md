---
layout: page
permalink: /teaching/
title: Talks & Posters
nav: true
nav_order: 2
---

## Talks
{% for talk in site.talks %}
- **{{ talk.title }}** — {{ talk.event }}, {{ talk.date | date: "%B %Y" }}
{% endfor %}

## Posters
{% for poster in site.posters %}
- **{{ poster.title }}** — {{ poster.event }}, {{ poster.date | date: "%B %Y" }}
{% endfor %}
