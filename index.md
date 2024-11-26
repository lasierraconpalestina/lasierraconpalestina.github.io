---
layout: home
title: Home
image: /assets/images/logo/circle_whitebg.png
show_news: true
---
_La Sierra con Palestina_ es una plataforma de vecinas y vecinos de la Sierra del Guadarrama creada para apoyar al pueblo palestino.

Nuestro [manifiesto](/manifiesto) establece el objeto de nuestra denucia, nuestras exigencias al gobierno del estado español y los objetivos de la plataforma.

En la sección de [acciones y eventos](/acciones) puedes encontrar algunos de nuestros eventos pasados y lo que tenemos preparado para las próximas fechas.

#### Contacto
Puedes encontrarnos en nuestras redes sociales:
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

¡Síguenos y únete!

![Elaboración de la bandera gigante de Palestina](/assets/images/flag_in_the_making.jpg)
