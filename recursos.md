---
title: Recursos
permalink: "/blog/"
descripcion: 'Instancias para reflexionar sobre los efectos de nuestras acciones en
  el futuro de la sociedad y nuestro planeta. '
layout: default
---

<section class="container" id="blog">
  <div class="col-xs-10 col-xs-offset-1">
    <div class="row">
      <div class="col-xs-12 col-sm-3">
        <h2 class="title">Recursos</h2>
        <h4>{{ page.descripcion }}</h4>
      </div>
      {% for post in site.posts %}
      <div class="col-xs-10 col-sm-3">
        <a href="{{site.baseurl}}{{post.url}}"><img class="img-responsive" src="{{site.baseurl}}{{ post.portada }}" /></a>
        <h3><a href="{{site.baseurl}}{{post.url}}">{{ post.nombre }}</a></h3>
        {{ post.excerpt | strip_html }}
      </div>
      {% endfor %}
    </div>
  </div>
</section>
