---
title: "Simulations"
layout: archive
permalink: /sims/
author_profile: true
---


{% for post in site.posts %}
 {% if post.category == "animation" %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}