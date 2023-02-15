<template>
  <section id="Carrusel-ca">
    <section id="Carrusel-casas">
      <img
        src="https://www.redstring.es/productos/imagenes/img_29406_664f8d473260be7c3d784cab358c2eeb_1.jpg"
        alt="grif"
      />
      <img
        src="https://www.redstring.es/productos/imagenes/img_29410_c612918ee9d57152d2633a1d07406822_1.jpg"
        alt="raven"
      />
      <img
        src="https://www.redstring.es/productos/imagenes/img_21978_ec0bb6e8978a7d6604e40b73e0698fa4_1.jpg"
        alt="slit"
      />
      <img
        src="https://www.redstring.es/productos/imagenes/img_21983_ea9969ca3857094ee69d6b264329badb_1.jpg"
        alt="huffle"
      />
    </section>
    <h2>¿Qué argumento tiene el juego</h2>
    <p>Aún está envuelto en un significativo misterio, pero sí se sabe que aunque el título no se base en ninguna novela de 'Harry Potter' sí que partirá del mundo y el lore creado por J.K. Rowling (que no está implicada en el apartado creativo del juego). La ambientación es a finales del siglo XIX y el protagonista será un aprendiz de mago como lo era Harry Potter. La diferencia: nuestro héroe o heroína tendrá una habilidad especial para aprender y ejecutar Magia Antigua. Avalanche afirma que "sólo tú puedes decidir si protegerás este secreto por el bien de todos, o cederás a la tentación de una magia más siniestra".</p>
  </section>
</template>

<script>
export default {};
</script>

<style>
#Carrusel-casas {
  display: flex;
  width: 600px;
  height: 400px;
  margin-bottom: 50px;
}

#Carrusel-casas img {
  width: 0;
  flex-grow: 1;
  object-fit: cover;
  opacity: 0.8;
  transition: 0.5s ease;
}

#Carrusel-casas img:hover {
  cursor: pointer;
  width: 300px;
  opacity: 1;
  filter: contrast(120%);
}

#Carrusel-ca {
  text-align: -webkit-center;
}

#Carrusel-ca p{
    width: 80%;
    margin:30px 0;
}
</style>