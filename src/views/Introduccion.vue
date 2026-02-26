<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero(data-aos="flip-up")
        span
          i.fas.fa-info
      h1 Introducción

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/intro/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La comprensión lectora es una habilidad esencial para el éxito académico y profesional, ya que permite interpretar, analizar y evaluar la información de manera eficiente y crítica. A través de técnicas específicas de lectura, se fortalecen habilidades como identificar las ideas principales, reconocer los detalles que organizan los textos y desarrollar el pensamiento crítico.

    .bg-1
      .col-12 
        .p-5 
          .row.align-items-start.mt-4
            .col-lg-1.mb-lg-0.mb-4
              figure(data-aos="fade-down")
                img(src='@/assets/curso/intro/2.svg', alt='Icono de video', style='width: 100px').m-auto
            
            .col
              p Se presentan estrategias para comprender textos en tres etapas: entender lo que dice directamente, descubrir la información que no está escrita, pero se puede deducir, y reflexionar de manera crítica para relacionar el planteamiento de estas habilidades favorece una lectura activa que va más allá de un simple reconocimiento de palabras y que resulta en la vida académica, laboral y cotidiana.
              
              p Para comprender la importancia del contenido y los temas abordados, se recomienda acceder al siguiente video:
              
          .row.justify-content-center.align-items-center.mt-4           
            .col-lg-12
              figure(data-aos="fade-down")
                .video
                  iframe(width="560" height="315" src="https://www.youtube.com/embed/egQYZ4OQu1M?si=SF0ScWvn7akXtv94" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)



</template>

<script>
export default {
  name: 'Introduccion',
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
