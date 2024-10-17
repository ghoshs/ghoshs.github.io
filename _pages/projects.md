---
permalink: /projects/
title: "Projects"
author_profile: true
---

<ul>
    <li>
      <a href="{% post_url 2024-09-01-count-information %}">Count Information</a>
    </li>
</ul>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>