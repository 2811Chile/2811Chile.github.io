---
title: Contacto
permalink: "/contacto/"
layout: default
descripcion: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloremque
  dicta ea, porro dignissimos fugit rem dolorum tempore nostrum, eum impedit, nobis
  hic esse ipsam consectetur reprehenderit soluta cumque voluptatum. Porro.
direccion: Apoquindo 12313, Las Condes. Santiago, Chile
telefono: "+56 2 123 123 12"
email: info@2811.cl
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
