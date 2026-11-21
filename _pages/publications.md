---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed publications in reverse chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @article %}

<h2 class="mt-5">theses</h2>

{% bibliography --query @*[keywords=thesis] %}

</div>
