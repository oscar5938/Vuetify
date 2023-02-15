<template>
<section id="Carrusel-ca">
  <section id="Carrusel-casas">
      <img src="https://www.redstring.es/productos/imagenes/img_29406_664f8d473260be7c3d784cab358c2eeb_1.jpg" alt="grif">
      <img src="https://www.redstring.es/productos/imagenes/img_29410_c612918ee9d57152d2633a1d07406822_1.jpg" alt="raven">
      <img src="https://www.redstring.es/productos/imagenes/img_21978_ec0bb6e8978a7d6604e40b73e0698fa4_1.jpg" alt="slit">
      <img src="https://www.redstring.es/productos/imagenes/img_21983_ea9969ca3857094ee69d6b264329badb_1.jpg" alt="huffle">
  </section></section>
</template>

<script>
export default {

}
</script>

<style>
#Carrusel-casas{
    display: flex;
    width: 600px;
    height: 430px;
}

#Carrusel-casas img{
    width: 0;
    flex-grow: 1;
    object-fit: cover;
    opacity: 0.8;
    transition: .5s ease;
}

#Carrusel-casas img:hover{
    cursor: crosshair;
    width: 300px;
    opacity: 1;
    filter: contrast(120%);
}

#Carrusel-ca{
    text-align: -webkit-center;
}
</style>