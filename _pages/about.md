---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


I am a second-year Ph.D. candidate at HKU, supervised by [Lingpeng Kong](https://ikekonglp.github.io/). I obtained my bachelor's and master's degrees from the Department of Computer Science at Fudan University, advised by Prof. [Xipeng Qiu](https://xpqiu.github.io/en.html). My current research focuses on building effective long-context LLMs, including:
(1) Fully utilizing the training context.
(2) Efficient inference on over 1 million tokens.
(3) Developing better evaluation tasks for current long-context LLMs.


{% include_relative includes/pubs.md %}

{% include_relative includes/honors.md %}
