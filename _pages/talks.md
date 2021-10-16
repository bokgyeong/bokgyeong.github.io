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

* "A Zero-Inflated Negative Binomial Regression Model for Spatiotemporal Data of US Vaccine Refusal." 2021 MIDAS Network Annual Meeting
* "Diagnostics for Monte Carlo algorithms for models with intractable normalizing functions." 2021 World Meeting of the International Society for Bayesian Analysis
* "Diagnostics for Monte Carlo algorithms for models with intractable normalizing functions." 2021 Joint Statistical Meetings
