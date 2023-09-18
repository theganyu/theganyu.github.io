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


{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/research.md %}

{% include_relative includes/awards.md %}

{% include_relative includes/educations.md %}

{% include_relative includes/invited_talks.md %}

{% %}

<center>
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=-4NCtYeRigQS9DpeddzMGvyE0COf2qYlcbrEAfCB3_o&cl=ffffff&w=a"></script>

<br> &copy; Gan Yu | Last updated: Sep, 2023
</center>