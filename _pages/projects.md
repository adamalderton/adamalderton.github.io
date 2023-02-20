---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

This page is under construction!

{% for post in site.projects reversed%}
  {% include archive-single.html %}
{% endfor %}