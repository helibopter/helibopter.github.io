---
layout: default
title: Student Blogs
permalink: /blogs/
---

<h1>Student Blogs</h1>

<ul>
  {% for blog in site.blogs %}
    <li>
      <a href="{{ blog.url }}">{{ blog.title }}</a> - <small>{{ blog.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
