---
layout: page
title: Portfolio
permalink: /portfolio/
---
<div class="portfolio">
  {% for item in site.portfolio %}
    <div class="portfolio-item">
      <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
      <img src="{{ item.image }}" alt="{{ item.title }}">
      <p>{{ item.description }}</p>
    </div>
  {% endfor %}
</div>