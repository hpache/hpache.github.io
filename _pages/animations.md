---
title: "Simulations"
layout: archive
permalink: /sims/
author_profile: false
header:
 overlay_image: /assets/headerImages/BZ.png
 overlay_filter: linear-gradient( rgba(0, 0, 0, 0.5), rgba(37, 42, 52, 0.5))
---


{% for post in site.posts %}
 {% if post.category == "animation" %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}