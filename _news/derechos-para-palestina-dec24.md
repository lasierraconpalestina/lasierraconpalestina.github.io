---
date: 2024-12-01
title: Derechos para Palestina
layout: news
---
Desde el 29 de noviembre, Día Internacional de Solidaridad con el Pueblo Palestino, hasta el 10 de diciembre La Sierra con Palestina participa en la campaña **Derechos para Palestina** en las redes sociales.

Cada día, subimos a nuestras redes sociales una imagen o un post sobre derechos humanos. Por ejemplo, el día 30 de noviembre, compartimos publicaciones sobre el artículo 3 de la Declaración Universal de los Derechos Humanos, sobre el derecho a la vida: Toda persona tiene derecho a la vida, la libertad y la seguridad. En Gaza y Líbano, miles de personas ven este derecho violado a diario por el bloqueo y los bombardeos.

Desde La Sierra con Paletina, te animamos a seguirnos en nuestras redes sociales y compartir estas publicaciones para que la reivindicación de los derechos humanos del pueblo palestino se oigan más alto y más claro:
<p class="buttons">
{% for item in site.data.social %}
  {% unless item.name == "Email" %}
  <a class="button is-text" href="{{ item.link }}" style="text-decoration: none">
    <span class="icon">
      <i
        class="{{ item.icon.type }} {{ item.icon.name }} {{ item.icon.source }}-{{ include.icon-size }}"
        aria-hidden="true">
      </i>
    </span>
    <span>{{ item.name }}</span>
  </a>
  {% endunless %}
{% endfor %}
</p>

![Artículo 3: Derecho a la vida, libertad y seguridad](/assets/images/news/derecho_a_la_vida.jpg)
