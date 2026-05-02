---
layout: page
title: Bibliografía
permalink: /bibliografia
---
{% assign bibliography = site.data.bibliografia | sort: 'year' | reverse %}
{% for item in bibliography %}
  {% include bibliography-item.html %}
{% endfor %}
