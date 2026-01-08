---
layout: page
title: Quotes
permalink: /tag/quotes/
---

### Quotes
*A collection of my favorite quotes.*

<hr>

{% for post in site.tags.quotes %}
<div style="margin-bottom: 30px;">
    <span style="font-size: 0.8em; color: #888;">{{ post.date | date: "%B %d, %Y" }}</span>
    <br>
    <a href="{{ post.url }}" style="font-family: 'Playfair Display', serif; font-size: 1.4em; text-decoration: none; color: #222;">{{ post.title }}</a>
  </div>
{% endfor %}
