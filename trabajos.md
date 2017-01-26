---
title: Proyectos
permalink: "/proyectos/"
descripcion: Aorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt atque
  odio non est, voluptatem dicta quaerat totam ipsam, sequi necessitatibus quae ducimus
  nesciunt dolorum deserunt, fugit porro, a eos molestiae.
layout: default
---

<section class="container" id="work">
  <div class="col-xs-10 col-xs-offset-1">
    <div class="row">
      <div class="col-xs-8">
        <h2 class="title">Proyectos & Publicaciones</h2>
        <h4>{{ page.descripcion }}</h4>
        <div class="line"></div>
      </div>
    </div>
    <div class="row">
      {% for proyecto in site.proyectos %}
      <div class="col-xs-10 col-sm-4 col-md-3 col-xs-offset-1">
        {% if proyecto.link %}
        <a href="{{ proyecto.link }}"><img class="img-responsive" src="{{ proyecto.imagen }}" alt="{{ proyecto.nombre }}"/></a>
        <h3><a href="{{ proyecto.link }}">{{ proyecto.nombre }}</a></h3>
        {% else %}
        <img class="img-responsive" src="{{ proyecto.imagen }}" alt="{{ proyecto.nombre }}"/>
        <h3>{{ proyecto.nombre }}</h3>
        {% endif %}
        {{ proyecto.content }}
      {% endfor %}
      </div>
    </div>
  </div>
</section>
