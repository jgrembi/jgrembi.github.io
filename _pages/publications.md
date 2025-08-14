---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
show_excerpts: true
---


{% if site.author.googlescholar %}
  <div class="wordwrap">You can find a full list of my manuscripts on <a href="https://scholar.google.com/citations?user=noeNd8EAAAAJ&hl=en">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



