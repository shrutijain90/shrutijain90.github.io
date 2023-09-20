---
layout: page
permalink: /publications/
title: publications
description:
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015]
nav: true
order: 3
---
&nbsp;

#### peer-reviewed papers

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

&nbsp;

#### datasets

<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f datasets -q @*[year={{y}}]* %}
{% endfor %}

</div>

&nbsp;

#### working papers

<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f workingpapers -q @*[year={{y}}]* %}
{% endfor %}

</div>

&nbsp;

#### conference proceedings

<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

</div>