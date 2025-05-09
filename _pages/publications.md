---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---

<div class="publications">
  {% for entry in site.data.papers %}
    <div class="entry">
      <!-- 加粗第一作者 -->
      {% assign authors = entry.author | split: " and " %}
      <span class="authors">
        {% for author in authors %}
          {% if forloop.first %}
            <strong>{{ author }}</strong>
          {% else %}
            {{ author }}
          {% endif %}
          {% unless forloop.last %}, {% endunless %}
        {% endfor %}
      </span>
      <!-- 其他字段（标题、期刊等） -->
      <div class="title">{{ entry.title }}</div>
      <div class="journal">{{ entry.journal }}, {{ entry.year }}</div>
    </div>
  {% endfor %}
</div>