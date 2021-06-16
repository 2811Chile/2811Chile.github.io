---
title: Contacto
permalink: "/contacto/"
descripcion: 'Si quieres saber más sobre lo que hacemos, quieres colaborar en algún
  proyecto o te interesa trabajar con nosotros, no dudes en contactarnos. Escríbenos
  a info@2811.cl o rellena el formulario a continuación. '
direccion1: 
telefono: 
direccion2: 
email: 
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


<script charset="utf-8" type="text/javascript" src="//js.hsforms.net/forms/shell.js"></script>
<script>
  hbspt.forms.create({
	region: "na1",
	portalId: "6925431",
	formId: "c446a2d6-aa5e-4666-85c9-e23bddcdf8e7"
});
</script>

    </div>
    <div class="row">
      <h5 class="col-xs-10">
        {{ page.direccion1 }}
      </h5>
      <h5 class="col-xs-10">
        {{ page.telefono }}
      </h5>
      <h5 class="col-xs-10">
        {{ page.direccion2 }}
      </h5>
      <h5 class="col-xs-10">
        <a href="mailto:{{ page.email }}">{{ page.email }}</a>
      </h5>

    </div>
  </div>
</section>


