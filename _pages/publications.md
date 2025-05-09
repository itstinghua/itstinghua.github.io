---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---

<style>
  /* 强制加粗第一作者 */
  .publications .entry .authors:first-child {
    font-weight: bold !important;
  }
</style>

<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} %}
</div>