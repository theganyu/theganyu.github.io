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

{% include_relative includes/education.md %}

{% include_relative includes/awards.md %}

{% include_relative includes/invited_talks.md %}

<center>

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w= 250&t=n&d=YaCEqTabkGhXbc9_VZFvuWg-a-Mfu1nj3xCZZdWZ5SY'></script>
<br> &copy; Gan Yu | Last updated: March, 2024
</center>

<!---  
    <a href="https://www.easycounter.com/">
    <img src="https://www.easycounter.com/counter.php?davidyugan"
    border="0" alt="Website Hit Counters"></a>
    unique visitors.  
 -->
