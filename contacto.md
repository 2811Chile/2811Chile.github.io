---
title: Contacto
permalink: "/contacto/"
descripcion: 'Si quieres saber más sobre lo que hacemos, quieres colaborar en algún
  proyecto o te interesa trabajar con nosotros, no dudes en contactarnos. '
direccion: |-
  Apoquindo 3669, piso 18,  Santiago, Chile
  Calle 81 #11-08, Bogotá, Colombia
telefono: 
email: info@2811.cl
layout: default
---

<section class="container" id="post">
  <div class="col-xs-10 col-xs-offset-1">
    <div class="row">
      <div class="col-xs-10">
        <h2 class="title">Contáctanos</h2>
        <h4>{{ page.descripcion }}</h4>
        <div class="line"></div>
        </div>
    </div>
    <div class="row">
      <h5 class="col-xs-10">
        {{ page.direccion }}
      </h5>
      <h5 class="col-xs-10">
        {{ page.telefono }}
      </h5>
      <h5 class="col-xs-10">
        <a href="mailto:{{ page.email }}">{{ page.email }}</a>
      </h5>

    </div>
  </div>
</section>
