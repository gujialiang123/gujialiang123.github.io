---
layout: page
permalink: /publications/
title: publications
description: published and accepted papers, followed by arXiv manuscripts.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Published / Accepted Papers</h2>
{% bibliography --group_by none --query @*[category=publication]* %}

<h2>arXiv / Manuscripts</h2>
{% bibliography --group_by none --query @*[category=manuscript]* %}

</div>
