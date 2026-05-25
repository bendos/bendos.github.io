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

<h2 class="year">Articles</h2>

{% bibliography -q @article %}

<h2 class="year">Book Chapters</h2>

{% bibliography -q @incollection %}

<h2 class="year">Books</h2>

{% bibliography -q @book %}

<h2 class="year">Working Papers</h2>

{% bibliography -q @unpublished %}

<h2 class="year">Other Written Work</h2>

{% bibliography -q @techreport %}

</div>
