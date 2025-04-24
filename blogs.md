---
title: "Student Blogs"
permalink: /blogs/
layout: page
author_profile: true
---

### List of Student Blogs

<ul>
  {% for blog in site.blogs %}
    <li>
      <a href="{{ blog.url }}">{{ blog.title }}</a> -
      <small>{{ blog.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

<!-- Debugging line: show the blogs collection -->
<p>{{ site.blogs | size }} blog posts found.</p>
