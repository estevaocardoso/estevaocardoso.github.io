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

## Publications
> [**Detection of cartel evidence: a case study for Belém/PA and Santarém/PA using volatility models**](https://rsdjournal.org/index.php/rsd/article/view/21397)      
*Research, Society and Development*, [S. l.], v. 10, n. 13, p.                                                                                                        
This study used R to analyze fuel price data series and apply ARCH and GARCH family forecast models. In it, we model the series using analysis of variance models to understand the behavior of the errors. The main objective of the project is to understand if there are signs of cartel in the behavior of the series either in the variance or in the mean of the series.
---
With Tarcísio Lobato, Brena do Nascimento Carvalho, Zilda Joaquina Cohen Gama dos Santos

> [**Analysis project of the historical series of fuels of municipalities in the state of Pará using Python**](https://docs.google.com/presentation/d/1ujuw85dBVfFrFYNTBzde2B_0GW9FhTiO/present?slide=id.p4)                                                                      
*29º Simpósio de Iniciação CIentífica e Tecnológica da USP - SIICUSP 2021*                                                                                           
This study used python to analyze data series and applied two filtering methodologies to the price series of retail fuel stations in the municipalities of Belém/PA, Marabá/PA and Santarém/PA in search of cartel evidence: i) the methodology used by the ANP based on the observation of price variation coefficients; and (ii) the methodology described by Ragazzo (2006) which consists of verifying the correlation coefficient between the coefficient of variation and the resale margin.
---
With Tarcísio Lobato

## Other projects
> [**Data analysis project for soybean crops from 2009/10 to 2021/22 using Python**](https://drive.google.com/file/d/1jCygbScqzbBCeuib1F76vWX-Ry9S_H49/view?usp=sharing)                                                                                                                                                         
This project presents the results of data analysis of the soybean crop historical series from the years 2009/2010 to 2021/2022 for all federal regions of Brazil. The main objective of this analysis is to understand how the evolution of soy producers' income occurred over the selected period.
---

> [**Building a Database for Volleyball data from international competitions with Machine Learning analysis**](https://github.com/estevaocardoso/projetos-estevao/tree/main/VOLLEYBALL)
> In this project, I am conducting webscraping on multiple websites to build a database of volleyball data from players participating in FIVB competitions. Additionally, I am performing a machine learning analysis to understand the performance of the players and assess how their height influences the results of their teams

