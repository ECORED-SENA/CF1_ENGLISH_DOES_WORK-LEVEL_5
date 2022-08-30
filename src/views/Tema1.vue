<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 <em>Simple present tense</em> (Tiempo presente simple)
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-3: img(src='@/assets/curso/temas/1.png', alt='')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p
              span.r-1.fst-italic When speaking or writing about a topic or current situation, the simple present tense is the verb tense that is used, as it is essential when it is necessary to describe habitual actions that happen with a certain frequency. However, it does not refer to the activity or action that is happening at the present time (the present continuous tense is used for this).
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p Cuando se habla o se escribe acerca de un tema o situación actual, el tiempo presente simple es el tiempo verbal que se utiliza, porque resulta indispensable cuando es necesario describir acciones habituales que suceden con cierta frecuencia. Sin embargo, no hace referencia a la actividad o acción que está ocurriendo en el momento actual (para ello se utiliza el tiempo presente continuo).
          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
    p.mb-5(data-aos='fade-right') A continuación, se presentan los siguientes ejemplos utilizando el presente simple:
    div(style='background-color: #fff7da').p-5.mb-5
      h5.text-center.span-title.mb-5
        span.px-4 Simple Present
      .row.justify-content-center.mb-3
        .col-lg-4.mb-lg-0.mb-3
          .card-grow-image
            img(src='@/assets/curso/temas/2.jpg', alt='')
            .card-grow-image__title
              h6.span-title2.mb-2.fst-italic
                span.px-5 Richard eats his lunch.
        .col-lg-4.mb-lg-0.mb-3
          .card-grow-image
            img(src='@/assets/curso/temas/3.jpg', alt='')
            .card-grow-image__title
              h6.span-title2.mb-2.fst-italic
                span.px-5 Lia and Patty are friends.
        .col-lg-4
          .card-grow-image
            img(src='@/assets/curso/temas/4.jpg', alt='')
            .card-grow-image__title
              h6.span-title2.mb-2.fst-italic
                span.px-5 They go to school every day.
      .row.justify-content-center.mb-5
        .col-lg-4.mb-lg-0.mb-3
          .card-grow-image
            img(src='@/assets/curso/temas/5.jpg', alt='')
            .card-grow-image__title
              h6.span-title2.mb-2.fst-italic
                span.px-5 In that city it rains daily.
        .col-lg-4.mb-lg-0.mb-3
          .card-grow-image
            img(src='@/assets/curso/temas/6.jpg', alt='')
            .card-grow-image__title
              h6.span-title2.mb-2.fst-italic
                span.px-5 Mary is a nurse.
        .col-lg-4
          .card-grow-image
            img(src='@/assets/curso/temas/7.jpg', alt='')
            .card-grow-image__title
              h6.span-title2.mb-2.fst-italic
                span.px-5 She works in a hospital.
      .row.justify-content-center
        .col-lg-8
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/1.mp3')"
            )      
    #t_1_1.titulo-segundo.color-primario(data-aos='fade-right')
      h2 1.1 <em>Simple present tense function</em> (Función del tiempo presente simple)
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal
        | The simple present tense in English allows us to express that a situation occurs at that moment (although not at the same moment it is spoken), or that it repeats itself in time.

      br
      br
      | El tiempo presente simple en inglés nos permite expresar que una situación ocurre en ese momento (aunque no en el mismo momento en que se habla), o que se repite en el tiempo.
    p.mb-5(data-aos='fade-right')
      span.r-1.fst-italic For example: 
      | / Por ejemplo: 
    .row.g-2
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/7.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.fw-bold.text-white.mb-0 The children play soccer in the park.
              p.mb-0 Los niños juegan fútbol en el parque.
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/8.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.fw-bold.text-white.mb-0 She always travels by plane.
              p.mb-0 Ella siempre viaja en avión.
      .col-lg-4
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/9.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-4
              p.fw-bold.text-white.mb-0 Peter goes to work by bus.
              p.mb-0 Peter va al trabajo en bus.
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal It also allows to give instructions, indications or signals to another individual or to a group. But it is also useful when you want to refer to some routine or custom, as well as practices that are repeated at a certain time.
      br
      br
      | También permite dar instrucciones, indicaciones o señales a otro individuo o a un grupo. Pero además sirve cuando se quiere referir a alguna rutina o costumbre, así como prácticas que se repiten en un tiempo determinado.
    p.mb-5(data-aos='fade-right')
      span.r-1.fst-italic For example: 
      | / Por ejemplo: 
    p.mb-5.text-center(data-aos='fade-right')
      span.r-1.fst-italic Giving instructions, indications or signals to another individual
    .row.justify-content-center.mb-5
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false" style='height: 400px')
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/10.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .d-flex.flex-column.justify-content-center.align-items-center.h-100
                img(src='@/assets/curso/temas/13.svg' alt='AvatarTop' style='width: 68px').mb-4
                h5.text-white.text-center.fst-italic Mario likes to swim<br> at the beach.
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false" style='height: 400px')
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/11.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .d-flex.flex-column.justify-content-center.align-items-center.h-100
                img(src='@/assets/curso/temas/14.svg' alt='AvatarTop' style='width: 68px').mb-4
                h5.text-center.fst-italic You can open the <br>door.
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false" style='height: 400px')
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/12.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .d-flex.flex-column.justify-content-center.align-items-center.h-100
                img(src='@/assets/curso/temas/15.svg' alt='AvatarTop' style='width: 68px').mb-4
                h5.text-center.fst-italic We work from<br> Monday to Friday.
    p.mb-5(data-aos='fade-right')
      span.r-2.fst-italic.fw-normal In addition, it can be used to establish an appointment, agreement or to indicate the moment in which a specific event is going to take place. In general terms, it is used to talk about hobbies, habits and attitudes of a person.
      br
      br
      |Aunado a lo anterior, puede indicarse que sirve para establecer una cita, acuerdo o señalar el momento en que va a desarrollarse un acontecimiento específico. En líneas generales, se usa para hablar de pasatiempos, hábitos y actitudes de una persona.
    p.mb-5(data-aos='fade-right')
      span.r-1.fst-italic For example: 
      | / Por ejemplo:
    p.mb-5.text-center(data-aos='fade-right')
      span.r-1.fst-italic Talk about hobbies, habits and attitudes of a person
    img.d-none.d-lg-block(src='@/assets/curso/temas/16.png', alt='')
    img.d-block.d-lg-none(src='@/assets/curso/temas/17.png', alt='')
    div(style='background-color: #e1e8ff').p-4.mb-5
      .row.justify-content-center.mb-5
        .col-lg-8
          TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/2.mp3')"
          )
    #t_1_2.titulo-segundo.color-primario(data-aos='fade-right')
      h2 1.2 <em>Simple present tense form</em> (Forma del tiempo presente simple)
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-3: img(src='@/assets/curso/temas/18.png', alt='')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p
              span.r-1.fst-italic The simple present tense is conjugated using the basic form of the verb (it is the same as the infinitive, but without the word “to”). It is of great importance to consider that when a verb is conjugated in the third-person singular, an "s" must be added at the end.
                br
                br
                |In the following table, you can see the form of conjugation, which will depend on the subject or grammatical person being spoken about, taking into account whether it is in a singular or plural number.
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp2}")
            p El tiempo presente simple se conjuga utilizando la forma básica del verbo (viene siendo igual al infinitivo, pero sin la palabra 
              span.r-1.fst-italic “to”
              | ). Resulta de gran importancia considerar que cuando se conjuga un verbo en la tercera persona del singular, debe añadirse una 
              span.r-1.fst-italic “s” 
              | al final. 
              br
              br
              |En las siguientes tablas, puede observarse la forma de conjugación, que va a depender del sujeto o persona gramatical de quien se habla, tomando en cuenta si está en número singular o plural.
          a.boton-traduccion(@click='ocultarEsp2 = !ocultarEsp2') Ver traducción
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 1
      span  Persona gramatical con el verbo 
      span.r-1 <em>“to talk”</em>
    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5
          table.border-table.fw-bold
            
            tr
              th(colspan='5' :style="{'background-image': `url(${require('@/assets/curso/temas/19.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/3.mp3')")
            tbody.text-center
              tr.fw-bold
                td(colspan='2') 
                  span.r-1.fst-italic Grammatical person 
                  br
                  | / Persona gramatical
                td 
                  span.r-1 Pronoun
                  br
                  |Pronombre
                td 
                  span.r-1.fst-italic Verb 
                  | / Verbo
                  br
                  span.fst-italic “to talk”
                td 
                  span.r-1.fst-italic Conjugation 
                  | / Conjugación
              tr
                td(rowspan='5') Singular
                td 1.ª persona
                td 
                  span.r-1 I 
                  |/ Yo
                td
                  span.r-1 talk
                td 
                  span.r-1 I talk. 
                  |/ Yo hablo.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Tú
                td
                  span.r-1 talk
                td 
                  span.r-1 You talk. 
                  | / Tú hablas.
              tr.bg-rc
                td(rowspan='3') 3.ª persona
                td 
                  span.r-1 He 
                  |/ Él
                td
                  span.r-1 talks
                td 
                  span.r-1 He talks. 
                  | / Él habla.
              tr.bg-rc
                td 
                  span.r-1 She 
                  |/ Ella
                td
                  span.r-1 talks
                td 
                  span.r-1 She talks. 
                  | / Ella habla.
              tr.bg-rc
                td 
                  span.r-1 It 
                  |/ Ello
                td
                  span.r-1 talks
                td 
                  span.r-1 It talks. 
                  | / Ello habla.
              tr
                td(rowspan='3') Plural
                td 1.ª persona
                td 
                  span.r-1 We 
                  |/ Nosotros
                td
                  span.r-1 talk
                td 
                  span.r-1 We talk. 
                  | / Nosotros hablamos.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Ustedes
                td
                  span.r-1 talk
                td 
                  span.r-1 You talk. 
                  | / Ustedes hablan.
              tr
                td 3.ª persona
                td 
                  span.r-1 They 
                  | / Ellos (as)
                td
                  span.r-1 talk
                td 
                  span.r-1 They talk. 
                  | / Ellos(as) hablan.





    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 2
      span  Persona gramatical con el verbo 
      span.r-1 <em>“to paint”</em>
    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5
          table.border-table.fw-bold
            
            tr
              th(colspan='5' :style="{'background-image': `url(${require('@/assets/curso/temas/20.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/4.mp3')")
            tbody.text-center
              tr.fw-bold
                td(colspan='2') 
                  span.r-1.fst-italic Grammatical person 
                  br
                  | / Persona gramatical
                td 
                  span.r-1 Pronoun
                  br
                  |Pronombre
                td 
                  span.r-1.fst-italic Verb 
                  | / Verbo
                  br
                  span.fst-italic “to paint”
                td 
                  span.r-1.fst-italic Conjugation 
                  | / Conjugación
              tr
                td(rowspan='5') Singular
                td 1.ª persona
                td 
                  span.r-1 I 
                  |/ Yo
                td
                  span.r-1 paint
                td 
                  span.r-1 I paint. 
                  | /Yo pinto.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Tú
                td
                  span.r-1 paint
                td 
                  span.r-1 You paint. 
                  | / Tú pintas.
              tr.bg-rc
                td(rowspan='3') 3.ª persona
                td 
                  span.r-1 He 
                  |/ Él
                td
                  span.r-1 paints
                td 
                  span.r-1 He paints. 
                  | / Él pinta.
              tr.bg-rc
                td 
                  span.r-1 She 
                  |/ Ella
                td
                  span.r-1 paints
                td 
                  span.r-1 She paints. 
                  | / Ella pinta.
              tr.bg-rc
                td 
                  span.r-1 It 
                  |/ Ello
                td
                  span.r-1 paints
                td 
                  span.r-1 It paints. 
                  | / Ello pinta.
              tr
                td(rowspan='3') Plural
                td 1.ª persona
                td 
                  span.r-1 We 
                  |/ Nosotros
                td
                  span.r-1 paint
                td 
                  span.r-1 We paint. 
                  | / Nosotros pintamos.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Ustedes
                td
                  span.r-1 paint
                td 
                  span.r-1 You paint. 
                  | / Ustedes pintan.
              tr
                td 3.ª persona
                td 
                  span.r-1 They 
                  | / Ellos (as)
                td
                  span.r-1 paint
                td 
                  span.r-1 They paint. 
                  | / Ellos(as) pintan.
    p.mb-5(data-aos='fade-right') 
      span.r-4.fw-normal.fst-italic In any case, it should also be considered that there are verbs in which certain exceptions occur, so the letter in which that verb ends must be taken into account when conjugating the third-person singular. For example, in the verbs ending in "y", this should be changed to an "i" and add "es" at the end.
      br
      br
      | En todo caso, también se debe considerar que hay verbos en los que ocurren ciertas excepciones, por lo que hay que tomar en cuenta la letra en que terminan esos verbos al conjugar la tercera persona del singular. Por ejemplo, en los verbos terminados en <em>“y”</em>, esta se debe cambiar por una <em>“i”</em> y añadir al final <em>“es”</em>.
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 3
      span  Persona gramatical con el verbo 
      span.r-1 <em>“to cry”</em>
    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5
          table.border-table.fw-bold
            
            tr
              th(colspan='5' :style="{'background-image': `url(${require('@/assets/curso/temas/21.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/5.mp3')")
            tbody.text-center
              tr.fw-bold
                td(colspan='2') 
                  span.r-1.fst-italic Grammatical person 
                  br
                  | / Persona gramatical
                td 
                  span.r-1 Pronoun
                  br
                  |Pronombre
                td 
                  span.r-1.fst-italic Verb 
                  | / Verbo
                  br
                  span.fst-italic “to cry”
                td 
                  span.r-1.fst-italic Conjugation 
                  | / Conjugación
              tr
                td(rowspan='5') Singular
                td 1.ª persona
                td 
                  span.r-1 I 
                  |/ Yo
                td
                  span.r-1 cry
                td 
                  span.r-1 I cry. 
                  | / Yo lloro.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Tú
                td
                  span.r-1 cry
                td 
                  span.r-1 You cry. 
                  | / Tú lloras.
              tr.bg-rc
                td(rowspan='3') 3.ª persona
                td 
                  span.r-1 He 
                  |/ Él
                td
                  span.r-1 cries
                td 
                  span.r-1 He cries  
                  | / Él llora.
              tr.bg-rc
                td 
                  span.r-1 She 
                  |/ Ella
                td
                  span.r-1 cries
                td 
                  span.r-1 She cries.  
                  | / Ella llora.
              tr.bg-rc
                td 
                  span.r-1 It 
                  | / Ello
                td
                  span.r-1 cries
                td 
                  span.r-1 It cries.  
                  | / Ello llora.
              tr
                td(rowspan='3') Plural
                td 1.ª persona
                td 
                  span.r-1 We 
                  |/ Nosotros
                td
                  span.r-1 cry
                td 
                  span.r-1 We cry.  
                  | / Nosotros lloramos.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Ustedes
                td
                  span.r-1 cry
                td 
                  span.r-1 You cry.  
                  | / Ustedes lloran.
              tr
                td 3.ª persona
                td 
                  span.r-1 They   
                  | / Ellos (as)
                td
                  span.r-1 cry
                td 
                  span.r-1 They cry.  
                  | / Ellos(as) lloran.
    p.mb-5(data-aos='fade-right')
      span.r-4.fw-normal.fst-italic Also, when the verbs end in "o", "sh", "ch", "ss", "x", "z", in simple present tense, “es” must be added at the end when conjugating the third-person singular.
      br
      br
      |También, cuando los verbos terminan en  “o”, “sh”, “ch”, “ss”, “x”, “z”, en tiempo presente simple, se les debe añadir “es” al final cuando se conjuga la tercera persona del singular.
    p.mb-5(data-aos='fade-right') 
      span.r-1.fst-italic For example:
      | / Por ejemplo: 
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 4
      span  Diferentes terminaciones del verbo
    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5
          table.border-table.fw-bold.fst-italic
            
            tr
              th(colspan='4' :style="{'background-image': `url(${require('@/assets/curso/temas/22.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/6.mp3')")
            tbody.text-center
              tr.bg-purple.fst-normal
                td Terminación del verbo
                td Verbo
                td Ejemplo al conjugar la tercera persona del singular
                td Traducción
              tr
                td.fst-normal Termina en letra “o”
                td To go
                td
                  span.r-1 He goes to school.
                td Él va a la escuela.
              tr
                td.fst-normal Termina en letra “sh”
                td To push
                td
                  span.r-1 Susy pushes the door
                td Susy empuja la puerta.
              tr
                td.fst-normal Termina en letra “ch”
                td To catch
                td
                  span.r-1 The dog catches the ball.
                td El perro atrapa la pelota.
              tr
                td.fst-normal Termina en letra “ss”
                td To cross
                td
                  span.r-1 The boy crosses the street.
                td El niño cruza la calle.
              tr
                td.fst-normal Termina en letra “x”
                td To relax
                td
                  span.r-1 He relaxes easily.
                td Él se relaja fácilmente.
              tr
                td.fst-normal Termina en letra “z”
                td To buzz
                td
                  span.r-1 This bee buzzes all day.
                td Esta abeja zumba todo el día.
    h4.mb-5 
      span.r-1 Affirmative form of the simple present tense 
      | / Forma afirmativa del tiempo presente simple.
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal In its affirmative form, the simple present tense uses its basic form and has the following structure:
      br
      br
      |En su forma afirmativa, el tiempo presente simple utiliza su forma básica y tiene la siguiente estructura:
    .row.justify-content-center.mb-5
      .col-lg-10: img(data-aos='zoom-in-up')(src='@/assets/curso/temas/23.svg', alt='')
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal The following table shows the present tense conjugation of the verb “to live” in the affirmative form. As can be seen, only the third-person singular adds an "s" at the end.
      br
      br
      |La siguiente tabla presenta la conjugación en tiempo presente del verbo <em>“to live”</em> en forma afirmativa. Tal como puede observarse, solo la tercera persona del singular añade una “s” al final.
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 5
      span Persona gramatical con el verbo 
      span.r-1.fst-italic “to live”
    .row.justify-content-center.mb-5
      .col-lg-11
        .tabla-a.color-acento-botones.mb-5
          table.border-table.fw-bold
            
            tr
              th(colspan='5' :style="{'background-image': `url(${require('@/assets/curso/temas/24.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/7.mp3')")
            tbody.text-center
              tr.fw-bold
                td(colspan='2') 
                  span.r-1.fst-italic Grammatical person 
                  | / Persona gramatical
                td 
                  span.r-1 Pronoun
                  br
                  |Pronombre
                td 
                  span.fst-italic.r-1 Verb
                  br
                  | Verbo
                td 
                  span.fst-italic.r-1 Complement
                  br
                  | Complemento 
              tr
                td(rowspan='5') Singular
                td 1.ª persona
                td 
                  span.r-1 I 
                  |/ Yo
                td
                  span.r-1 live  
                  | / vivo
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Tú
                td
                  span.r-1 live 
                  | / vives
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
              tr.bg-rc
                td(rowspan='3') 3.ªpersona
                td 
                  span.r-1 He 
                  | / Él
                td
                  span.r-1 lives  
                  | / vive
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
              tr.bg-rc
                td 
                  span.r-1 She 
                  |/ Ella
                td
                  span.r-1 lives  
                  | / vive
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
              tr.bg-rc
                td 
                  span.r-1 It 
                  | / Ello
                td
                  span.r-1 lives  
                  | / vive
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
              tr
                td(rowspan='3') Plural
                td 1.ª persona
                td 
                  span.r-1 We 
                  | / Nosotros
                td
                  span.r-1 live 
                  | / vivimos 
                td 
                  span.r-1 in Colombia  
                  | / en Colombia.
              tr
                td 2.ª persona
                td 
                  span.r-1 You 
                  |/ Ustedes
                td
                  span.r-1 live 
                  | / viven
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
              tr
                td 3.ª persona
                td 
                  span.r-1 They  
                  | / Ellos (as)
                td
                  span.r-1 live 
                  | / viven
                td 
                  span.r-1 in Colombia 
                  | / en Colombia.
    h4.mb-5 
      span.r-1 Negative form of the simple present tense 
      | / Forma negativa del tiempo presente simple.
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal In its negative form, the simple present tense uses its basic form and has the following structure:
      br
      br
      | En su forma negativa, el tiempo presente simple utiliza su forma básica y tiene la siguiente estructura:
    .row.justify-content-center.mb-5
      .col-lg-10: img(data-aos='zoom-in-up')(src='@/assets/curso/temas/25.svg', alt='')
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal The following table presents 
        span.r-1 the present tense 
        | conjugation of the verb 
        span.r-1 “to live” 
        | in the negative form. As can be seen, only the third-person singular adds an "es" to the auxiliary verb, since it ends in a vowel letter "o", while the main verb keeps its basic form.
      br
      br
      |En la siguiente tabla, se presenta la conjugación <b>en tiempo presente</b> del verbo 
      span.r-1.fst-italic “to live” 
      | en forma negativa. Tal como puede observarse, solo la tercera persona del singular añade “es” en el verbo auxiliar, debido a que termina en letra vocal “o”, mientras que el verbo principal mantiene su forma básica.
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 6
      span Persona gramatical con el verbo 
      span.r-1.fst-italic “to live” 
      | en forma negativa

    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5
          table.border-table
            
            tr
              th(colspan='4' :style="{'background-image': `url(${require('@/assets/curso/temas/26.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/8.mp3')")
            tbody.text-center
              tr
                td 
                  span.r-1.fst-italic Pronoun 
                  br
                  span.fw-bold Pronombre
                td.bg-rc 
                  span.r-1.fst-italic Auxiliary verb (to do) + Negation (not) 
                  br
                  span.fw-bold  Verbo auxiliar <em>(to do)</em> + Negación <em>(not)</em>
                td 
                  span.r-1.fst-italic Verb
                  br
                  span.fw-bold Verbo
                td 
                  span.r-1.fst-italic Complement
                  br
                  span.fw-bold Complemento
              tr
                td 
                  span.r-1.fst-italic I 
                  |/ Yo
                td.bg-rc.fw-bold.fst-italic do + not  → don’t
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vivo
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
              tr
                td 
                  span.r-1.fst-italic  You 
                  | / Tú
                td.bg-rc.fw-bold.fst-italic do + not  → don’t
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vives
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
              tr
                td 
                  span.r-1.fst-italic  He 
                  | /Él
                td.bg-rc.fw-bold.fst-italic does + not  → doesn’t
                td
                  span.r-1.fst-italic lives 
                  span.fw-bold / vive
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
              tr
                td 
                  span.r-1.fst-italic She 
                  | / Ella
                td.bg-rc.fw-bold.fst-italic does + not  → doesn’t
                td
                  span.r-1.fst-italic lives 
                  span.fw-bold / vive
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia..
              tr
                td 
                  span.r-1.fst-italic  It 
                  | / Ello
                td.bg-rc.fw-bold.fst-italic does + not  → doesn’t
                td
                  span.r-1.fst-italic lives 
                  span.fw-bold / vive
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
              tr
                td 
                  span.r-1.fst-italic We  
                  | / Nosostros
                td.bg-rc.fw-bold.fst-italic do + not  → don’t
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vivimos
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
              tr
                td 
                  span.r-1.fst-italic You 
                  | / Ustedes
                td.bg-rc.fw-bold.fst-italic do + not  → don’t
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / viven
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
              tr
                td 
                  span.r-1.fst-italic They 
                  | / Ellos
                td.bg-rc.fw-bold.fst-italic do + not  → don’t
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / viven
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia.
        p(data-aos='fade-right') * Contractions / contracciones:  do not = don’t y does not = doesn’t
    h4.mb-5 
      span.r-1 Interrogative form of simple present tense 
      | / Forma interrogativa del tiempo presente simple.
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal In its interrogative form, the simple present tense uses its basic form and has the following structure:
      br
      br
      | En su forma interrogativa, el verbo en tiempo presente simple utiliza su forma básica y tiene la siguiente estructura:
    .row.justify-content-center.mb-5
      .col-lg-10: img(data-aos='zoom-in-up')(src='@/assets/curso/temas/c26.svg', alt='')
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal The following table presents the present tense conjugation of the verb “to live” in interrogative form. As can be seen, only the third-person singular adds an "es" to the auxiliary verb, since "to do" ends in a vowel letter "o", while the principal verb keeps its basic form.
      br
      br
      | En la siguiente tabla, se presenta la conjugación en tiempo presente del verbo 
      span.r-4.fst-italic.fw-normal “to live” 
      | en forma interrogativa. Tal como puede observarse, solo la tercera persona del singular añade 
      span.r-4.fst-italic.fw-normal “es” 
      | en el verbo auxiliar, porque 
      span.r-1.fst-italic “to do” 
      | termina en letra vocal 
      span.r-1.fst-italic “o”
      | , mientras que el verbo principal mantiene su forma básica.
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 7
      span Verbo auxiliar 
      span.r-1.fst-italic “to do” 
      | en forma interrogativa

    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5
          table.border-table.fw-bold
            
            tr
              th(colspan='4' :style="{'background-image': `url(${require('@/assets/curso/temas/28.svg')})`}").bg-table-audio
                Audio.d-inline-block.border-audio.color-primario.m-5(:audio="require('@/assets/audios/tema1/9.mp3')")
            tbody.text-center
              tr
                td.bg-rc  
                  span.r-1.fst-italic Auxiliary verb 
                  br
                  |Verbo auxiliar <em>(To do)</em>
                td
                  span.r-1.fst-italic Pronoun
                  br
                  | Pronombre
                td 
                  span.r-1.fst-italic Verb
                  br
                  | Verbo
                td 
                  span.r-1.fst-italic Complement
                  br
                  | Complemento
              tr
                td.bg-rc.fst-italic Do
                td 
                  span.r-1.fst-italic I 
                  span.fw-bold / Yo
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vivo
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Do
                td 
                  span.r-1.fst-italic You 
                  span.fw-bold / Tú
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vives
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Does
                td 
                  span.r-1.fst-italic He 
                  span.fw-bold / Él
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vive
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Does
                td 
                  span.r-1.fst-italic She 
                  span.fw-bold / Ella
                td
                  span.r-1.fst-italic live
                  span.fw-bold / vive
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Does
                td 
                  span.r-1.fst-italic It 
                  span.fw-bold / Ello
                td
                  span.r-1.fst-italic live
                  span.fw-bold / vive
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Do
                td 
                  span.r-1.fst-italic We 
                  span.fw-bold / Nosostros
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / vivimos
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Do
                td 
                  span.r-1.fst-italic You 
                  span.fw-bold / Ustedes
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / viven
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
              tr
                td.bg-rc.fst-italic Do
                td 
                  span.r-1.fst-italic They 
                  span.fw-bold / Ellos
                td
                  span.r-1.fst-italic live 
                  span.fw-bold / viven
                td 
                  span.r-1.fst-italic in Colombia 
                  | / en Colombia ?
    .contenedor-franja.margin-n
      .franja1(style= 'height: 87%')
      .row.justify-content-center.align-items-end.g-0
        .col-lg-3.d-none.d-lg-block: img(data-aos='zoom-in-up')(src='@/assets/curso/temas/29.png', alt='')
        .col-lg-9
          .contenido.px-5
            .row.justify-content-center.mb-5
              .col-lg-2.col-6.mb-lg-0.mb-3
                img(src='@/assets/curso/temas/warning.svg', alt='' style='width:85px').m-auto
              .col-lg-10
                h4.mb-5.text-lg-white
                  span.r-1.fst-italic Warning #1
                  br
                  | Advertencia #1
            p.mb-5 
              span.r-3.fw-normal.fst-italic When answering, either the short answer or the complete answer can be used.
                br
                |Following an example from the table above:
              br
              br
              span.text-white Al responder, se puede utilizar la respuesta corta o la respuesta completa.
                
                br
                |Siguiendo un ejemplo de la tabla anterior: 
            .row.justify-content-center.mb-5
              .col-lg-4
                h5.text-white Question / Pregunta: 
                
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="Do we live in Mexico?"
                  :audio="require('@/assets/audios/tema1/tema_1_warning1_a_CF1.wav')"
                )  
                p.text-white.ms-3 ¿Nosotros vivimos en México?
              .col-lg-4
                h5.text-white Clomplete answer / Respuesta completa: 
                
                .audio-verde
                  TarjetaAudio.color-acento-botones.bg-white.mb-3(
                    texto="No, we don’t live in Mexico"
                    :audio="require('@/assets/audios/tema1/tema_1_warning1_b_CF1.wav')"
                    )  
                p.text-white.ms-3 No, nosotros no vivimos en México
              .col-lg-4
                h5.text-white Short answer / Respuesta corta:
                
                .audio-verde
                  TarjetaAudio.color-acento-botones.bg-white.mb-3(
                    texto="No, we don’t."
                    :audio="require('@/assets/audios/tema1/tema_1_warning1_c_CF1.wav')"
                    )  
                p.text-white.ms-3 No.
    Separador
    #t_1_3.titulo-segundo.color-primario(data-aos='fade-right')
      h2 1.3 <em>Simple present tense pronunciation</em> / Pronunciación del tiempo presente simple
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-3: img(src='@/assets/curso/temas/30.png', alt='')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p
              span.r-1.fst-italic As presented in the previous point, the simple present tense has the particularity of adding a letter "s" or "es" at the end (in the third-person singular). Also, in the case of verbs that end in "y", where it is changed to an "i" + "es". In these cases, the pronunciation must be taken care of because it will also vary, depending on the case.
                br
                br
                |So, when conjugating a verb in the third-person singular, in the affirmative, three different sounds will be determined when pronouncing it. These sounds are: /s/, /z/ and /iz/.
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp3}")
            p Tal como se presenta en el punto anterior, el tiempo presente simple tiene la particularidad de añadir una letra 
              span.r-4.fw-normal.fst-italic “s” 
              | o 
              span.r-4.fw-normal.fst-italic “es” 
              | al final (en tercera persona del singular). También en el caso de los verbos que terminan en 
              span.r-4.fw-normal.fst-italic “y”
              | , donde se cambia por una 
              span.r-4.fw-normal.fst-italic “i” + “es”. 
              | En estos casos, se debe cuidar la pronunciación pues también va a variar, según sea el caso.
              br
              br
              |De manera que, al conjugar un verbo en la tercera persona del singular, en forma afirmativa, se van a determinar tres sonidos diferentes al momento de pronunciarlo. Estos sonidos son: 
              span.r-1.fst-italic /s/, /z/ y /iz/.
          a.boton-traduccion(@click='ocultarEsp3 = !ocultarEsp3') Ver traducción
    p.mb-5(data-aos='fade-right')
      span.r-4.fst-italic.fw-normal Listen to the audio. 
      | / Escuche el audio.
    .row.mb-5
      .col-lg-4
        .tarjeta.color-secundario.h-100.p-5
          .card-audio-top.p-4.d-flex.flex-column.justify-content-center.mb-4(style='background-color: #f3f6ff ; border-radius: 20px')
            img(src='@/assets/curso/temas/31.svg', alt='' style='width:98px').m-auto.mb-4
            Audio.d-inline-block.color-primario.mb-3.m-auto(:audio="require('@/assets/audios/tema1/13.mp3')")
            p.text-center.mb-1
              span.r-1.fst-italic James helps her friend.
              br
              | James ayuda a su amiga.
            hr(style='background-color: #6b8dff; opacity: 1; height: 3px; border: none;').rounded-pill.m-2
            p.text-center.mb-1
              span.r-1.fst-italic Julia speaks french very well.
              br
              | Julia habla francés muy bien.
          p * <b>El sonido /s/</b> se pronuncia cuando la letra “s” se encuentra al final, luego de un sonido sordo o silencioso.
            br
            br
            span.text-white.fw-bold.fst-italic Por ejemplo: eats - speaks - works - helps.
      .col-lg-4
        .tarjeta.color-acento-contenido.h-100.p-5
          .card-audio-top.p-3.d-flex.flex-column.justify-content-center.mb-4(style='background-color: #f3f6ff ; border-radius: 20px')
            img(src='@/assets/curso/temas/31.svg', alt='' style='width:98px').m-auto.mb-4
            Audio.d-inline-block.color-primario.mb-3.m-auto(:audio="require('@/assets/audios/tema1/14.mp3')")
            p.text-center.mb-1
              span.r-1.fst-italic Billy plays the piano every day.
              br
              | Billy toca el piano todos los días.
            hr(style='background-color: #6b8dff; opacity: 1; height: 3px; border: none;').rounded-pill.m-2
            p.text-center.mb-1
              span.r-1.fst-italic Susy arrives from London today.
              br
              | Susy llega hoy de Londres.
          p <b>* El sonido /z/</b> se pronuncia cuando la letra “s” se encuentra al final, luego de un sonido sonoro de consonante o vocal
            br
            br
            span.r-2.fst-italic Por ejemplo: lives - plays - arrives - reads.
      .col-lg-4
        .tarjeta.color-primario.h-100.p-5
          .card-audio-top.p-3.px-2.d-flex.flex-column.justify-content-center.mb-4(style='background-color: #f3f6ff ; border-radius: 20px')
            img(src='@/assets/curso/temas/31.svg', alt='' style='width:98px').m-auto.mb-4
            Audio.d-inline-block.color-primario.mb-3.m-auto(:audio="require('@/assets/audios/tema1/15.mp3')")
            p.text-center.mb-1
              span.r-1.fst-italic Michael fixes the car
              br
              | Michael arregla el automóvil.
            hr(style='background-color: #6b8dff; opacity: 1; height: 3px; border: none;').rounded-pill.m-2
            p.text-center.mb-1
              span.r-1.fst-italic She watches the children from the house.
              br
              | Ella observa a los niños desde la casa.
          p * El sonido /iz/ se pronuncia cuando la letra “s” se encuentra al final, luego de un sonido de consonantes con un sonido sibilante como /ʧ/, /ʤ/, /ʃ/, /ʒ/, /z/, /s/.
            br
            br
            span.text-white.fst-italic.fw-bold  Por ejemplo: fixes - watches - pronounces - pushes.
    .contenedor-franja.margin-n.mb-5
      .franja(style= 'height: 76% ; background-color: #fff0b5')
      .row.justify-content-center.g-0
        .col-lg-9
          .contenido.px-5
            p.mb-5 
              span.r-4.fw-normal.fst-italic Below is an audio with the activities that Joe does in a day, which includes the verbs in the present simple with endings in the final letter "s" whose pronunciation includes /s/, /z/ and /iz/. You can listen to it several times and practice repeating the pronunciation of these sounds.
              br
              br
              |A continuación, se presenta un audio con las actividades que realiza Joe en un día, el cual incluye los verbos en presente simple con terminaciones en letra final “s” cuya pronunciación incluye /s/, /z/ y /iz/. Puede escucharlo varias veces y realizar prácticas de repetición de la pronunciación de estos sonidos.
            TarjetaAudio.color-acento-botones.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema1/16.mp3')"
            ) 
        .col-lg-3.d-none.d-lg-block: img(data-aos='zoom-in-up')(src='@/assets/curso/temas/32.svg', alt='')
    p.mb-5(data-aos='fade-right') A continuación, escuche el siguiente diálogo, en el cual se aplica lo estudiado en el tema
    .row.justify-content-center.mb-5
      .col-lg-8
        .tarjeta.p-4.color-primario.bg-claro
          DialogoChat.color-primario(:dialogo="dialogoUno")
    p.mb-5(data-aos='fade-right') Luego realice los siguientes ejercicios:
    Dialogo.color-secundario(:dialogo="dialogoDos").mb-5
      template(#nombre-actividad) Tipo de actividad (completar, puzle, pronunciación, etc)
<<<<<<< HEAD
      template(#titulo-actividad) Simple present tense pronunciation - Completa la conversación
      template(#descripcion-actividad) Arrastra y suelta cada una de las palabras en el orden correcto.

=======
      template(#titulo-actividad) Simple present tense pronunciatio - Completa la conversación
      template(#descripcion-actividad) Arrastra y suelta el cada una de las palabras en el orden correcto.
    .titulo-segundo.color-primario(data-aos='fade-right')
      h2 Actividad Didactica 
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/arrastrar.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 What do you do? / ¿Qué haces?
        p.mb-4 Identificar la estructura gramatical del presente simple en oraciones.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Arrastrar y soltar
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/a1/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
>>>>>>> 5a793b7a2519c59f7f7a896d30d57fdca888e682



</template>

<script>
import DialogoChat from '../components/DialogoChat.vue'
export default {
  name: 'Tema1',
  components: {
    DialogoChat,
  },
  data: () => ({
    ocultarEsp: true,
    ocultarEsp2: true,
    ocultarEsp3: true,
    dialogoUno: {
      personajes: [
        {
          nombre: 'Paul',
          img: require('@/assets/curso/temas/paul.png'),
        },
        {
          nombre: 'July',
          img: require('@/assets/curso/temas/july.png'),
        },
      ],
      dialogo: [
        {
          personaje: 'Paul',
          textoIng: 'July, do you want to go to the movies?',
          textoEsp: '',
          audio: require('@/assets/audios/d1/1.mp3'),
        },
        {
          personaje: 'July',
          textoIng: 'That’s fine. Which movie do you want to watch?',
          textoEsp: '',
          audio: require('@/assets/audios/d1/2.wav'),
        },
        {
          personaje: 'Paul',
          textoIng: 'I want to see “Jurassic World Dominion.”',
          textoEsp: '',
          audio: require('@/assets/audios/d1/3.mp3'),
        },
        {
          personaje: 'July',
          textoIng: 'That’s an excellent choice! I love the protagonist!',
          textoEsp: '',
          audio: require('@/assets/audios/d1/4.wav'),
        },
        {
          personaje: 'Paul',
          textoIng: 'Well, I have very good taste in everything!',
          textoEsp: '',
          audio: require('@/assets/audios/d1/5.mp3'),
        },
      ],
    },
    dialogoDos: {
      personajes: [
        {
          nombre: 'Paul',
          img: require('@/assets/curso/temas/paul.png'),
        },
        {
          nombre: 'July',
          img: require('@/assets/curso/temas/july.png'),
        },
      ],
      dialogo: [
        {
          personaje: 'Paul',
          textoIng: 'Do you *** to go to the movies?',
          textoEsp: '',
          audio: require('@/assets/audios/a1/1.mp3'),
          palabra: 'want',
        },
        {
          personaje: 'July',
          textoIng: 'I ***  the protagonist',
          textoEsp: '',
          audio: require('@/assets/audios/a1/2.wav'),
          palabra: 'love',
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
h5.span-title
  span
    background-color: #6b8dff
    color: $white
    border-radius: 0px 0px 10px 10px
    padding: .5rem
  margin-top: -2.5rem
.card-grow-image
  position: relative
  display: flex
  align-items: end
  justify-content: center
  overflow: hidden
  border-radius: 20px
  img
    width: 100%
    transition: transform .5s ease-in-out

  &:hover
    img
      transform: scale(1.1)
  &__title
    position: absolute
    bottom: 0
    left: 0
    width: 100%
    text-align: center
    h6.span-title2
      span
        background-color: #ffd947
        color: $color-sistema-texto
        border-radius: 10px 10px 0px 0px
        padding: .5rem
.bg-table-audio
  background-repeat: no-repeat
  background-size: 100%
  background-position: end
  width: 100%
.border-audio
  .audio__btn, .audio__btn:hover , .audio__btn:focus
    outline: solid 20px  $white
.bg-rc
  background-color: #fff1f1
.border-table
  th,td
    border: 2px solid $color-acento-botones
.bg-purple
  background-color: #d5d6f0
.audio-verde
  .tarjeta-audio.color-acento-botones
    border-color: #01ac57
    button
      background-color: #01ac57
    .h5
      color: #01ac57
    .tarjeta-audio__input input[type=range]
      background: rgba(1, 172, 87, 0.2)
      background-image: linear-gradient(#01ac57, #01ac57)
.dialogoChat
  .h5
    span
      font-style: italic
      color: #ff5f65
.noAudio
  button
    display: none
  input
    display: none
</style>
