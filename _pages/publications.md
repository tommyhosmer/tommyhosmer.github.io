---
layout: page
permalink: /publications/
title: publications
description: publications and works cited
nav: false
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
  <!-- <h2>My Publications</h2>
  {% bibliography --query @*[author="TI Zohdi"] %} -->

  <h2>Works Cited</h2>
  <!-- Render the bibliography for works cited -->
  {% bibliography --query @*[author!="Zohdi"] %}
</div>
