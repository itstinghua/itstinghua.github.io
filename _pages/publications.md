---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---

<style>
  /* 加粗第一个作者名 */
  .publications .entry .author:first-child {
    font-weight: bold !important;
  }
  
  /* 或者更精确的选择器 */
  [data-author="Li, Tinghua"] {
    font-weight: bold !important;
  }
</style>

<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} %}
</div>