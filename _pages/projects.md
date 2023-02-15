---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

List of my research projects, presented in chronological order.

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single-project.html %}
{% endfor %}