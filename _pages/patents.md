---
layout: page
permalink: /patents/
title: Patents
description: Patents I have filled.
nav: true
nav_order: 4
---

<!-- _pages/patents.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

	{% bibliography --query @*[type=patent]* %}

</div>
