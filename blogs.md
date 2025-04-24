---
title: "Student Blogs"
permalink: /blogs/
layout: page
author_profile: true
---

### List of Student Blogs

{% if site.blogs and site.blogs.size > 0 %}
<ul>
  {% for blog in site.blogs %}
    <li>
      <a href="{{ blog.url }}">{{ blog.title }}</a> -
      <small>{{ blog.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
<p>{{ site.blogs | size }} blog posts found.</p>
{% else %}
<p>No blog posts found. Be the first to submit one!</p>
{% endif %}
