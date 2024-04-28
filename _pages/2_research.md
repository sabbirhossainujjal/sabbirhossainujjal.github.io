---
layout: page
permalink: /research/
title: Research
description: 
years: [2024]
nav: true
nav_order: 2
---
A list of my publications are provided here. Google scholar link is provided [here](https://scholar.google.com/citations?user=5zj2Ho0AAAAJ&hl=en&oi=sra). I will keep updating the list over time. These are only the articles that have been published in journals or conferences. Un-published works are listed under __"Projects"__.
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
