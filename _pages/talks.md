---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

* "A Zero-Inflated Negative Binomial Regression Model for Spatiotemporal Data of US Vaccine Refusal." MIDAS Network Annual Meeting. May 2021
