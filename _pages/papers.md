---
title: "Papers"
layout: archive
permalink: /Papers/
author_profile: true
---

Here are a collection of papers that I have written over my academic carrer. 

{% for post in site.posts %}
 {% if post.category == "Paper" %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}