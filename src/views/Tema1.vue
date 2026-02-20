<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero(data-aos="flip-up")
        span 1
      h1 Técnicas de comprensión lectora

    p.mb-4 La comprensión lectora permite entender, interpretar y analizar la información que presentan los textos. Comprender un texto implica ir más allá de reconocer palabras; requiere identificar las ideas principales, secundarias entre otras y construir significados coherentes.

    p.mb-4 Para desarrollar esta habilidad, es importante aplicar un proceso que incluye:

    .row.justify-content-center
      .col-10.col-md-6.col-lg-4.mb-4.mb-md-0(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/1.svg')
          .tarjeta.color-primario.shadow
            .p-4
              .row.justify-content-center.mb-3
                .col-auto
                  .py-2.px-3
              p.text-center.mb-0 Identificar la información clave y las ideas principales del texto.
      .col-10.col-md-6.col-lg-4.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/2.svg')
          .tarjeta.color-primario.shadow
            .p-4
              .row.justify-content-center.mb-3
                .col-auto
                  .py-2.px-3
              p.text-center.mb-0 Relacionar estas ideas para entender cómo se conectan y complementan.

      .col-10.col-md-6.col-lg-4.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/3.svg')
          .tarjeta.color-primario.shadow
            .p-4
              .row.justify-content-center.mb-3
                .col-auto
                  .py-2.px-3
              p.text-center.mb-0 Sintetizar la información en las propias palabras, lo que demuestra comprensión real.

    p.mt-4 Una manera efectiva de verificar la comprensión es mejorar una síntesis propia de lo que se ha leído, ya sea de forma oral o escrita. Esta práctica confirma que la información se ha procesado y comprendido correctamente.



    .titulo-tres.mt-5: h3 ¿Qué operaciones cognitivas se requieren cuando se busca comprender lo estudiado o leído?

    .row.bg-3
      .col-12
        .p-5
          .row.align-items-center
            .col-lg-4.d-lg-block.d-none
              figure
                img(src='@/assets/curso/tema1/4.png', alt='Persona leyendo libro', style='width: 396px').m-auto

            .col-lg-8
              SlyderF(columnas="col-lg-6 col-xl-4")
                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/5.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Explicar las características de algo (describir).

                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/6.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Identificar los elementos principales de esas características (definir).

                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/7.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Reconocer las distintas categorías, grupos y subgrupos a los que pertenece algo (clasificar).

                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/8.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Descubrir semejanzas y diferencias entre dos cosas (comparar).

                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/9.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Llegar a una ley general a partir de ejemplos particulares (inducir).

                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/10.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Realizar operaciones lógicas para llegar a conclusiones (deducir).
                
                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/11.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Separar los distintos elementos que componen una estructura (analizar).

                .tarjeta.bg-9.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/tema1/12.svg', alt='').img100.m-auto
                  p.text-center.mb-0 Extraer lo más importante de un todo (sintetizar).



    .row.mt-4.bg-4.p-3.bg-r8
      .col-12
        ul.lista-ul--color
          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 Un resumen debe tener una extensión aproximada de una cuarta parte del texto original.

          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 Todas las ideas deberán estar completamente integradas, enlazadas y relacionadas. No puede ser una sucesión de ideas ni una simple enumeración.

          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 Debe ir de lo general e importante del tema a lo particular del mismo.

          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 Debe ir de lo fundamental a lo explicativo.

          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 En los resúmenes no podrán utilizarse guiones ni asteriscos. El punto seguido es el medio de enlace.

          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 La labor de resumir es posterior al subrayado y consiste en la unión de todas las ideas principales y secundarias.

          li.d-flex.align-items-start
            span.icono-img
            p.mb-0 Facilita la comprensión

    .row.align-items-center.mt-4
      .col-lg-8.mb-lg-0
        p.mt-4 La comprensión lectora efectiva requiere el desarrollo de habilidades cognitivas y la creación de condiciones favorables para el aprendizaje. A continuación, se describen los elementos fundamentales que facilitan este proceso:

        ul.lista-ul--color.bg-7.bg-r8.p-4
          li
            i.lista-ul__vineta
            | Tener un fin claro y específico.
          li
            i.lista-ul__vineta
            | Tener experiencia cognitiva con la ejecución de las operaciones del pensamiento.
          li
            i.lista-ul__vineta
            | Saber organizar y estructurar la información (orden secuencial de ideas).
          li
            i.lista-ul__vineta
            | Ejercitar el lenguaje como instrumento para expresar los pensamientos e ideas.
          li
            i.lista-ul__vineta
            | Ejercitar la voluntad y la perseverancia para someterse a los obstáculos los que opone la memoria al evocar lo aprendido.
          li
            i.lista-ul__vineta
            | Lo más importante son las ideas, no las palabras. Poner atención en captar las ideas es lo esencial.
          li
            i.lista-ul__vineta
            | Verificar las respuestas. Obtener una confirmación de lo que uno cree que captó.
          li
            i.lista-ul__vineta
            | Trabajar en grupo, desarrollar una conducta participativa, e intercambiar información para agilizar la dinámica del estudio, donde cada uno pasa a ser parte activa e imprescindible. (el grupo enseña a asumir responsabilidades).
          li
            i.lista-ul__vineta
            | Ejercitar para sacar el mayor número de ideas, porque mayores serán las posibilidades de retención.
          li
            i.lista-ul__vineta
            | Realizar al comienzo explicaciones cortas recalcando los puntos principales hasta ser capaz de expresar la idea en forma más compleja.

      .col-lg-4.d-none.d-lg-block
        figure.mb-4
          img(src='@/assets/curso/tema1/13.png', alt='Mujer leyendo', style='width: 293px')
        figure
          img(src='@/assets/curso/tema1/14.svg', alt='Persona estudiando', style='width: 293px')


    separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Estrategias de lectura

    p Para desarrollar la comprensión lectora de manera efectiva, es fundamental aplicar estrategias específicas que faciliten el procesamiento y la retención de la información. A continuación, se presentan las principales técnicas que optimizan este proceso:

    .row.bg-6
      .col-12
        .p-5
          .row.align-items-center.bg-5.bg-r8.p-4
            .col-12
              ol.lista-ol--cuadro
                li 
                  .lista-ol--cuadro__vineta
                    span.text-black A
                  | Si el texto es complejo:

              .row.p-2
                .col-lg-7
                  ul.lista-ul--color.bg-17.bg-r8.p-4
                    li.d-flex.align-items-start
                      i.lista-ul__vineta
                      p.mb-0 Consultar el texto con menor velocidad.

                    li.d-flex.align-items-start
                      i.lista-ul__vineta
                      p.mb-0 Repasar párrafo a párrafo para procesar las ideas.

                    li.d-flex.align-items-start
                      i.lista-ul__vineta
                      p.mb-0 Formar una "imagen mental" con las ideas.

                    li.d-flex.align-items-start
                      i.lista-ul__vineta
                      p.mb-0 Predecir contenidos a partir de los títulos y subtítulos.

                    li.d-flex.align-items-start
                      i.lista-ul__vineta
                      p.mb-0 Buscar significados de las palabras apoyándose en el contexto.

                    li.d-flex.align-items-start
                      i.lista-ul__vineta
                      p.mb-0 Incentivar el pensamiento relacionando la información que se recibe al consultar el texto con

                .col-lg-5
                  figure.d-lg-block.d-none
                    img(src='@/assets/curso/tema1/15.png', alt='Tres personas estudiando con laptop', style='width: 371px')


              ol.lista-ol--cuadro
                li 
                  .lista-ol--cuadro__vineta
                    span.text-black B
                  | Expresar con palabras propias o cambiar sustantivos y adjetivos, la idea del autor (parafrasear).

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black C
                  | Organizar la historia que se consulta. Tener un orden lógico.

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black D
                  | Buscar frases, palabras clave o "nexos" que sirven de señal para localizar las razones en que el autor fundamenta su tema (palabra que más se repite, nexos, etc.)

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black E
                  | Discutir sobre hechos y fenómenos que se perciben, formular hipótesis y crear estrategias para solucionarlas.

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black F
                  | Planificar acciones y evaluar las consecuencias.

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black G
                  | Utilizar definiciones, comparaciones, y clasificaciones, etc., en trabajos, conversaciones y exposiciones diarias.

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black H
                  | Explicar conceptos ya aprendidos.

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black I
                  | Crear analogías (imágenes).

                li 
                  .lista-ol--cuadro__vineta
                    span.text-black J
                  | Crear situaciones para poner en práctica lo aprendido. 



    separador
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Señales de organización textual

    p Los textos presentan señales que indican cómo está organizada la información y cómo se relacionan las ideas entre sí. Reconocer estas señales permite identificar la estructura del texto y facilita la comprensión de su contenido. Estas señales son:

    .row.justify-content-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.clr-paleYellow.p-4.text-center.bg-21
          .row.justify-content-center.mb-3
            .col-auto
              .circle-morado
                figure
                  img(src='@/assets/curso/tema1/16.svg', alt='Estructura lógica', style='width: 80px')
          h4.mb-0 Estructura lógica

      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.clr-paleYellow.p-4.text-center.bg-21
          .row.justify-content-center.mb-3
            .col-auto
              .circle-morado
                figure
                  img(src='@/assets/curso/tema1/17.svg', alt='Ideas generales', style='width: 80px')
          h4.mb-0 Ideas generales

      .col-lg-4
        .tarjeta.clr-paleYellow.p-4.text-center.bg-21
          .row.justify-content-center.mb-3
            .col-auto
              .circle-morado
                figure
                  img(src='@/assets/curso/tema1/18.svg', alt='Ideas principales', style='width: 80px')
          h4.mb-0 Ideas principales

    p.mb-4 Es fundamental reconocer cuál es la estructura lógica que el autor utiliza en la elaboración de un texto.

    // Segunda fila - 4 tarjetas azules con avatar
    .row.justify-content-center
      .col-lg-3.col-md-6.mb-4.mb-lg-0
        .tarjeta-avatar.h-100
          img(src='@/assets/curso/tema1/19.svg')
          .tarjeta.bg-2.shadow
            .p-4.pt-5
              p.text-center.mb-0 Dividir el tema por subtemas o partes diferentes.

      .col-lg-3.col-md-6.mb-4.mb-lg-0
        .tarjeta-avatar.h-100
          img(src='@/assets/curso/tema1/20.svg')
          .tarjeta.bg-2.shadow
            .p-4.pt-5
              p.text-center.mb-0 Utilizar una secuencia temporal. 
              p(style="color: #A4C2FF") Utilizar una secuencia temporal. Utilizar una secuencia temporal. 

      .col-lg-3.col-md-6.mb-4.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/21.svg')
          .tarjeta.bg-2.shadow
            .p-4.pt-5
              p.text-center.mb-0 Utilizar un procedimiento inductivo, es decir, de un hecho experimental, llegar a uno general y exponer una ley.

      .col-lg-3.col-md-6
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/22.svg')
          .tarjeta.bg-2.shadow
            .p-4.pt-5
              p.text-center.mb-0 Utilizar un procedimiento deductivo, es decir, de una norma o definición añadir argumentos que lo apoyan.


    p.mt-4 Los signos de puntuación cumplen funciones específicas que permiten identificar y jerarquizar las ideas dentro de un texto. Conocer estas funciones facilita la comprensión de la estructura del contenido:

    .row.mb-5.align-items-center
      .col-lg-8
        ul.lista-ul.mb-0.bg-4.p-4.bg-r8
          li
            span.icono-img
            p.mb-0 Cada párrafo contiene una idea principal.

          li
            span.icono-img
            p.mb-0 seguido marca ampliaciones o explicaciones de esa idea, es decir, son ideas secundarias.

          li
            span.icono-img
            p.mb-0 La coma (,) separa explicaciones que tienen el mismo valor, ejemplos y datos.

          li
            span.icono-img
            p.mb-0 El punto y coma (;) equivale a un punto, pero su relación con la oración anterior es más estrecha.

      .col-lg-4
        figure.d-lg-block.d-none
          img(src='@/assets/curso/tema1/23.png', alt='Mano escribiendo en documento', style='width: 100%')


    .titulo-tres.mt-5: h3 Identificar la idea principal y secundaria

    .row.mb-5
      .col-lg-3.mb-4.mb-lg-0
        figure.d-lg-block.d-none
          img(src='@/assets/curso/tema1/24.png', alt='Mujer leyendo sentada', style='width: 292px')

      .col-lg-9
        p.mb-3 El título más breve posible representa generalmente la idea principal. También es la respuesta a las preguntas: ¿de qué se habla? ¿Qué se dice de ello?

        p.mb-4 La idea principal es lo fundamental de la materia expuesta.

        .row.align-items-start.bg-7.p-3.bg-r8
          .col-lg-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/tema1/25.svg', alt='Icono puzzle', style='width: 100px').m-auto
          .col
            p.mb-0 Para identificar correctamente las ideas principales y secundarias, es fundamental conocer dos aspectos clave: la ubicación de la idea principal dentro del párrafo y las características de las frases secundarias que la complementan. A continuación, se desarrollan estos dos elementos:

    
    .row.mb-4.bg-17.bg-r8.p-4.justify-content-center

      h3 a) Localizar la idea principal

      p.mb-4 La idea principal puede ubicarse en diferentes posiciones dentro del párrafo:

      .col-lg-10
        .row
          .col-lg-7
            .row.justify-content-center
              .col-lg-4
                .crd.bg-7.bg-r8.p-4.text-center.h-100
                  figure.mb-2
                    img(src='@/assets/curso/tema1/26.svg', alt='Inicio párrafo', style='width: 80px').m-auto
                  p.mb-0
                    strong Al inicio del párrafo

              .col-lg-4.mt-lg-0.mt-4
                .crd.bg-7.bg-r8.p-4.text-center.h100
                  figure.mb-2
                    img(src='@/assets/curso/tema1/27.svg', alt='Parte central', style='width: 80px').m-auto
                  p.mb-0
                    strong En la parte central del párrafo

              .col-lg-4.mt-lg-0.mt-4
                .crd.bg-7.bg-r8.p-4.text-center.h-100
                  figure.mb-2
                    img(src='@/assets/curso/tema1/28.svg', alt='Final párrafo', style='width: 80px').m-auto
                  p.mb-0
                    strong Al final del párrafo

          .col-lg-5.mt-lg-0.mt-4
            .tarjeta.bg-8.p-4
              p.mb-0 Es fundamental comprender que cada párrafo constituye una unidad de pensamiento completa. En él, el autor desarrolla una idea específica mediante una o varias oraciones relacionadas entre sí. Los párrafos inician con sangría y finalizan con punto aparte.

      p.mt-4 Según la ubicación de la idea principal, se pueden identificar tres estructuras:

      .row.justify-content-center
        .col-lg-10
          .row.justify-content-center.mb-5
            .col-lg-4.mb-4.mb-lg-0
              .tarjeta.bg-12.p-4.h-100.text-center
                .row.justify-content-center.mb-4
                  .col-auto
                    .circle-verde
                      figure
                        img(src='@/assets/curso/tema1/29.svg', alt='Bombilla inicio', style='width: 80px')
                p.mb-0
                  strong Idea al inicio: 
                  | cuando la idea principal se encuentra al principio del párrafo, su identificación resulta directa, ya que el resto del párrafo generalmente ejemplifica esta idea inicial.

            .col-lg-4.mb-4.mb-lg-0
              .tarjeta.bg-12.p-4.h-100
                .row.justify-content-center.mb-4
                  .col-auto
                    .circle-verde
                      figure
                        img(src='@/assets/curso/tema1/30.svg', alt='Bombilla centro', style='width: 80px')
                p.mb-0.text-center
                  strong Idea en la parte central: 
                  | en este caso, el párrafo se divide en tres segmentos:
                ul.lista-ul--color.mt-3.mb-0
                  li.d-flex.align-items-start
                    i.lista-ul__vineta
                    p.mb-0 El primer segmento presenta una introducción o contexto que prepara al lector.
                  li.d-flex.align-items-start
                    i.lista-ul__vineta
                    p.mb-0 El segundo segmento contiene la idea principal.
                  li.d-flex.align-items-start
                    i.lista-ul__vineta
                    p.mb-0 El tercer segmento aclara, matiza o amplía la idea expresada en la parte central.

            .col-lg-4
              .tarjeta.bg-12.p-4.h-100.text-center
                .row.justify-content-center.mb-4
                  .col-auto
                    .circle-verde
                      figure
                        img(src='@/assets/curso/tema1/31.svg', alt='Bombilla final', style='width: 80px')
                p.mb-0
                  strong Idea al final: 
                  | cuando la idea principal se sitúa al final del párrafo, es necesario consultar el texto con especial atención. La oración que contiene la idea principal funciona como conclusión general de todo lo expuesto y constituye el punto central de la argumentación.

      p.mb-4 Es posible encontrar párrafos que contengan más de una idea principal, o algunos en los que ni siquiera aparezca la idea principal; estos últimos se denominan "párrafos de transición".

      .row.mb-4.bg-9.bg-r8.p-3
        .col-12
          h5.mb-3
            strong Estrategias para identificar la idea principal
          p Para reconocer la idea principal de un párrafo, se pueden aplicar las siguientes estrategias:

          ul.lista-ul--color
            li.d-flex.align-items-start
              span.icono-img2
              p.mb-0 Formular las preguntas: ¿De qué o de quién se habla? ¿Qué se dice de ello? La respuesta a estas preguntas es la idea principal.

            li.d-flex.align-items-start
              span.icono-img2
              p.mb-0 Determinar cuál es la palabra que más se repite dentro del párrafo.

            li.d-flex.align-items-start
              span.icono-img2
              p.mb-0 Verificar que la frase principal es imprescindible dentro del párrafo; si se quita, el párrafo aparecerá trunco e incompleto. Además, identificar que la frase donde se exprese la afirmación más amplia y abstracta será siempre la conclusión y el resumen de las demás.


    .row.mb-4.bg-13.bg-r8.p-3
      .col-12
        .row.align-items-center
          .col-lg-3
            h5.mb-3.bg-2.bg-r8.p-3
              strong b) Las frases secundarias

        p Para reconocer la idea principal de un párrafo, se pueden aplicar las siguientes estrategias:

        ul.lista-ul--color
          li.d-flex.align-items-start
            span.icono-img2
            p.mb-0 Formular las preguntas: ¿De qué o de quién se habla? ¿Qué se dice de ello? La respuesta a estas preguntas es la idea principal.

          li.d-flex.align-items-start
            span.icono-img2
            p.mb-0 Determinar cuál es la palabra que más se repite dentro del párrafo.

          li.d-flex.align-items-start
            span.icono-img2
            p.mb-0 Verificar que la frase principal es imprescindible dentro del párrafo; si se quita, el párrafo aparecerá trunco e incompleto. Además, identificar que la frase donde se exprese la afirmación más amplia y abstracta será siempre la conclusión y el resumen de las demás.


    separador
    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3 Técnica del subrayado

    p El subrayado es una técnica que consiste en destacar con una línea las ideas que se consideran fundamentales de la materia en estudio.

    p Su aplicación facilita el estudio, la retención y la confección de esquemas y/o resúmenes. Asimismo, hace del aprendizaje un proceso activo y comprometido, mejora la atención y permite que el repaso sea más corto y eficaz.

    .titulo-tres.mt-5: h3 Estrategias para aplicar la técnica del subrayado

    .row.mb-5.align-items-center
      .col-lg-8.mb-lg-0
        p.mb-4 Para subrayar de manera efectiva, es importante seguir ciertas pautas que optimicen el aprovechamiento de esta técnica:

        ul.lista-ul--color.mb-0.bg-8.bg-r8.p-4
          li.d-flex.align-items-start
            span.icono-img2
            p.mb-0 Realizar una lectura general o preliminar del texto y, después de una segunda lectura, proceder a subrayar.

          li.d-flex.align-items-start
            span.icono-img2
            p.mb-0 Subrayar únicamente palabras clave, que incluyen el verbo, el sustantivo y el adjetivo. Se debe evitar subrayar los conectores (lativos).

          li.d-flex.align-items-start
            span.icono-img2
            p.mb-0 Subrayar las ideas que correspondan a las preguntas clave para recuperar toda la información importante (antecedentes, características, definiciones, acciones, funciones, procesos, etc.)

      .col-lg-4
        figure.d-lg-block.d-none
          img(src='@/assets/curso/tema1/32.png', alt='Texto subrayado con marcador naranja', style='width: 292px')



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
