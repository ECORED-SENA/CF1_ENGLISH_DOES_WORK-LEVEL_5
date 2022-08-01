<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p
              span.r-1.fst-italic In general terms, it can be pointed out that the content of this training component is very useful, since it deals with the function of the simple present tense of verbs, their form and pronunciation, using concrete and simple examples that will allow the practice of these grammatical structures, which also facilitate descriptions of people, animals, objects or places through the use of qualifying adjectives.
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p En líneas generales, puede señalarse que el contenido de este componente formativo resulta de gran utilidad, porque se aborda la función del tiempo presente simple de los verbos, su forma y pronunciación, utilizando ejemplos concretos y sencillos que van a permitir la práctica de estas estructuras gramaticales, que además facilitan realizar descripciones de personas, animales, objetos o lugares, mediante el uso de los adjetivos calificativos.
          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
      .col-lg-5.col-8: img(src='@/assets/curso/temas/0.jpg', alt='')
    p.mb-5(data-aos='fade-right') Se invita a explorar el siguiente video introductorio que se presenta a continuación:
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    p.mb-5(data-aos='fade-right') Si desea practicar, el siguiente PDF presenta los textos del video anterior, tanto en inglés como en español.
    .row.justify-content-center
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/introduction.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Guion video Introducción
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    ocultarEsp: true,
  }),
}
</script>

<style lang="sass"></style>
