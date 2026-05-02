---
layout: page
title: Bibliografía
permalink: /bibliografia
---
{% assign bibliography = site.data.bibliography | sort: 'year' | reverse %}
{% for item in site.data.bibliography %}
  {% include bibliography-item.html %}
{% endfor %}
