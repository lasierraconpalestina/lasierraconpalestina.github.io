---
layout: page
title: Blog
permalink: /blog
---
## Artículos recientes

{% for post in site.posts %}
  - ### [{{ post.title }}]({{ post.url }})
    {{ post.excerpt }}
{% endfor %}
