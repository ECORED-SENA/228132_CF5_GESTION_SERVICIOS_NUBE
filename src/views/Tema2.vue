<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.pb-0.pb-md-0.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Tipos de servicios de computación en la nube

    p Es importante tener claridad sobre los tipos de servicio que se pueden ofrecer por medio de la computación en la nube, porque puede ayudar a tomar la decisión de migrar o no a este tipo de servicios o seguir trabajando con los mecanismos de aprovisionamiento tradicionales (Peña, 2021).

    h5.mb-4 Tipos de servicios de computación en la nube

    .row.fondo-t2.align-items-center.py-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .fondo-slider.p-4.mb-4(data-aos="fade-down")
            SlyderA(tipo="b")
              .row.justify-content-evenly.align-items-center
                .col-md-6.mb-4.mb-md-0
                  h2 Servicios de almacenamiento
                  p Este tipo de servicios buscan garantizar la disponibilidad de la información en cualquier momento, pues va más allá de brindar grandes cantidades de almacenamiento. Establecen mecanismo como, por ejemplo, la replicación en diferentes ubicaciones geográficas, de forma que se pueda trabajar y acceder a los datos, incluso en escenarios complejos, dando gran tolerancia a fallos.
                .col-md-3
                  img(src="@/assets/curso/temas/t2/slider-img1.png", alt="")
              
              .row.justify-content-evenly.align-items-center
                .col-md-6.mb-4.mb-md-0
                  h2 Servicios de cómputo
                  p Este tipo de servicios da soporte a la capa de procesamiento de las aplicaciones, es decir, el usuario determinará entre características como: cantidades de núcleos de procesamiento y memoria requerida para el correcto funcionamiento de las aplicaciones y el proveedor del servicio se encarga de provisionar y mantenerlos disponibles para el usuario cuando se requiera.
                .col-md-3
                  img(src="@/assets/curso/temas/t2/slider-img2.png", alt="")

              .row.justify-content-evenly.align-items-center
                .col-md-6.mb-4.mb-md-0
                  h2 Servicios de red
                  p Estos están orientados a la selección de herramientas que permiten controlar la comunicación entre los diferentes servicios y la gestión de la seguridad de los recursos.
                .col-md-3
                  img(src="@/assets/curso/temas/t2/slider-img1.png", alt="")


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
