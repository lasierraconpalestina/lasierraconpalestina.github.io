---
layout: home
title: Home
image: /assets/images/logo/circle_whitebg.png
show_news: true
---
Lorem ipsum dolor sit amet. 

#### Una sección de muestra
[Lorem ipsum dolor sit amet](https://www.lipsum.com/), consectetur adipiscing elit. Nunc dui velit, interdum ac justo sit amet, pulvinar fermentum sem. Suspendisse in sem in odio venenatis rhoncus. Vivamus accumsan tristique est at dictum. Sed ornare enim vitae vehicula blandit. Pellentesque ex elit, elementum nec sem vel, pretium feugiat dui. Nullam interdum vitae diam et ultrices. Phasellus sollicitudin erat non ligula maximus tempor eu a turpis. Cras ac magna faucibus, faucibus arcu in, varius neque. Sed molestie finibus cursus. Mauris egestas id mi ac congue. Ut placerat felis egestas est dapibus, eu rutrum dolor iaculis. 


#### Otra sección de muestra
Donec et vulputate velit. Praesent id tortor ac risus sodales bibendum sed condimentum arcu. Sed ante metus, consequat ac nulla nec, suscipit pharetra mi. Aliquam porttitor, erat at aliquet luctus, justo urna facilisis tellus, at fermentum nisl dolor eu mauris. Etiam tristique nunc nulla, a pharetra arcu iaculis a. Pellentesque posuere urna non mi malesuada, ac sodales nulla molestie. Aliquam erat volutpat. Sed dictum libero eros, at finibus felis auctor a. Ut nibh turpis, rutrum sit amet pretium id, placerat vitae libero. Etiam faucibus lacus neque, eget ultrices felis commodo nec. Proin viverra neque ut ligula commodo suscipit. 

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
