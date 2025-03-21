---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 3
---

&nbsp;

#### peer-reviewed papers

<div class="publications">
{% bibliography -f papers -q @*[year={{y}}]* %}
</div>

&nbsp;

#### working papers

<div class="publications">
{% bibliography -f workingpapers -q @*[year={{y}}]* %}
</div>

&nbsp;

#### datasets

<div class="publications">
{% bibliography -f datasets -q @*[year={{y}}]* %}
</div>

&nbsp;

#### conference proceedings

<div class="publications">
{% bibliography -f conferences -q @*[year={{y}}]* %}
</div>