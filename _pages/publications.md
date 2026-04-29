---
layout: page
permalink: /publications/
title: publications
description: selected publications and manuscripts.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Publications</h2>
{% bibliography --group_by none --query @*[category=publication]* %}

<h2>arXiv / Manuscripts</h2>
{% bibliography --group_by none --query @*[category=manuscript]* %}

</div>
