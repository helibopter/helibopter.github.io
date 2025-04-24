---
title: "Student Blogs"
permalink: /blogs/
layout: default
---

<h1>List of Student Blogs</h1>

<ul>
  {% for blog in site.blogs %}
    <li>
      <a href="{{ blog.url }}">{{ blog.title }}</a> - {{ blog.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
