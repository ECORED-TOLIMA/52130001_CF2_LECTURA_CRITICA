<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero(data-aos="flip-up")
        span 2
      h1 Comprensión global de textos
    
    p La comprensión de un texto es un hecho en el que interactúan un autor, que es quien comunica unas ideas, y un lector, quien interpreta el mensaje del autor. 

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
          p.mb-0 Para que dicha interacción sea posible, el lector debe activar los conocimientos que posee sobre el tema, las estrategias que ha aprendido a lo largo de su vida, el conocimiento que tiene de su lengua materna y la visión del mundo que ha configurado con sus conocimientos y experiencias. La comprensión de un texto o de un asunto oral requiere de un acto unidireccional en el que un emisor comunica algo que debe ser asimilado o entendido por otro.
    p.mt-4 Para que haya una verdadera comprensión, el texto debe ser interpretado en distintos niveles:

    .row.justify-content-center
      .col-lg-3.col-md-6.mb-4.mb-lg-0
        .tarjeta.bg-2.p-4.text-center.h-100
          .row.justify-content-center.mb-3
            .col-auto
              .circle-verde
                figure(data-aos="fade-down")
                  img(src='@/assets/curso/tema2/2.svg', alt='Literal', style='width: 80px')
          h5.mb-0 Literal

      .col-lg-3.col-md-6.mb-4.mb-lg-0
        .tarjeta.bg-8.p-4.text-center.h-100
          .row.justify-content-center.mb-3
            .col-auto
              .circle-verde
                figure(data-aos="fade-down")
                  img(src='@/assets/curso/tema2/3.svg', alt='Inferencial', style='width: 80px')
          h5.mb-0 Inferencial

      .col-lg-3.col-md-6.mb-4.mb-lg-0
        .tarjeta.bg-2.p-4.text-center.h-100
          .row.justify-content-center.mb-3
            .col-auto
              .circle-verde
                figure(data-aos="fade-down")
                  img(src='@/assets/curso/tema2/4.svg', alt='Crítico valorativo', style='width: 80px')
          h5.mb-0 Crítico valorativo

      .col-lg-3.col-md-6
        figure(data-aos="fade-down")
          img(src='@/assets/curso/tema2/5.svg', alt='Ilustración decorativa', style='width: 100%')


    p.mt-4 Comprender un texto en los tres niveles mencionados se necesita de un proceso.

    SlyderA.p-4.bg-14.bg-r8(tipo="b")
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-4.mb-lg-0
          h4 Nivel literal
          p Consiste en identificar y comprender todo aquello que el autor comunica de manera explícita en el texto. Esto implica:
          ul.lista-ul--color
            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Comprender el vocabulario utilizado (palabras clave para el sentido del texto).

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Interpretar las oraciones completas.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Analizar cada párrafo para construir una idea global del contenido.

          p Este nivel es fundamental para acceder a los niveles superiores de comprensión.
        
        .col-lg-6
          figure(data-aos="fade-down")
            img(src='@/assets/curso/tema2/6.png', alt='Estudiantes conversando', style='width: 572px')

      .row.justify-content-center.align-items-center
        .col-lg-6.mb-4.mb-lg-0
          h4 Nivel inferencial
          p Permite interpretar la intención comunicativa del autor más allá de lo explícito. En este nivel:

          ul.lista-ul--color
            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 El lector deduce significados no expresados directamente.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Se realiza una lectura fluida que integra simultáneamente los tres niveles.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Solo cuando surge dificultad, se retorna al nivel literal para aclarar el sentido.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Requiere competencia lingüística y conocimientos previos del tema.

          p Este nivel representa el puente entre la comprensión básica y la lectura crítica.
        
        .col-lg-6
          figure(data-aos="fade-down")
            img(src='@/assets/curso/tema2/7.png', alt='Persona estudiando', style='width: 572px')

      .row.justify-content-center.align-items-center
        .col-lg-6.mb-4.mb-lg-0
          h4 Nivel crítico-valorativo
          p Implica evaluar, valorar y juzgar tanto el contenido explícito como las inferencias del texto. Este nivel requiere:

          ul.lista-ul--color
            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Argumentar posiciones propias basadas en evidencias del texto.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Proyectar implicaciones y consecuencias de lo planteado.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Cuestionar la validez y pertinencia de los argumentos del autor.

            li.d-flex.align-items-start
              i.lista-ul__vineta
              p.mb-0 Sustentar juicios con elementos textuales concretos.

          p El lector asume una posición crítica y reflexiva frente al discurso del autor, construyendo interpretaciones fundamentadas.
        
        .col-lg-6
          figure(data-aos="fade-down")
            img(src='@/assets/curso/tema2/8.png', alt='Pila de libros', style='width: 572px')


    .titulo-tres.mt-5: h3 Tipo de textos y funciones del lenguaje

    
    .row.align-items-center.mb-5
      .col-lg-8
        .tarjeta.bg-5.p-4.mb-4
          p.mb-0 La función esencial del lenguaje es permitir a las personas la interacción y coordinación de sus acciones, mediante la comunicación de significados construidos por un emisor y destinados a un receptor. El receptor, a su vez, se vuelve emisor de los significados que va construyendo. Como herramienta de interacción y comunicación, el lenguaje tiene diferentes funciones:
        .row.justify-content-center
          .col-lg-4.mb-4.mb-lg-0
            .tarjeta-avatar
              img(src='@/assets/curso/tema2/9.svg' alt='AvatarTop')
              .tarjeta.shadow.bg-2
                .p-4.pt-5
                  h5.text-center.mb-3 Función persuasiva o apelativa
                  p.text-center.mb-0 Busca convencer al receptor de creer o hacer algo.

          .col-lg-4.mb-4.mb-lg-0
            .tarjeta-avatar
              img(src='@/assets/curso/tema2/10.svg' alt='AvatarTop')
              .tarjeta.shadow.bg-2
                .p-4.pt-5
                  h5.text-center.mb-3 Función expresiva
                  p.text-center.mb-0 Permite expresar emociones, sentimientos o sensaciones del emisor.

          .col-lg-4
            .tarjeta-avatar
              img(src='@/assets/curso/tema2/11.svg' alt='AvatarTop')
              .tarjeta.shadow.bg-2
                .p-4.pt-5
                  h5.text-center.mb-3 Función informativa o referencial
                  p.text-center.mb-0 Tiene como propósito informar algo al receptor.

      .col-lg-4
        figure.d-none.d-lg-block(data-aos="fade-down")
          img(src='@/assets/curso/tema2/12.png', alt='Persona leyendo tablet', style='width: 291px')


    p.mt-4 Según la intención comunicativa del autor, los textos se clasifican en diferentes tipos que corresponden a las funciones del lenguaje. En la Figura 1 se presentan las tres funciones principales del lenguaje y los tipos de textos que corresponden a cada una de ellas:


    .row.justify-content-center
      .col-lg-10

        .titulo-sexto.color-acento-contenido.mb-3.mt-4
          h5 Figura 1.
          span Funciones del lenguaje y tipos de textos

        figure(data-aos="fade-down")
          img.d-none.d-md-block.m-auto(
            src='@/assets/curso/tema2/13.svg',
            alt='Figura 1. Funciones del lenguaje y tipos de textos. La figura clasifica los textos según la intención comunicativa del autor en tres funciones: la persuasiva, que busca convencer; la expresiva, que permite manifestar emociones; y la referencial o informativa, que tiene como propósito transmitir información objetiva. ', style="width: 1020px").m-auto
          
          img.d-block.d-md-none.m-auto(
            src='@/assets/curso/tema2/13m.svg',
            alt='Figura 1. Funciones del lenguaje y tipos de textos. La figura clasifica los textos según la intención comunicativa del autor en tres funciones: la persuasiva, que busca convencer; la expresiva, que permite manifestar emociones; y la referencial o informativa, que tiene como propósito transmitir información objetiva. '
          )

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
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

<style lang="sass"></style>
