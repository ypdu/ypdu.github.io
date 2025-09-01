---
layout: archive
title: "Courses"
permalink: /courses/
author_profile: false
classes: courses-page
---

Here you'll find information about courses I teach or have been involved in teaching.

{% for post in site.courses reversed %}
  {% include archive-single.html %}
{% endfor %}