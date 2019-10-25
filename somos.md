---
title: Somos
permalink: "/somos/"
layout: default
---

<section id="why2811">
  <section class="container">
    <div class="row">
      <div class="col-xs-8 col-xs-offset-1">
        <h2 class="title">28 de Noviembre</h2>
        <h3>Por primera vez en la historia, el 28 de noviembre de 2015, Chile <span>sobrepasó sus límites ecológicos</span>, agotando los recursos naturales correspondientes a un año y, por lo tanto, empezando a gastar lo que, en el fondo, es la herencia para las futuras generaciones. </h3>
      </div>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-xs-8 col-xs-offset-1">
        <div class="line"></div>
        <h3>Trabajamos por un cambio social y ecológico que promueva el desarrollo regenerativo de las comunidades en armonía con el planeta.</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-10 col-xs-offset-1">
        <div class="line"></div>
        <h3>Co-creamos conocimiento, capacidades y proyectos basados en herramientas como la innovación social, emprendimiento social, inversión de impacto y el desarrollo urbano sustentable.</h3>
      </div>
    </div>
  </section>
</section>


<section class="container" id="somos">
  <div class="row">
    <div class="col-xs-offset-1 col-xs-10">
      <div class="row">
        <div class="col-xs-8">
          <h2 class="title">Somos</h2>
          <h3>Equipo</h3>
        </div>
      </div>
      <div class="row">
        {% for persona in site.equipo %}
        <div class="col-xs-6 col-sm-4 col-md-3">
          <img class="img-responsive" src="{{ persona.foto }}" alt="{{ persona.name }}"/>
          <h4>{{ persona.nombre }}</h4>
          <p>{{ persona.cargo }}</p>
          <p><a href="mailto:{{ persona.email }}"> {{ persona.email }} </a></p>
        </div>
        {% endfor %}
      </div>
      <div class="row">
        <div class="col-xs-8">
           <p style="margin:30px 0px;">
            <h4>El equipo de 2811 ha trabajado tres años en la promoción de la innovación social y el desarrollo sostenible desde espacios académicos, trabajando mano a mano con fundaciones, empresas, organizaciones de la sociedad civil y otras universidades en América Latina. Hoy trabajamos en y desde diferentes países incluyendo Chile, Perú, Colombia, México, Brasil, Estados Unidos y Alemania. 
          </p>
<div class="line"></div>
        </div>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col-xs-offset-1 col-xs-10">
      <div class="row">
        <div class="col-xs-8">
        </div>
      </div>
      <div class="row">
        {% for persona in site.colaboradores %}
        <div class="col-xs-4 col-sm-3 col-md-3">
          <h4>{{ persona.nombre }}</h4>
          <p>{{ persona.cargo }}</p>
          <p><a href="mailto:{{ persona.email }}"> {{ persona.email }} </a></p>
        </div>
        {% endfor %}
      </div>
    </div>
  </div>
</section>

<section class="container" id="alianzas">
  <div class="col-xs-10 col-xs-offset-1">
    <div class="row">
      <div class="col-xs-8">
        <h2 class="title">Alianzas</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-6 col-sm-4 col-md-3 col-xs-offset-1">
        <a href=""><img class="img-responsive" src="/assets/images/logos/ashoka.png" /></a>
      </div>
      <div class="col-xs-6 col-sm-4 col-md-3">
        <a href=""><img class="img-responsive" src="/assets/images/logos/corfo.png" /></a>
      </div>
      <div class="col-xs-6 col-sm-4 col-md-3">
        <a href=""><img class="img-responsive" src="/assets/images/logos/utalca.png" /></a>
      </div>
    </div>
  </div>
</section>
