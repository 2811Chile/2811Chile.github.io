---
title: Proyectos
permalink: "/proyectos/"
descripcion: 'Realizamos proyectos que nos permitan catalizar cambios para un futuro
  sostenible. Colaboramos con diferentes organizaciones que nos permitan avanzar en
  este propósito.'
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
      </div>
    {% endfor %}
    </div>
  </div>
</section>
