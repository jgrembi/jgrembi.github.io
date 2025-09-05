---
layout: archive
title: "News"
permalink: /news/
author_profile: true
entries_layout: grid
show_excerpts: true
teaser: true
---

{% include base_path %}

{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}
