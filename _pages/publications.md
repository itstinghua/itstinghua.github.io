---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---

<style>
  /* 新方案：直接匹配作者字段容器 */
  .publications .entry div[itemprop="author"] {
    font-weight: normal; /* 先重置所有作者 */
  }
  /* 通过伪元素或JavaScript动态加粗第一个作者名 */
  .publications .entry div[itemprop="author"]::first-line {
    font-weight: bold !important;
  }
</style>

<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} %}
</div>