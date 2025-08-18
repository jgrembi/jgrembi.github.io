---
permalink: /research/
title: "Research"
---

Our research explores biological mechanisms underlying persistent childhood undernutrition.  For this, we focus on the first 1000 days of a child's life, which includes _in utero_ exposures and the first two years of life after birth.

## Current Projects

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}
.project-tile {
  border: 1px solid #ddd;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  background-color: #fafafa;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  transition: transform 0.2s, box-shadow 0.2s;
}
.project-tile:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
.project-tile img {
  width: 100%;
  height: auto;
  border-radius: 6px;
  margin-bottom: 10px;
}
.project-tile h3 {
  margin: 0;
  font-size: 1.2em;
  color: #333;
}
</style>

<div class="project-grid">
  {% for item in site.research %}
    <div class="project-tile">
      <a href="{{ item.url | relative_url }}">
        <img src="{{ item.image | relative_url }}" alt="{{ item.title }}">
        <h3>{{ item.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>




