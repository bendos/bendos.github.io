---
layout: page
permalink: /publications/
title: publications
description: in reverse chronological order, split by publication type.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="year">Published Articles and Book Chapters</h2>

{% bibliography -q @article || @incollection || @book %}

<h2 class="year">Working Papers</h2>

{% bibliography -q @unpublished %}

<h2 class="year">Other Written Work</h2>

{% bibliography -q @techreport %}

</div>
