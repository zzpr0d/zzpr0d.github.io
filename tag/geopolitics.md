---
layout: default
title: Geopolitics
---

<h1 class="page-title">Geopolitics</h1>

<ul class="post-list">
  {% for post in site.tags.geopolitics %}
    <li style="margin-bottom: 30px; list-style: none;">
      <span style="color: #888; font-family: 'Inter', sans-serif; font-size: 0.8rem;">{{ post.date | date: "%B %d, %Y" }}</span>
      <h3 style="margin: 5px 0;">
        <a href="{{ post.url | relative_url }}" style="text-decoration: none; color: #1a1a1a; font-family: 'Playfair Display', serif; font-size: 1.5rem;">{{ post.title }}</a>
      </h3>
      <p style="color: #666; font-size: 0.95rem;">{{ post.excerpt | strip_html | truncatewords: 25 }}</p>
    </li>
  {% endfor %}
</ul>
