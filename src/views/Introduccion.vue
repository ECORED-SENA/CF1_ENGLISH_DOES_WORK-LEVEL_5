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
    .tarjeta-introduccion
      .row.justify-content-center
        .col-lg-3
        .col-lg-6
          p.fw-bold.fst-italic Welcome to this training component, in which you will learn to express yourself in English using the simple present tense, as well as its function, form and pronunciation. You will also learn how to indicate differences and similarities between living beings, objects and places. With the help of examples we will go through comparative adjectives in their various degrees and superlative adjectives to be able to indicate characteristics of everything which surrounds us! Let's begin!
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
            texto=""
            :audio="require('@/assets/audios/tema1/intro.wav')"
            )  
      .tarjeta-introduccion__img.d-none.d-lg-block: img(src='@/assets/curso/temas/introduccion.png', alt='')
          

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    ocultarEsp: true,
  }),
}
</script>

<style lang="sass">
.tarjeta-introduccion
  @media (min-width: $bp-min-lg)
    margin-top: 200px
    border-radius: 0px 150px 0px 200px
    margin-left: 20px
  border-radius: 20px
  background-color: #c4d1ff
  padding: 3rem
  position: relative
  &__img
    position: absolute
    width: 400px
    bottom: 0
    left: -1%
</style>
