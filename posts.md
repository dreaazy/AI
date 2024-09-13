---
layout: posts
title: Posts
permalink: /posts/
---

<h2>All Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
