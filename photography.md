---
layout: page
title: Photography
---

<ul id="photo-grid">
  {% for photo in site.photography %}
    <li>
      <a href="{{ photo.url }}">
        <img src="{{ photo.thumb }}" alt="{{ photo.title }}" />
      </a>
    </li>
  {% endfor %}
</ul>
