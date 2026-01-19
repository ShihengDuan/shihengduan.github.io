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

I am currently a postdoctoral researcher at Lawrence Livermore National Laboratory. My research focuses on the hydroclimate system, climate change impacts, detection and attribution (D&A), and extreme events. I use machine learning and deep learning to study climate, as well as simulations from climate models. My broader goal is to integrate AI and climate science to improve prediction, risk assessment, and climate adaptation strategies. 
