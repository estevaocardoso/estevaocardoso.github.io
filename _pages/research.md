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
This study used R to analyze fuel price data series and apply ARCH and GARCH family forecast models. In it, we model the series using analysis of variance models to understand the behavior of the errors. The main objective of the project is to understand if there are signs of cartel in the behavior of the series either in the variance or in the mean of the series.
---
With Tarcísio Lobato, Brena do Nascimento Carvalho, Zilda Joaquina Cohen Gama dos Santos
