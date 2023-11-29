<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.align-items-center.justify-content-center(data-aos="fade-down")
      .col-12
        img(src="@/assets/curso/temas/intro/img.png", alt="")
      .col-lg-11.mb-5
        .bg-1.bx-sh1.br-10.p-3.px-4.mt-n3
          p.mb-0 Este componente formativo muestra las generalidades relacionadas con una forma de dar solución al problema del alistamiento tecnológico, el cual es muy usado actualmente en la industria: #[b la computación en la nube]. En el siguiente video, de manera genérica, se amplía un poco más sobre esta temática. 

    figure(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/mqmufUhhriA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Planificación y configuración de comunicación sobre VoIP



</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
