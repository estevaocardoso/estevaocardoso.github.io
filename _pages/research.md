---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

> [**Detection of cartel evidence: a case study for Belém/PA and Santarém/PA using volatility models**](https://rsdjournal.org/index.php/rsd/article/view/21397)   
With Tarcísio Lobato, Brena do Nascimento Carvalho, Zilda Joaquina Cohen Gama dos Santos
