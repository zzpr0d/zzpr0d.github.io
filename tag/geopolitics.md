---
layout: default
title: Geopolitics
---

{% for post in site.tags.geopolitics %}
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}
