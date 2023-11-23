<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.pb-0.pb-md-0.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Computación en la nube

    .row.fondo-t1.align-items-center.py-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.justify-content-center.mb-4
            .col-lg-7.pt-lg-5.mb-2(data-aos="fade-right")
              p En el campo de la TI, el concepto de nube ya existía desde los años 90. Sin embargo, solo hasta el año 2006 fue cuando se popularizó el término, con la aparición del servicio EC2 de Amazon (Elastic Compute Cloud), el cual es un servicio web que se puede alquilar, pero con la característica que es escalable de acuerdo con las necesidades del usuario (AWS, 2021). Es decir, un servidor que se puede modificar en almacenamiento, poder de procesamiento, red, sistema operativo, entre otras cosas.
            .col-lg-5.col-8.mb-2(data-aos="fade-left")
              img(src='@/assets/curso/temas/t1/img.png', alt='')

          h5.mb-4(data-aos="fade") Entre las ventajas que se pueden destacar del #[em cloud computing] se encuentran las siguientes:

          .col-lg-6(data-aos="fade-down")
            ImagenInfografica.color-acento-botones
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/t1/img-infog.svg', alt='')          

              .tarjeta.bg-3.p-3(x="50.5%" y="4%")
                .h4.mb-2 Costos más favorables
                p.mb-0 No es necesario invertir en una gran infraestructura ni licencias que serán obsoletas con el paso del tiempo. Hay gran variedad de servicios que se pagan de forma mensual de acuerdo con el uso y que son acompañados muchas veces de otros servicios totalmente gratuitos.

              .tarjeta.bg-3.p-3(x="95%" y="49%")
                .h4.mb-2 Mayor velocidad
                p.mb-0 Debido a que son plataformas basadas y pensadas para la web.

              .tarjeta.bg-3.p-3(x="50.5%" y="96%")
                .h4.mb-2 Flexibilidad
                p.mb-0 Permite reasignar recursos sin dejar de prestar los servicios existentes y facilita los procesos largos de compra. El proceso de aprovisionamiento de recursos, dependiendo de su complejidad, puede realizarse en pocos minutos.
            
              .tarjeta.bg-3.p-3(x="5%" y="49%")
                .h4.mb-2 Acceso a la información
                p.mb-0 En cualquier momento y desde cualquier lugar en que se cuente con una conexión a internet.

      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
