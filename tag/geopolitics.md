---
layout: default
title: Geopolitics & Strategy
permalink: /tag/geopolitics/
---

### Global Analysis
*A collection of my thoughts on international relations, power shifts, and global trends.*

<hr>

{% for post in site.tags.geopolitics %}
  <div style="margin-bottom: 30px;">
    <span style="font-size: 0.8em; color: #888;">{{ post.date | date: "%B %d, %Y" }}</span>
    <br>
    <a href="{{ post.url }}" style="font-family: 'Playfair Display', serif; font-size: 1.4em; text-decoration: none; color: #222;">{{ post.title }}</a>
  </div>
{% endfor %}
