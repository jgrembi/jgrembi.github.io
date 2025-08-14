---
permalink: /research/
title: "Research"
---

Our research explores biological mechanisms underlying persistent childhood undernutrition...

## Current Projects

<div class="project-grid">
{% for item in site.research %}
<div class="project-tile">
  <a href="{{ item.url | relative_url }}">
    <img src="{{ item.image | relative_url }}" alt="{{ item.title }}" style="width:100%">
    <h3>{{ item.title }}</h3>
  </a>
</div>
{% endfor %}
</div>



