---
permalink: /projects/
title:
author_profile: true
---
<h3>Projects</h3>
<ul class="small">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
