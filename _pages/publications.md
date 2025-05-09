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
  // 遍历所有文献条目
  document.querySelectorAll('.publications .entry').forEach(entry => {
    const authorElem = entry.querySelector('[itemprop="author"]');
    if (authorElem) {
      const authors = authorElem.textContent.split(' and ');
      if (authors.length > 0) {
        // 替换为加粗后的HTML
        authorElem.innerHTML = `<strong>${authors[0]}</strong> and ${authors.slice(1).join(' and ')}`;
      }
    }
  });
});
</script>