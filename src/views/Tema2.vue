<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Qualifying adjectives (Adjetivos calificativos)
    .contenedor-traductor.mb-5
      .contenedor-traductor__eng
        p
          span.r-1.fst-italic Qualifying adjectives are variable words that indicate characteristics of people, animals and things. In general, they are used to describe nouns.
            br
            |So, the adjective is a part of the sentence that qualifies the noun, providing additional information or complementing its meaning. Also, these adjectives have no gender and no plural.

            br
            br
            |In this order of ideas, adjectives determine names or nouns by specifying or highlighting their characteristics. In fact, several adjectives can be used together. 
      .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
        p Los adjetivos calificativos son palabras variables que indican características de las personas, los animales y las cosas. En líneas generales, se utilizan para describir los sustantivos. De manera que el adjetivo es una parte de la oración que califica al sustantivo, aportando información adicional o complementando su significado. Además, estos adjetivos no tienen género ni plural.
          br
          br
          |En este orden de ideas, los adjetivos determinan los nombres o sustantivos al especificar o resaltar sus características. De hecho, pueden usarse varios adjetivos juntos.
      a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal For example: 
      | / Por ejemplo: 
    .row.justify-content-center.g-2
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/33.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.mb-0
                span.text-white.fst-italic The big blue car.

                br
                |  El carro azul grande.
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/34.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.mb-0
                span.text-white.fst-italic A ripe red apple
                br
                | Una manzana roja madura.
      p.mb-5(data-aos='fade-right') 
        span.r-4.fst-italic.fw-normal  They are also widely used for general or abstract descriptions.
        br
        br
        |También se utilizan ampliamente para realizar descripciones generales o abstractas. 
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal For example: 
      | / Por ejemplo: 
    .row.justify-content-center.g-2
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/35.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.mb-0
                span.text-white.fst-italic The difficult job.

                br
                |  El trabajo difícil.
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/36.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.mb-0
                span.text-white.fst-italic A sad situation.

                br
                |Una situación triste.
    p.mb-5(data-aos='fade-right') 
      span.r-4.fw-normal.fst-italic From a semantic perspective, an adjective can state various characteristics, such as: qualities (beautiful, tall), states (single, sad, happy), attitudes (active, idealistic), possibilities (probable, incredible), origin or nationality (Mexican, Argentine), among others. Some examples are:
      br
      br
      |Desde una perspectiva semántica, un adjetivo puede enunciar diversas características, como: cualidades (bello, alto), estados (soltero, triste, feliz), actitudes (activo, idealista), posibilidades (probable, increíble), procedencia o nacionalidad (mexicano, argentino), entre otras. Algunos ejemplos son:
    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="<em>Qualities</em> / Cualidades" :icono="require('@/assets/curso/temas/38.svg')")
        .row.justify-content-center.mb-5
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/38.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="This is a beautiful baby."
              :audio="require('@/assets/audios/tema1/17.mp3')"
              )
            p.text-center.mt-3
              span.f-2.p-2 Es un <b>lindo</b> bebe .  
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/39.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Grace is very smart."
              :audio="require('@/assets/audios/tema1/18.mp3')"
              )
            p.text-center.mt-3
              span.f-2.p-2 Grace es muy <b>inteligente</b> .
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/40.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Jimmy is a strong boy."
              :audio="require('@/assets/audios/tema1/19.mp3')"
              )
            p.text-center.mt-3
              span.f-2.p-2 Jimmy es un chico <b>fuerte</b> . 
      .py-4.py-md-5(titulo="<em>States</em> / Estados" :icono="require('@/assets/curso/temas/53.svg')")
        .row.justify-content-center.mb-5
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/41.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Molly is a happy girl."
              :audio="require('@/assets/audios/tema1/20.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Molly es una chica <b>feliz</b> .
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/42.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="George feels furious."
              :audio="require('@/assets/audios/tema1/21.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 George está <b>furioso</b> .
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/43.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Lucas has a calm temperament."
              :audio="require('@/assets/audios/tema1/22.mp3')"
              ) 
            p.text-center.mt-3
              span.f-2.p-2 Lucas tiene un temperamento <b>tranquilo</b> .
      .py-4.py-md-5(titulo="<em>Attitudes</em> / Actitudes" :icono="require('@/assets/curso/temas/54.svg')")
        .row.justify-content-center.mb-5
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/44.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Marge is sympathetic with her children."
              :audio="require('@/assets/audios/tema1/tema_2_pstañas_b_sympathetic_CF1.wav')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Marge es <b>comprensiva</b> con sus hijos.
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/45.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Peter is an enthusiastic human rights activist."
              :audio="require('@/assets/audios/tema1/24.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Peter es un <b>entusiasta </b> activista por los derechos humanos. 
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/46.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="The teacher is very patient with her students."
              :audio="require('@/assets/audios/tema1/tema_2_pstañas_b_patient_CF1.wav')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 La maestra es muy <b>paciente</b> con sus estudiantes.
      .py-4.py-md-5(titulo="<em>Possibilities</em> / Posibilidades" :icono="require('@/assets/curso/temas/55.svg')")
        .row.justify-content-center.mb-5
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/47.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="It’s likely to rain today."
              :audio="require('@/assets/audios/tema1/26.mp3')"
              ) 
            p.text-center.mt-3
              span.f-2.p-2 Es <b>probable</b> que llueva hoy.  
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/48.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="The chances of winning are slim."
              :audio="require('@/assets/audios/tema1/27.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Las oportunidades de ganar son <b>escasas</b> .
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/49.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="It’s incredible that you’re here. "
              :audio="require('@/assets/audios/tema1/28.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Es <b>increible </b> que estés aquí.
      .py-4.py-md-5(titulo="<em>Nationality</em> / Nacionalidad" :icono="require('@/assets/curso/temas/56.svg')")
        .row.justify-content-center.mb-5
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/50.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Nicole is French."
              :audio="require('@/assets/audios/tema1/29.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Nicole es <b>francesa</b> .
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/51.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Paula is a Brazilian athlete."
              :audio="require('@/assets/audios/tema1/30.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Paula es una <b>atleta</b> brasileña.
          .col-lg-3.col-4
            .card-audio-bg.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/52.jpg')})`}")
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Pierina is the Italian candidate."
              :audio="require('@/assets/audios/tema1/31.mp3')"
              )  
            p.text-center.mt-3
              span.f-2.p-2 Pierina es la candidata <b>italiana</b> .
    p.mb-5(data-aos='fade-right') Para poder establecer una comparación en el idioma inglés, se utilizan diversas cualidades, que se pueden expresar a través de tres diferentes grados de los adjetivos, como se verá a continuación:
    h3 <em>Degrees of the adjective</em> / Grados del adjetivo.
    p.mb-5(data-aos='fade-right') 
      span.r-4.fst-italic.fw-normal It should be noted that adjectives, depending on their function, are presented in three different forms or degrees: 
      span.r-1.fst-italic a positive degree, a comparative degree, and a superlative degree.
      br
      br
      |Se debe señalar que los adjetivos, según su función, se presentan en tres formas o grados distintos: grado positivo, grado comparativo y grado superlativo.
      br
      br
      |Ahora, observe un video para entender mejor los diferentes grados de los adjetivos:
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/f5cwrrqnPEM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    #t_2_1.titulo-segundo.color-primario(data-aos='fade-right')
      h2 2.1 <em>Comparative adjectives</em> (Adjetivos comparativos)
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-3: img(src='@/assets/curso/temas/57.png', alt='')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p
              span.r-1.fst-italic They are words used to express a comparison of qualities between two elements. A comparative element is inserted between the two elements or statements and a quantifier can also be included to intensify that assessment.
                br
                br
                |It should be noted that when no comparison is made, the adjective is said to be in a positive degree. In addition to this, there are several degrees in which the comparison between these two elements can occur: the comparative degree of equality, inferiority and superiority.
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p Son palabras que se utilizan para expresar una comparación de cualidades entre dos elementos. Entre los dos elementos o enunciados, se inserta un elemento comparativo y, además, se puede incluir un cuantificador, que permite intensificar esa valoración.
              br
              br
              |Cabe destacar que cuando no se realiza ninguna comparación se dice que el adjetivo está en grado positivo. Aunado a ello, existen varios grados en que puede darse la comparación entre esos dos elementos: el grado comparativo de igualdad, de inferioridad y de superioridad.
          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal For example: 
      | / Por ejemplo:
    .row.justify-content-center.mb-lg-3.mb-0
      .col-lg-4.mb-lg-0.mb-3.h-100
        img(src='@/assets/curso/temas/58.png', alt='')
        .audio-red.tarjeta.rounded-0(style='background-color: #ffdfe0').p-4
          p
            span.r-4.fst-italic Is more beautiful than
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Mary’s house is more beautiful than Betty’s house"
              :audio="require('@/assets/audios/tema1/32.mp3')"
              )  
          p.ms-4 La casa de Mary es más bonita que la casa de Betty.
      .col-lg-4.mb-lg-0.mb-3
        img(src='@/assets/curso/temas/59.png', alt='')
        .audio-red.tarjeta.rounded-0(style='background-color: #d5d6f0').p-4
          p
            span.r-4.fst-italic Is less attentive than 
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Felix is less attentive than Joseph."
              :audio="require('@/assets/audios/tema1/33.mp3')"
              )  
          p.ms-4 Félix es menos atento que Joseph.
      .col-lg-4.mb-lg-0.mb-3
        img(src='@/assets/curso/temas/60.png', alt='')
        .audio-red.tarjeta.rounded-0(style='background-color: #fff7da').p-4
          p
            span.r-4.fst-italic Is as productive as
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="This company is as productive as that one"
              :audio="require('@/assets/audios/tema1/tema_2.1_infografia_interactiva_productive_CF1.wav')"
              )  
          p.ms-4 Esta empresa es tan productiva como aquella. 
    .row.justify-content-center.mb-5
      .col-lg-4.mb-lg-0.mb-3
        img(src='@/assets/curso/temas/61.png', alt='')
        .audio-red.tarjeta.rounded-0(style='background-color: #ffdfe0').p-4
          p
            span.r-4.fst-italic Is bigger than
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="This bull is bigger than this cow."
              :audio="require('@/assets/audios/tema1/35.mp3')"
              )  
          p.ms-4 Este toro es más grande que esta vaca.
      .col-lg-4.mb-lg-0.mb-3
        img(src='@/assets/curso/temas/62.png', alt='')
        .audio-red.tarjeta.rounded-0(style='background-color: #d5d6f0').p-4
          p
            span.r-4.fst-italic is less heavy than
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="That backpack is less heavy than yours. "
              :audio="require('@/assets/audios/tema1/tema_2.1_infografia_interactiva_that_backpack_CF1.wav')"
              )  
          p.ms-4 Ese morral está menos pesado que el tuyo.
    h3 <em>Comparative adjectives of equality.</em> / Adjetivos comparativos de igualdad.
    p.mb-5(data-aos='fade-right')
      span.r-4.fw-normal.fst-italic Sometimes, two elements, be they objects, people, animals or places, are on an equal footing when compared to each other. Therefore, the level or degree of the comparative adjective is equality when describing them. It is important to note that a comparative adjective of equality generally has one of the following structures:
      br
      br
      |En ocasiones, dos elementos, ya sean objetos, personas, animales o lugares, se encuentran en igualdad de condiciones cuando se comparan entre sí. Por ello, el nivel o grado del adjetivo comparativo es de igualdad. Al describirlos, es importante señalar que un adjetivo comparativo de igualdad generalmente tiene alguna de las siguientes estructuras:
    .tarjeta.position-relative.p-5(style='background-color: #fff7da').mb-5
      .position-absolute(style='bottom: 0; left: 0; width: 230px;')
        img.d-none.d-lg-block(src='@/assets/curso/temas/66.png', alt='')
      .row.justify-content-center.mb-5
        .col-lg-2
        .col-lg-10
          img.mb-4(src='@/assets/curso/temas/63.svg', alt='')
          .tarjeta-audio-botton
            div.flex-grow-1(style='background-color: #c4d1ff').d-flex.align-items-center.justify-content-center.px-3
              Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/tema_2.1_comparative_equiality_karen_cf1.wav')")
            div.d-flex.flex-grow-1.p-4.w-100.justify-content-center.flex-wrap(style='background-color: #ffe891')
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/64.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-1.fst-italic Karen is as tall as her sister.
                  br
                  | Karen es tan alta como su hermana.
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/65.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-1.fst-italic You are as happy as James. 
                  br
                  | Tú estás tan alegre como James.
    .tarjeta.position-relative.p-5(style='background-color: #e1e8ff').mb-5
      .position-absolute(style='bottom: 0; right: -5%; width: 230px;')
        img.d-none.d-lg-block(src='@/assets/curso/temas/67.png', alt='')
      .row.justify-content-center.mb-5
        .col-lg-11
          img.mb-4(src='@/assets/curso/temas/68.svg', alt='')
          p(data-aos='fade-right') 
            span.r-1.fst-italic For the as much… as structure: 
            | / Para la estructura as much… as:
          .tarjeta-audio-botton
            div.flex-grow-1(style='background-color: #ffe891').d-flex.align-items-center.justify-content-center.px-3
              Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/39.mp3')")
            div.d-flex.flex-grow-1.p-4.w-100.justify-content-center.flex-wrap(style='background-color: #a6bbff')
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/69.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-4.fst-italic Give me as much money as Ricky has. 
                  br
                  | Dame <b>tanto</b> dinero <b>como</b> Ricky tiene.
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/70.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-4.fst-italic Add as much sugar as you want. 
                  br
                  | Añade <b>tanta</b> azúcar <b>como</b> quieras.
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/71.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-4.fst-italic Take as much water as it’s needed.
                  br
                  | Toma <b>tanta</b> agua <b>como</b> sea necesario.
        .col-lg-1
    .tarjeta.position-relative.p-5(style='background-color: #fff7da').mb-5
      .position-absolute(style='bottom: 0; left: 0; width: 230px;')
        img.d-none.d-lg-block(src='@/assets/curso/temas/73.png', alt='')
      .row.justify-content-center.mb-5
        .col-lg-2
        .col-lg-10
          img.mb-4(src='@/assets/curso/temas/72.svg', alt='')
          .tarjeta-audio-botton
            div.flex-grow-1(style='background-color: #c4d1ff').d-flex.align-items-center.justify-content-center.px-3
              Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/42.mp3')")
            div.d-flex.flex-grow-1.p-4.w-100.justify-content-center.flex-wrap(style='background-color: #ffe891')
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/74.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-1.fst-italic Take as many notebooks as <br>your brother.
                  br
                  | Toma tantos cuadernos como<br> tu hermano.
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/75.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-1.fst-italic He can use as many excuses<br> as he wants. 
                  br
                  | Él puede usar tantas excusas<br> como quiera.
              .d-flex.align-items-center.flex-wrap.mb-lg-0.mb-3.m-2
                img(src='@/assets/curso/temas/76.svg', alt='' style='width: 54px').me-4
                p.mb-0
                  span.r-1.fst-italic Please, buy as many shirts as you need.
                  br
                  | Por favor, compra tantas camisas como necesites.
    h3 <em>Comparative adjectives of inferiority.</em> / Adjetivos comparativos de inferioridad.
    p
      span.r-4.fst-italic.fw-normal When comparing two elements, whether they are objects, people, animals or places, it may happen that one of them is at a lower level or degree with respect to the characteristic that is evaluated between them. Therefore, the level or degree of the comparative adjective is one of inferiority. In general terms, a comparative adjective of inferiority has the following structure:
      br
      br
      |Al comparar dos elementos, ya sean objetos, personas, animales o lugares, puede ocurrir que uno de ellos se encuentre en un nivel o grado inferior respecto a la característica que se evalúa entre ellos. Por ello, el nivel o grado del adjetivo comparativo es de inferioridad. En líneas generales, un adjetivo comparativo de inferioridad tiene la siguiente estructura:
    .tarjeta-bg.p-5.mb-5
      .row.justify-content-center.mb-5
        .col-lg-6
          .tarjeta.bg-white.p-5.d-flex.flex-column
            img(src='@/assets/curso/temas/78.svg', alt='' style='width: 335px;').mb-3.m-auto
            p.text-center
              span.r-1.fst-italic The glass number 2 is less full than glass number 1.
              br
              br
              | El vaso número 2 está menos lleno que el vaso número 1.
        .col-lg-6
          .tarjeta.bg-white.p-5.d-flex.flex-column
            img(src='@/assets/curso/temas/79.svg', alt='' style='width: 335px;').mb-3.m-auto
            p.text-center
              span.r-1.fst-italic Richard is less tall than his friend Paula.
              br
              br
              | Richard es menos alto que su amiga Paula.
      .row.justify-content-center.mb-5
        .col-lg-8
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
          texto=""
          :audio="require('@/assets/audios/tema1/2.1_comparative_example_glass_cf1.wav')"
          ) 
    h3 <em>Comparative adjectives of superiority.</em> / Adjetivos comparativos de superioridad.
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal Regarding the comparison of two elements, whether they are objects, people, animals or places, it may happen that one of them is at a higher level or degree with respect to the characteristic that is evaluated between them. In this case, the level or degree of the comparative adjective is one of superiority. In this regard, it is argued that a comparative adjective of superiority has the following structure:
      br
      br
      |En cuanto a la comparación de dos elementos, ya sean objetos, personas, animales o lugares, puede ocurrir que uno de ellos se encuentre en un nivel o grado superior respecto a la característica que se evalúa entre ellos. En este caso, el nivel o grado del adjetivo comparativo es de superioridad. A este respecto, se plantea que un adjetivo comparativo de superioridad tiene la siguiente estructura:
    .tarjeta-bg.p-5.mb-5
      img(src='@/assets/curso/temas/80.svg', alt='' ).mb-4.m-auto
      p.fw-bold.text-center.mb-4 A continuación, puede escuchar el audio con los ejemplos utilizados en adjetivos comparativos de superioridad:
      .row.justify-content-center
        .col-lg-4
          .tarjeta.bg-white.p-3.h-100.audio-red
            img(src='@/assets/curso/temas/81.svg', alt='' ).me-4.mb-3
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Pierre is more efficient than Mary in the office."
              :audio="require('@/assets/audios/tema1/2.1_comparative_superiority_piere_cf1.wav')"
              ) 
            p Pierre es más eficiente que Mary en la oficina.
        .col-lg-4
          .tarjeta.bg-white.p-3.h-100.audio-red
            img(src='@/assets/curso/temas/82.svg', alt='' ).me-4.mb-3
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Silvia is more organized than Billy at school."
              :audio="require('@/assets/audios/tema1/2.1_comparative_superiority_silvia_cf1.wav')"
              ) 
            p Silvia es más ordenada que Billy en la escuela.
        .col-lg-4
          .tarjeta.bg-white.p-3.h-100.audio-red
            img(src='@/assets/curso/temas/83.svg', alt='' ).me-4.mb-3
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto="Caroline is more interesting than Betty."
              :audio="require('@/assets/audios/tema1/2.1_comparative_superiority_caroline_cf1.wav')"
              ) 
            p Caroline es más interesante que Betty.
    .contenedor-franja.margin-n.mb-5
      .franja1(style= 'height: 70%')
      .row.justify-content-center.align-items-end.g-0
        .col-lg-3.d-none.d-lg-block: img(data-aos='zoom-in-up')(src='@/assets/curso/temas/29.png', alt='')
        .col-lg-9
          .contenido.px-5
            .row.justify-content-center.mb-3
              .col-lg-2.col-6.mb-lg-0.mb-3
                img(src='@/assets/curso/temas/warning.svg', alt='' style='width:85px')
              .col-lg-10
                h4.mb-5.text-lg-white
                  span.r-1.fst-italic Warning #2
                  br
                  | Advertencia #2
            p.mb-5 
              span.r-3.fw-normal.fst-italic In case the qualifier used is a single syllable, the word “more” is omitted, the last consonant is repeated and “er” is added at the end.
              br
              br
              span.text-white En caso de que el calificativo utilizado sea de una sola sílaba, se omite la palabra 
                span.r-3.fst-italic “more” 
                | se repite la última consonante y se le añade 
                span.r-3.fst-italic “er” 
                | al final.
            .row.justify-content-center.mb-5
              .col-lg-3
                TarjetaAudio.color-primario.bg-white.mb-3(
                texto="thin → thinner"
                :audio="require('@/assets/audios/tema1/50.mp3')"
                ) 
                p.text-white delgado → más delgado
              .col-lg-3
                TarjetaAudio.color-primario.bg-white.mb-3(
                texto="fat → fatter"
                :audio="require('@/assets/audios/tema1/51.mp3')"
                ) 
                p.text-white gordo → más gordo
              .col-lg-3
                TarjetaAudio.color-primario.bg-white.mb-3(
                texto="big → bigger"
                :audio="require('@/assets/audios/tema1/2.1_warning2_big_cf1.wav')"
                ) 
                p.text-white grande → más grande
              .col-lg-3
                TarjetaAudio.color-primario.bg-white.mb-3(
                texto="small → smaller"
                :audio="require('@/assets/audios/tema1/53.mp3')"
                ) 
                p.text-white pequeño → más pequeño
    p.mb-5(data-aos='fade-right') Observe algunos ejemplos con los adjetivos comparativos de superioridad:
    .row.justify-content-center.mb-3
      .col-lg-6
        .tarjeta.color-primario.p-3.px-0
          h3.mb-0.text-center.text-white.fst-italic Comparative adjectives of superiority
    br
    br
    br
    .row.justify-content-center.mb-5.g-2
      .col-lg-4
        .tarjeta-icon-up.p-4.h-100(style='background-color: #c4d1ff ; ' ) 
          .tarjeta-icon-up__img: img(src='@/assets/curso/temas/84.svg', alt='' style='width: 276px' ).m-auto.mb-0
          p.text-center.fw-bold.fst-italic The glass number 1 is 
            span.f-3 fuller than  
            | glass number 2.
      .col-lg-4
        .tarjeta-icon-up.p-4.h-100(style='background-color: #fff0b5 ; ' ) 
          .tarjeta-icon-up__img: img(src='@/assets/curso/temas/85.svg', alt='' style='height: 163px' ).m-auto.mb-0
          p.text-center.fw-bold.fst-italic Joan is 
            span.f-3 thinner than 
            | his friend Jimmy.
      .col-lg-4
        .tarjeta-icon-up.p-4.h-100(style='background-color: #ffbfc1 ; ' ) 
          .tarjeta-icon-up__img: img(src='@/assets/curso/temas/86.svg', alt='' style='height: 163px' ).m-auto.mb-0
          p.text-center.fw-bold.fst-italic A shark is 
            span.f-3 more 
            | dangerous 
            span.f-3 than 
            | a penguin.
    Separador
    #t_2_2.titulo-segundo.color-primario(data-aos='fade-right')
      h2 2.2 <em>Superlative adjectives</em> (Adjetivos superlativos)
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal Superlative adjectives are those that serve to indicate the description of an object, person, animal or place that is located at the upper or lower end of a certain quality. For example:
      br
      br
      |Los adjetivos superlativos son aquellos que sirven para indicar la descripción de un objeto, persona, animal o lugar que se ubica en el extremo superior o inferior de una determinada cualidad. Por ejemplo: 
    .row.justify-content-center.mb-5
      .col-lg-3.col-sm-6
        .card-audio-bg2.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/87.jpg')})`}")
          .tarjeta.bg-white.p-4
            .d-flex.justify-content-center 
              Audio.d-inline-block.color-primario.m-3(:audio="require('@/assets/audios/tema1/2.2_super_adjectives_tarjeta_avatar_woman_cf1.wav')")
            p.text-center
              span.r-1.fst-italic The  
                span.r-2.fst-italic most beautiful 
                | woman in the universe.
              br
              | La mujer más bonita del universo.
      .col-lg-3.col-sm-6
        .card-audio-bg2.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/88.jpg')})`}")
          .tarjeta.bg-white.p-4
            .d-flex.justify-content-center 
              Audio.d-inline-block.color-primario.m-3(:audio="require('@/assets/audios/tema1/2.2_super_adjectives_tarjeta_avatar_student_cf1.wav')")
            p.text-center
              span.r-1.fst-italic The 
                span.r-2.fst-italic smartest 
                | student in school.
              br
              | El estudiante más inteligente de la escuela.
      .col-lg-3.col-sm-6
        .card-audio-bg2.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/89.jpg')})`}")
          .tarjeta.bg-white.p-4
            .d-flex.justify-content-center 
              Audio.d-inline-block.color-primario.m-3(:audio="require('@/assets/audios/tema1/2.2_super_adjectives_tarjeta_avatar_house_cf1.wav')")
            p.text-center
              span.r-1.fst-italic The 
                span.r-2.fst-italic largest 
                | house in the neighborhood.
              br
              | La casa más grande del vecindario.
      .col-lg-3.col-sm-6
        .card-audio-bg2.d-flex.align-items-end.justify-content-center.p-2(:style="{'background-image': `url(${require('@/assets/curso/temas/90.jpg')})`}")
          .tarjeta.bg-white.p-4
            .d-flex.justify-content-center 
              Audio.d-inline-block.color-primario.m-3(:audio="require('@/assets/audios/tema1/2.2_super_adjectives_tarjeta_avatar_kitten_cf1.wav')")
            p.text-center
              span.r-1.fst-italic The 
                span.r-2.fst-italic cutest 
                | kitten in the litter.
              br
              | El gatito más tierno de la camada.
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-3: img(src='@/assets/curso/temas/91.png', alt='')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p
              span.r-1.fst-italic It is very important to note that superlative adjectives are always preceded by the word (definite article) “the” and add the ending “est”.
                br
                |In the same way, certain rules must be applied that are of great importance so that the description that is wanted to be made is done in an adequate and correct way.
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp2}")
            p Es muy importante acotar que los adjetivos superlativos siempre van precedidos por la palabra (artículo determinado) 
              span.r-1.fst-italic “the” 
              | y añaden la terminación 
              span.r-1.fst-italic “est”.
              br
              |De igual manera, se deben aplicar ciertas reglas que resultan de gran importancia para que la descripción que se quiere realizar se haga en forma adecuada y correcta. 
          a.boton-traduccion(@click='ocultarEsp2 = !ocultarEsp2') Ver traducción
    p.mb-5(data-aos='fade-right') Algunas reglas a seguir con los adjetivos y superlativos son:
    SlyderF.mb-5(columnas="col-lg-6 col-xl-12")
      .tarjeta(style='background-color: #ecf1ff')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/92.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have only one syllable
                br
                | Para los adjetivos que  tienen una sola sílaba
            p.mb-4 When an adjective consists of only one syllable, to form the comparative degree of superiority,  <b>“er”</b> is added at the end.
            p.fw-bold
              span.f-3.p-2.pe-5 Fast / Rápido → Fast 
                span.r-1 + er 
                | = Faster / más rápido.
            .row.justify-content-center.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/93.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic He has a very fast car.
                    br
                    | Él tiene un carro muy rápido.
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/94.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic His car is faster than yours.
                    br
                    | Su carro es más rápido que el tuyo.
            p.fw-bold
              span.f-3.p-2.pe-5 Old / Viejo → Old 
                span.r-1 + er 
                | = Older / más viejo.
            .row.justify-content-center.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/95.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Mario is an old man.
                    br
                    | Mario es un hombre viejo.
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/96.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Mario is older than his brother. 
                    br
                    | Mario es más viejo que su hermano.
            p.fw-bold
              span.f-3.p-2.pe-5 Calm / Tranquilo → Calm 
                span.r-1 + er 
                | = Calmer / más tranquilo.
            .row.justify-content-center.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/97.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Susy is calm at home.
                    br
                    | Susy está tranquila en su casa.
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/98.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Susy is calmer with her husband.
                    br
                    | Susy está más tranquila con su esposo.
            p.fw-bold
              span.f-3.p-2.pe-5 Bright / Brillante  →  Bright
                span.r-1 + er 
                | = Brighter / más brillante.
            .row.justify-content-center.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/99.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This room is bright.
                    br
                    | Esta habitación es brillante.
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/100.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Your room is brighter than mine.
                    br
                    | Tu habitación es más brillante que la mía.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/58.mp3')"
              ) 
      .tarjeta(style='background-color: #ecf1ff')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/92.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have only one syllable
                br
                | Para los adjetivos que  tienen una sola sílaba
            p.mb-4 To form the superlative degree when the adjective consists of one syllable, “est” is added at the end.
            p.fw-bold
              span.f-3.p-2.pe-5 Fast / Rápido  →  Fast
                span.r-1 + est
                | = Fastest / el más rápido.
            .row.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/101.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Robert is the fastest in the team
                    br
                    | Robert es el más rápido del equipo.
            p.fw-bold
              span.f-3.p-2.pe-5 Old / Viejo   →   Old 
                span.r-1  + est
                | = Oldest / el más viejo.
            .row.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/102.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Charles is the oldest of my friends.
                    br
                    | Charles es el más viejo de mis amigos.
            p.fw-bold
              span.f-3.p-2.pe-5 Calm / Tranquilo  →  Calm
                span.r-1 + est
                | = Calmest  / el más tranquilo.
            .row.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/103.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Tommy is the calmest in the classroom.
                    br
                    | Tommy es el más tranquilo en el salón de clases.
            p.fw-bold
              span.f-3.p-2.pe-5 Bright / Brillante  →  Bright
                span.r-1 + est
                | = Brightest / el más brillante.
            .row.align-items-center.mb-3
              .col-lg-6
                .d-flex.align-items-center.justify-content-center
                  img(src='@/assets/curso/temas/104.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The blue dress is the brightest you have.
                    br
                    | El vestido azul es el más brillante que tú tienes.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/59.mp3')"
              ) 
      .tarjeta(style='background-color: #fff1f1')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/105.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have only one syllable and end in the letter “e”
                br
                | Para los adjetivos que  tienen una sola sílaba y terminan en la letra “e”
            p.mb-4 When an adjective consists of a single syllable and ends in the letter <b>"e"</b>, to form the comparative degree only a letter <b>"r"</b> is added at the end.
            p.fw-bold
              span.f-4.p-2.pe-5 Large / Grande  →  Large 
                span.r-1  + r 
                | = Larger / más grande.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/106.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The elephants is larger than a deer.
                    br
                    | El elefante es más grande que un venado.
            p.fw-bold
              span.f-4.p-2.pe-5 Pure  / Puro   →   Pure 
                span.r-4  + r 
                | = Purer / más puro.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/107.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The air is purer in the countryside.
                    br
                    | El aire es más puro en el campo.
            p.fw-bold
              span.f-4.p-2.pe-5 Brave / Valiente  →  Brave 
                span.r-1  + r 
                | = Braver / más valiente.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/108.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Felix is braver than Johan.
                    br
                    | Félix es más valiente que Johan.
            p.fw-bold
              span.f-4.p-2.pe-5 Rare / Raro  →  Rare 
                span.r-1  + r 
                | = Rarer / más raro.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/109.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic In this city the air is rarer than in the mountains.
                    br
                    | En esta ciudad, el aire es más raro que en las montañas.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/60.mp3')"
              ) 
      .tarjeta(style='background-color: #fff1f1')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/105.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have only one syllable and end in the letter “e”
                br
                | Para los adjetivos que  tienen una sola sílaba y terminan en la letra “e”
            p.mb-4 To form the superlative degree when the adjective consists of one syllable and ends in the letter <b>"e"</b>, it is add <b>“st”</b> to the end.
            p.fw-bold
              span.f-4.p-2.pe-5 Large / Grande  →  Large  
                span.r-1  + st 
                | = Largest  / el más grande.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/110.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The whale is the largest mammal in the world.
                    br
                    | La ballena es el mamífero más grande del mundo.
            p.fw-bold
              span.f-4.p-2.pe-5 Pure  / Puro   →   Pure 
                span.r-4  + st 
                | = Purest / el más puro.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/111.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This is the purest  water we have around here.
                    br
                    | Esta es el agua más pura que tenemos por aquí.
            p.fw-bold
              span.f-4.p-2.pe-5 Brave / Valiente  →  Brave 
                span.r-1  + st 
                | = Bravest / el más valiente.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/112.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic James is the bravest soldier of the group.
                    br
                    | James es el soldado más valiente en el grupo.
            p.fw-bold
              span.f-4.p-2.pe-5 Rare / Raro  →  Rare  
                span.r-1  + st  
                | = Rarest / el más raro.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/113.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This is the rarest stone I have found in the river. 
                    br
                    | Esta es la piedra más rara que he encontrado en el río.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/61.mp3')"
              ) 
      .tarjeta(style='background-color: #fff7da')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/114.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have a single syllable made up of: consonant, vowel, and consonant
                br
                | Para los adjetivos que  tienen una sola sílaba conformada por: consonante, vocal y consonante
            p.mb-4 In this case, to form the comparative degree, its last consonant is doubled and <b>“er”</b> is added in the end.
            p.fw-bold
              span.f-5.p-2.pe-5 Hot / Caliente  →   Hot + t + er = Hotter / más caliente.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/115.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This water is hotter than that one.
                    br
                    | Esta agua está más caliente que aquella.
            p.fw-bold
              span.f-4.p-2.pe-5 Sad  / Triste   →   Sad + d + er = Sadder / más triste. 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/116.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Laura is sadder than Julia.
                    br
                    | Laura está más triste que Julia.
            p.fw-bold
              span.f-4.p-2.pe-5 Tan / Bronceado  →  Tan + n + er = Tanner  / más bronceado
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/117.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Joe is tanner than Peter.
                    br
                    | Joe está más bronceado que Peter.
            p.fw-bold
              span.f-4.p-2.pe-5 Wet / Húmedo  →  Wet + t + er = Wetter / más húmedo.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/118.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic These clothes are wetter than yours. 
                    br
                    | Estas ropas están más húmedas que las tuyas.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/62.mp3')"
              ) 
      .tarjeta(style='background-color: #fff7da')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/114.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have a single syllable made up of: consonant, vowel, and consonant
                br
                | Para los adjetivos que  tienen una sola sílaba conformada por: consonante, vocal y consonante
            p.mb-4 Para formar el grado superlativo, en este caso, se duplica su última consonante y se le añade <b>“est”</b> al final.
            p.fw-bold
              span.f-5.p-2.pe-5 Hot / Caliente  →   Hot + t + est = Hottest / el más caliente.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/119.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This is the hottest water in the whole spa.
                    br
                    | Esta es el agua más caliente de todo el balneario.
            p.fw-bold
              span.f-4.p-2.pe-5 Sad  / Triste   →   Sad + d + est = Saddest / el más triste. 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/120.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic It is the saddest song that she sings.
                    br
                    | Es la canción más triste que ella canta.
            p.fw-bold
              span.f-4.p-2.pe-5 Tan / Bronceado  →  Tan + n + est = Tannest  / el más bronceado.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/121.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Fanny is the tannest girl in the group.
                    br
                    | Fanny es la chica más bronceada del grupo.
            p.fw-bold
              span.f-4.p-2.pe-5 Wet / Húmedo  →  Wet + t + est = Wettest / el más húmedo.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/122.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This is the wettest place in this house.
                    br
                    | Este es el sitio más húmedo en la casa.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/63.mp3')"
              ) 
            
      .tarjeta(style='background-color: #e1e8ff')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/123.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have two syllables and end in "y"
                br
                | Para los adjetivos que  tienen dos sílabas y terminan en “y”
            p.mb-4 In this case, to form the comparative degree, the <b>“y”</b> is changed to <b>“i”</b> and <b>“er”</b> is added at the end.
            p.fw-bold
              span.f-3.p-2.pe-5 Ugly / Feo  →   Ugly 
                span.r-1 (- y + i) + er 
                |= Uglier / más feo.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/124.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Randy is uglier than Joan.
                    br
                    | Randy es más feo que Joan.
            p.fw-bold
              span.f-3.p-2.pe-5 Silly  / Tonto   →   Silly 
                span.r-1 (- y + i) + er 
                | = Sillier / más tonto.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/125.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Camila is sillier than her friend.
                    br
                    | Camila es más tonta que su amiga.
            p.fw-bold
              span.f-3.p-2.pe-5 Tiny / Diminuto  →  Tiny 
                span.r-1 (- y + i) + er 
                | = Tinier  / más diminuto.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/126.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This bird is tinier than that parrot.
                    br
                    | Este pájaro es más diminuto que ese loro.
            p.fw-bold
              span.f-3.p-2.pe-5 Salty  / Salado  →  Salty 
                span.r-1 (- y + i) + er 
                | = Saltier / más salado.
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/127.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The  food you ordered today is saltier than the one I ordered yesterday.
                    br
                    | La comida que pediste hoy está más salada que la que yo pedí ayer.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/64.mp3')"
              ) 
      .tarjeta(style='background-color: #e1e8ff')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/123.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have two syllables and end in "y"
                br
                | Para los adjetivos que  tienen dos sílabas y terminan en “y”
            p.mb-4 To form the superlative degree, in this case, the <b>"y"</b> is changed to <b>"i"</b>, then <b>"est"</b> is added at the end.
            p.fw-bold
              span.f-3.p-2.pe-5 Ugly / Feo  →   Ugly 
                span.r-1 (- y + i) + est  
                |= Ugliest / el más feo. 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/128.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Bob is the ugliest in his family.
                    br
                    | Bob es el más feo de su familia.
            p.fw-bold
              span.f-3.p-2.pe-5 Silly  / Tonto   →   Silly  
                span.r-1 (- y + i) + est  
                | = Silliest / el más tonto.	
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/129.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Carmen is the silliest girl I know.
                    br
                    | Carmen es la chica más tonta que conozco.
            p.fw-bold
              span.f-3.p-2.pe-5 Tiny / Diminuto  →  Tiny    
                span.r-1 (- y + i) + est 
                | = Tiniest  / el más diminuto. 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/130.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This is the tiniest kitten in the litter.
                    br
                    | Este es el gatito más diminuto de la camada.
            p.fw-bold
              span.f-3.p-2.pe-5 Salty  / Salado  →  Salty 
                span.r-1 (- y + i) + est 
                | = Saltiest / el más salado. 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/131.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic This food is the saltiest in this restaurant.
                    br
                    | Esta comida es la más salada en este restaurante.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/65.mp3')"
              ) 
      .tarjeta(style='background-color: #fff7da')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/135.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have two or more syllables
                br
                | Para los adjetivos que  tienen dos o más sílabas
            p.mb-4 In this case, to form the comparative degree, the structure is used: <b>more…than</b> (comparative of superiority), <b>less…than</b> (comparative of inferiority) or the structure <b>as…as</b> (comparative of equality)
            h4.mb-4.fst-italic Adjective / Adjetivo: Handsome / Guapo.
            p.fw-bold
              span.f-5.p-2.pe-5 Ugly / Feo  →   Ugly 
                span.r-1 (- y + i) + est  
                |= Ugliest / el más feo. 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/132.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Bob is the ugliest in his family.
                    br
                    | Bob es el más feo de su familia.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of equality. / Grado comparativo de igualdad: 	
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/132.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Peter is as handsome as Felix. 
                    br
                    | Peter es tan guapo como Félix.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of superiority. / Grado comparativo de superioridad:  
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/132.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Peter is more handsome than Felix.
                    br
                    | Peter es más guapo que Félix.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of inferiority. /  Grado comparativo de inferioridad: 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/132.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Peter is less handsome than Felix. 
                    br
                    | Peter es menos guapo que Félix.
            p.fw-bold
              span.f-5.p-2.pe-5 Superlative degree. / Grado superlativo: 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/132.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic Peter is the most handsome. 
                    br
                    | Peter es el más guapo.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/66.mp3')"
              ) 
      .tarjeta(style='background-color: #fff7da')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/135.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have two or more syllables
                br
                | Para los adjetivos que  tienen dos o más sílabas
            p.mb-4 In this case, to form the comparative degree, the structure is used: <b>more…than</b> (comparative of superiority), <b>less…than</b> (comparative of inferiority) or the structure <b>as…as</b> (comparative of equality)
            h4.mb-4.fst-italic Adjective / Adjetivo: Expensive / Caro. 
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of equality. / Grado comparativo de igualdad: 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/133.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The sweater is as expensive as the skirt. 
                    br
                    | El suéter es tan caro como la falda.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of superiority. / Grado comparativo de superioridad:  	
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/133.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The sweater is more expensive than the skirt. 
                    br
                    | El suéter es más caro que la falda.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of inferiority. /  Grado comparativo de inferioridad:   
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/133.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The sweater is less expensive than the skirt. 
                    br
                    | El suéter es menos caro que la falda.
            p.fw-bold
              span.f-5.p-2.pe-5 Superlative degree. / Grado superlativo: 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/133.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic The sweater is the most expensive. 
                    br
                    | El suéter es el más caro.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/67.mp3')"
              ) 
      .tarjeta(style='background-color: #fff7da')
        .row.justify-content-center.align-items-end.mb-5
          .col-lg-3: img(src='@/assets/curso/temas/135.png', alt='')
          .col-lg-9.p-5
            .titulo-slyder.d-inline-block.p-4.mb-4
              h3.mb-0.me-5 
                span.text-white For adjectives that have two or more syllables
                br
                | Para los adjetivos que  tienen dos o más sílabas
            p.mb-4 In this case, to form the comparative degree, the structure is used: <b>more…than</b> (comparative of superiority), <b>less…than</b> (comparative of inferiority) or the structure <b>as…as</b> (comparative of equality)
            h4.mb-4.fst-italic Adjective / Adjetivo: Polite / Cortés. 
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of equality. / Grado comparativo de igualdad: 
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/134.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic James is as polite as Michael. 
                    br
                    | James es tan cortés como Michael.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of superiority. / Grado comparativo de superioridad:   	
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/134.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic James is more polite than Michael. 
                    br
                    | James es más cortés que Michael.
            p.fw-bold
              span.f-5.p-2.pe-5 Comparative degree of inferiority. /  Grado comparativo de inferioridad:    
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/134.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic James is less polite than Michael. 
                    br
                    | James es menos cortés que Michael.
            p.fw-bold
              span.f-5.p-2.pe-5 Superlative degree. / Grado superlativo:  
            .row.align-items-center.mb-3
              .col-lg-8
                .d-flex.align-items-center
                  img(src='@/assets/curso/temas/134.svg', alt='' style='width: 54px;').me-3
                  p.mb-0
                    span.r-1.fst-italic James is the most polite. 
                    br
                    | James es el más cortés. 
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/68.mp3')"
              ) 
    h4 <b>Irregular adjectives.</b> / Adjetivos irregulares.
    p.mb-5(data-aos='fade-right') 
      span.r-4.fst-italic.fw-normal There are also certain adjectives in English called irregular, because they do not follow any rule when forming comparative and superlative degrees. In general, they are completely different from the adjective in a positive degree. It should be noted that they have their own adjectives in their comparative and superlative forms.
      br
      br
      |También existen ciertos adjetivos en inglés denominados irregulares, porque no cumplen ninguna regla al momento de formar los grados comparativos y superlativos. En general, resultan completamente distintos al adjetivo en grado positivo. Se debe señalar que cuentan con sus propios adjetivos en sus formas comparativa y superlativa.  
    p
      span.r-4.fst-italic.fw-normal For example 
      | / Por ejemplo:      

    .row.justify-content-center.mb-5
      .col-lg-3
        .titulo-sexto.color-primario(data-aos='fade-right')
          h5 Tabla 8
          span El adjetivo “Good” / Bueno
        .table-purple
          .table-purple__top
            .tarjeta.rounded-0.color-secundario.p-3
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/2.2_tabla_8_cf1.wav')"
              ) 
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Positive degree 
                | / Grado positivo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Good
              br
              br
              span.r-1.fst-italic Marcus is a good boy.
          .table-purple__middle
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Comparative degree 
                | / Grado comparativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Better
              br
              br
              span.r-1.fst-italic She dances better than you.
          .table-purple__bottom
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Superlative degree 
                | / Grado superlativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Best
              br
              br
              span.r-1.fst-italic This is the best week of the <br>year for her.
      .col-lg-3
        .titulo-sexto.color-primario(data-aos='fade-right')
          h5 Tabla 9
          span El adjetivo “Bad” / Malo
        .table-purple
          .table-purple__top
            .tarjeta.rounded-0.color-secundario.p-3
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/2.2_tabla_9_cf1.wav')"
              ) 
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Positive degree 
                | / Grado positivo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Bad
              br
              br
              span.r-1.fst-italic Tommy is a bad boy.
          .table-purple__middle
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Comparative degree 
                | / Grado comparativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Worse
              br
              br
              span.r-1.fst-italic This day is worse than yesterday.
          .table-purple__bottom
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Superlative degree 
                | / Grado superlativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Worst
              br
              br
              span.r-1.fst-italic Mark is the worst student at <br>school.
      .col-lg-3
        .titulo-sexto.color-primario(data-aos='fade-right')
          h5 Tabla 10
          span  El adjetivo ”Far” / Lejos
        .table-purple
          .table-purple__top
            .tarjeta.rounded-0.color-secundario.p-3
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/2.2_tabla_10_cf1.wav')"
              ) 
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Positive degree 
                | / Grado positivo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Far
              br
              br
              span.r-1.fst-italic Amy lives far from school
          .table-purple__middle
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Comparative degree 
                | / Grado comparativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Further
              br
              br
              span.r-1.fst-italic She has to make an effort to go further.
          .table-purple__bottom
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Superlative degree  
                | / Grado superlativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Furthest
              br
              br
              span.r-1.fst-italic The furthest place from <br>Alaska is Argentina.
      .col-lg-3
        .titulo-sexto.color-primario(data-aos='fade-right')
          h5 Tabla 11
          span El adjetivo ”Little” / Pequeño
        .table-purple
          .table-purple__top
            .tarjeta.rounded-0.color-secundario.p-3
              TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/2.2_tabla_11_cf1.wav')"
              ) 
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Positive degree 
                | / Grado positivo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Little
              br
              br
              span.r-1.fst-italic Mary is a little fat.
          .table-purple__middle
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Comparative degree 
                | / Grado comparativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Less
              br
              br
              span.r-1.fst-italic She is less fat than her sister Claire.
          .table-purple__bottom
            .table-title.p-3.mb-4
              p.text-center.fw-bold.mb-0
                span.r-1.fst-italic Superlative degree 
                | / Grado superlativo
            p.text-center
              span.f-6.fw-bold.px-5.py-1 Least
              br
              br
              span.r-1.fst-italic Sophie is the least fat of <br>Mary’s sisters.
    .tarjeta.p-4.p-md-5.mb-5(style='background-color: #dbedfd ')
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/curso/temas/136.svg")

        .col-md.col-lg-6
          h3 Listado de adjetivos calificativos
          p.mb-4 
            span.r-1.fst-italic Below is a list of qualifying adjectives, referencing their positive degree, translation into Spanish, also presenting the corresponding comparative and superlative degrees.
            br
            br
            |A continuación, se presenta un listado de adjetivos calificativos, referenciando su grado positivo, traducción al español, presentándose además los correspondientes grados comparativos y superlativos.
          
          a.boton.color-acento-contenido(:href="obtenerLink('downloads/documento1.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download
    p.mb-5(data-aos='fade-right') A continuación, escuche los siguientes diálogos, y luego realice los ejercicios correspondientes.
    .row.justify-content-center.mb-5
      .col-lg-8
        h4 Dialogue 02   Qualifying adjectives
        .tarjeta.p-4.color-primario.bg-claro
          DialogoChat.color-primario(:dialogo="dialogoUno")
    Dialogo.color-secundario(:dialogo="dialogoDos").mb-5
      template(#nombre-actividad) Tipo de actividad (completar, puzle, pronunciación, etc)
      template(#titulo-actividad) Qualifying adjectives - Completa la conversación
      template(#descripcion-actividad) Arrastra y suelta cada una de las palabras en el orden correcto.
    .row.justify-content-center.mb-5
      .col-lg-8
        h4 Dialogue 03   Qualifying adjectives
        .tarjeta.p-4.color-primario.bg-claro
          DialogoChat.color-primario(:dialogo="dialogoTres")
    p.mb-5(data-aos='fade-right') Luego realice los siguientes ejercicios:
    Dialogo.color-secundario(:dialogo="dialogoCuatro").mb-5
      template(#nombre-actividad) Tipo de actividad (completar, puzle, pronunciación, etc)
      template(#titulo-actividad) Qualifying adjectives - Completa la conversación
      template(#descripcion-actividad) Arrastra y suelta cada una de las palabras en el orden correcto.
    .titulo-segundo.color-primario(data-aos='fade-right')
      h2 Actividad Didactica 
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/completar-espacios.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Are you smart? / ¿Eres inteligente?
        p.mb-4 Utilizar los adjetivos calificativos de acuerdo con la estructura indicada: comparativos y superlativos, de acuerdo con el contexto que se maneja en la oración.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Completar los espacios
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/a2/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece






























</template>

<script>
import DialogoChat from '../components/DialogoChat.vue'

export default {
  name: 'Tema2',
  components: {
    DialogoChat,
  },
  data: () => ({
    ocultarEsp: true,
    ocultarEsp2: true,
    dialogoUno: {
      personajes: [
        {
          nombre: 'Susy',
          img: require('@/assets/curso/temas/Susy.png'),
        },
        {
          nombre: 'Karol',
          img: require('@/assets/curso/temas/Karol.png'),
        },
      ],
      dialogo: [
        {
          personaje: 'Susy',
          textoIng:
            'Tell me, Karol, isn’t this a beautiful design for my kitchen?',
          textoEsp: '',
          audio: require('@/assets/audios/d2/1.wav'),
        },
        {
          personaje: 'Karol',
          textoIng: 'Yes, I think so. And, who is the designer?',
          textoEsp: '',
          audio: require('@/assets/audios/d2/2.wav'),
        },
        {
          personaje: 'Susy',
          textoIng:
            'You won’t believe it! I took this amazing design out of a magazine.',
          textoEsp: '',
          audio: require('@/assets/audios/d2/3.wav'),
        },
        {
          personaje: 'Karol',
          textoIng: 'Wow. Really, it’s a spectacular design for your kitchen.',
          textoEsp: '',
          audio: require('@/assets/audios/d2/4.wav'),
        },
        {
          personaje: 'Susy',
          textoIng: 'Yes. I want an amazing environment here in the kitchen.',
          textoEsp: '',
          audio: require('@/assets/audios/d2/5.wav'),
        },
      ],
    },
    dialogoDos: {
      personajes: [
        {
          nombre: 'Susy',
          img: require('@/assets/curso/temas/Susy.png'),
        },
        {
          nombre: 'Karol',
          img: require('@/assets/curso/temas/Karol.png'),
        },
      ],
      dialogo: [
        {
          personaje: 'Susy',
          textoIng: ' Isn’t this a *** design for my kitchen?',
          textoEsp: '',
          audio: require('@/assets/audios/a2/1.wav'),
          palabra: 'beautiful',
        },
        {
          personaje: 'Karol',
          textoIng: 'I took this *** design out of a magazine.',
          textoEsp: '',
          audio: require('@/assets/audios/a2/2.wav'),
          palabra: 'amazing',
        },
      ],
    },
    dialogoTres: {
      personajes: [
        {
          nombre: 'Peter',
          img: require('@/assets/curso/temas/Peter.png'),
        },
        {
          nombre: 'Caitlyn',
          img: require('@/assets/curso/temas/Caitlyn.png'),
        },
      ],
      dialogo: [
        {
          personaje: 'Peter',
          textoIng: 'Hi Caitlyn! What are you doing?',
          textoEsp: '',
          audio: require('@/assets/audios/d3/1.mp3'),
        },
        {
          personaje: 'Caitlyn',
          textoIng:
            'Hey Peter! I am really tired; these are really difficult days at work.',
          textoEsp: '',
          audio: require('@/assets/audios/d3/2.wav'),
        },
        {
          personaje: 'Peter',
          textoIng:
            'Oh! That’s true, this is a very intense month for your company!',
          textoEsp: '',
          audio: require('@/assets/audios/d3/3.mp3'),
        },
        {
          personaje: 'Caitlyn',
          textoIng:
            'Yes, fortunately, we have incredibly smart people working with us.',
          textoEsp: '',
          audio: require('@/assets/audios/d3/4.wav'),
        },
        {
          personaje: 'Peter',
          textoIng:
            'You are right, they are extremely hardworking people, I miss working with your incredible team.',
          textoEsp: '',
          audio: require('@/assets/audios/d3/5.mp3'),
        },
      ],
    },
    dialogoCuatro: {
      personajes: [
        {
          nombre: 'Peter',
          img: require('@/assets/curso/temas/Peter.png'),
        },
        {
          nombre: 'Caitlyn',
          img: require('@/assets/curso/temas/Caitlyn.png'),
        },
      ],
      dialogo: [
        {
          personaje: 'Caitlyn',
          textoIng: ' I am really *** these are really difficult days at work',
          textoEsp: '',
          audio: require('@/assets/audios/a3/1.wav'),
          palabra: 'tired',
        },
        {
          personaje: 'Caitlyn',
          textoIng:
            'Fortunately, we have incredibly *** people working with us.',
          textoEsp: '',
          audio: require('@/assets/audios/a3/2.wav'),
          palabra: 'smart',
        },
      ],
    },
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass">
.card-audio-bg2
  background-repeat: no-repeat
  background-size: cover
  background-position: center
  width: 100%
  height: 516px
.card-audio-bg
  border-radius: 20px
  background-repeat: no-repeat
  background-size: cover
  background-position: center
  width: 100%
  height: 307px
  .tarjeta-audio__texto.h5
    color: #ff5f65 !important
.audio-red
  .tarjeta-audio__texto.h5
    color: #ff5f65 !important
.tarjeta-audio-botton

  overflow: hidden
  border-radius: 20px
  display: flex
  flex: wrap
.border-audio
  .audio__btn, .audio__btn:hover , .audio__btn:focus
    outline: solid 20px  $white
.tarjeta-bg
  background-image: url('../assets/curso/temas/tarjeta-bg.svg')
.tarjeta-icon-up
  position: relative
  border-radius: 20px
  &__img
    width: 100%
    position: inherit
    top: 0
    left: 0
    transform: translateY(-40%)
slyder-f__btn
  .fa-chevron-right:before
    content: 'url(../assets/curso/temas/flecha-derecha.svg)' !important
.titulo-slyder
  background-color: #ff5f65 !important
  border-radius: 0px 50px 50px 30px
.table-purple
  border-color: #3c3fa7 !important
  &__top, &__middle, &__bottom
    overflow: hidden
  &__top
    overflow: hidden
    border-radius: 10px 10px 0px 0px
    border: 2px solid
  &__middle
    overflow: hidden
    border-left: 2px solid
    border-right: 2px solid
  &__bottom
    border-radius: 0px 0px 10px 10px
    border: 2px solid
.table-title
  background-color: #e1e8ff
</style>
