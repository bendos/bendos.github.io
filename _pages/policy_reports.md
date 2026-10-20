---
layout: page
permalink: /policy_reports/
title: policy reports
description: reports written for research centres, think tanks and government agencies, in reverse chronological order. Most are in French (marked FR).
nav: true
nav_order: 4
---

<!-- _pages/policy_reports.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -q @techreport[category=policy] %}

</div>
