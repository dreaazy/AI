---
layout: course
title: AI Course Overview
permalink: /course/
---

# AI Course Overview

Welcome to the AI course! Here are the chapters you can explore:

<ul>
  {% for chapter in site.pages %}
    {% if chapter.path contains 'chapters' %}
      <li><a href="{{ chapter.url | relative_url }}">{{ chapter.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
