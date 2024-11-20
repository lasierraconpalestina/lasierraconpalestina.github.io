---
layout: page
title: Acciones y eventos
permalink: /acciones
show_videos: false
---
{% assign today = 'now' | date: "%Y-%m-%d" %}
{% assign future_actions = "" | split: "," %}
{% assign past_actions = "" | split: "," %}

{% for action in site.data.actions %}
  {% assign action_date = action.date | date: "%Y-%m-%d" %}
  {% if action_date > today %}
      {% assign future_actions = future_actions | push: action %}
  {% else %}
      {% assign past_actions = past_actions | push: action %}
  {% endif %}
{% endfor %}

## Próximamente
{% assign actions = future_actions | sort: 'date' | reverse %}
{% if actions.size == 0 %}
Por el momento, no hay acciones planificadas para las próximas fechas.
{% else %}
  {% for action in actions %}
  {% include action.html %}
  {% endfor %}
{% endif %}

## En el pasado
{% assign actions = past_actions | sort: 'date' | reverse %}
{% for action in actions %}
  {% include action.html %}
{% endfor %}
