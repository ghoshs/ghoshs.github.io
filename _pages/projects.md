---
permalink: /projects/
title: "Projects"
author_profile: true
---

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}
{% include paginator.html %}