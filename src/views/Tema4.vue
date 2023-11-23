<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Tipos de nube

    .mb-5(data-aos="fade-down")
      img(src="@/assets/curso/temas/t4/img.png", alt="")  

    p.mb-4(data-aos="fade") Dependiendo de quién es el propietario y el método de implementación de la infraestructura a ser utilizada, existen tres grandes tipos de nube, las cuales que se detallan a continuación:

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-8
        ImagenInfografica.color-acento-botones.tema-4.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/t4/img-infog.svg', alt='')          

          .tarjeta.color-acento-botones.p-3(x="17%" y="99%")
            .row
              .col-lg-3.col-4
                img(src="@/assets/curso/temas/t4/ico1.svg", alt="") 
              .col-lg-9
                .h5.mb-2 Nube privada
                p.mb-0 Se conoce como nube privada al aprovisionamiento de capacidades de cómputo, almacenamiento y de #[em networking] de manera local para consumo individual. En general, las instalaciones de tipo #[em on-premise] se incluyen dentro de la categoría de nubes privadas.

          .tarjeta.color-acento-botones.p-3(x="82%" y="99%")
            .row
              .col-lg-3.col-4
                img(src="@/assets/curso/temas/t4/ico2.svg", alt="") 
              .col-lg-9
                .h5.mb-2 Nube pública
                p Una nube es pública cuando todo el conjunto de recursos de infraestructura de TI, ajena al usuario final, se despliega para el consumo como servicios a través de internet, independientemente de si los recursos son asignados o no a los usuarios de forma privada.  Algunos proveedores de este tipo de nubes son:
                p.mb-0 Amazon Web Services (AWS), Google Cloud, IBM Cloud y Microsoft Azure.

          .tarjeta.color-acento-botones.p-3(x="50%" y="56%")
            .row
              .col-lg-3.col-4
                img(src="@/assets/curso/temas/t4/ico3.svg", alt="") 
              .col-lg-9
                .h5.mb-2 Nube híbrida
                p.mb-0 Una nube es híbrida cuando combina servicios de proveedores de nubes públicas con servicios de nubes privadas, las cuales  generalmente están conectadas mediantes redes de área local (LAN), de área amplia (WAN), redes privadas virtuales (VPN) o API.
        




</template>

<script>
export default {
  name: 'Tema4',
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
