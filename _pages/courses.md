---
layout: default
title: "Our Courses"
permalink: /courses/
---

<h1>Our Courses</h1>

<div class="courses-list">
  {% for course in site.courses %}
    <div class="course">
      <h2>{{ course.title }}</h2>
      <i class="fa {{ course.icon }}"></i>
      <img src="{{ course.image }}" alt="{{ course.title }}">
      <p>{{ course.description }}</p>
      <p><strong>Duration:</strong> {{ course.duration }}</p>
      <a href="/{{ course.slug }}">Learn More</a>
    </div>
  {% endfor %}
</div>
