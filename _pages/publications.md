---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Journal Articles
====== 
* **Bokgyeong Kang** and Taeyoung Park. (2019). "Efficient and flexible model-based clustering of jumps in diffusion processes." Journal of the Korean Statistical Society. 48(3)
