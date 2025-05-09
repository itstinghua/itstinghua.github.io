---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---



<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} %}
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // 精确匹配作者名
  const entries = document.querySelectorAll('.publications .entry [itemprop="author"]');
  entries.forEach(el => {
    el.innerHTML = el.innerHTML.replace('Li*, Tinghua', '<strong>Li*, Tinghua</strong>');
    el.innerHTML = el.innerHTML.replace('厉庭华*', '<strong>厉庭华*</strong>');
    el.innerHTML = el.innerHTML.replace('厉庭华', '<strong>厉庭华</strong>');
  });
});
</script>