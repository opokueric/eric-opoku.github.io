---
layout: archive
title: "Teaching"
permalink: /teach/
author_profile: true
---

{% include base_path %}

### Current Courses (University of Toronto, IHPME)
* Fall 2022-Present: [Quantitative Methods/Health Econometrics 1 (HAD 5744)]
* Winter 2023-Present: [Health Economic Theory 1I (HAD 5760)]
* Winter 2024-Winter 2025: [Statistics in Applied Research (HAD 5772)]

### Previous Courses (Boston University, Economics) 

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
