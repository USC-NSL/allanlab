---
title: Publications
layout: publications
permalink: /publications/
description: Publications in reverse chronological order. 
years: [2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011]
nav: true
---
<!-- _pages/publications.md -->

## Publications

For publications prior to 2011, see [DBLP](https://dblp.org/pid/g/RameshGovindan.html). 

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
