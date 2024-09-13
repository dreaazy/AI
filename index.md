---
layout: default
title: Home
---

## Recent Posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
