---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---
<style>
  /* 加粗所有包含 "Li, Tinghua" 或 "厉庭华" 的作者 */
  .bibliography a[href*="Li%2C+Tinghua"],
  .bibliography a[href*="厉庭华"],
  .bibliography:not(a)::text:contains("Li, Tinghua"),
  .bibliography:not(a)::text:contains("厉庭华") {
    font-weight: 700 !important;
    color: inherit;
  }
</style>


<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>