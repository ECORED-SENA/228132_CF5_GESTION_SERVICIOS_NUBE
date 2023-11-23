<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Modelos de servicios de la computación en la nube

    figure.mb-5(data-aos="fade-down")
      img(src="@/assets/curso/temas/t3/img.png", alt="")  

    p(data-aos="fade") Dependiendo de los proveedores seleccionados para servicios de computación en la nube, se pueden generar diferentes responsabilidades por parte del proveedor y el usuario (Peña, 2019). Lo anterior permite diferenciar modelos de servicio que se describen a continuación.
    
    Separador


    // 3.1
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.1. Infraestructura como servicio (Iaas)

    .row.mb-4
      .col-lg-9.mb-2(data-aos="fade-right")
        p Este modelo es conocido como servicios de infraestructura en la nube y permite que  el usuario se encargue de la administración de los sistemas operativos, las aplicaciones, los datos, el #[em middleware] y todos los elementos que en este se despliega; por otra parte, el proveedor del servicio se encarga del soporte de la infraestructura que da soporte al  sistema operativo montado por el usuario.
      .col-lg-3.mb-2(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/img2.png', alt='')   

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-acento-contenido.titulo-img
          p.mb-0 #[b Figura 1.] Administración de componentes  en IaaS
        .bg-1.br-19.p-4.p-lg-5  
          figure
            img(src='@/assets/curso/temas/t3/fig1.svg', alt='Elementos de infraestructura laaS que administra el usuario y el proveedor.')   


    Separador


    // 3.2
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.2.	Plataforma como servicio (PaaS)

    .row.mb-4
      .col-lg-9.mb-2(data-aos="fade-right")
        p En esta categoría, el proveedor de servicios ofrece una plataforma como una solución integrada o servicio a través de Internet, según la lista para el consumo por parte del usuario. El proveedor se encarga de gestionar toda la infraestructura referente al #[em hardware] y al sistema operativo sobre el que se despliega la plataforma mientras el usuario solo es responsable de la administración y consumo de esta, logrando el desarrollo, ejecución y gestión de sus propias aplicaciones. Por lo anterior, es el modelo ideal para desarrolladores de #[em software] porque solo necesita un entorno para el desarrollo y ejecución del código sin necesidad de preocuparse de otros procesos. A continuación, se relaciona un ejemplo de PaaS es #[em Firebase]:
      .col-lg-3.mb-2(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/img3.png', alt='')   

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-acento-contenido.titulo-img
          p.mb-0 #[b Figura 2.] Administración de componentes en PaaS
        .bg-1.br-19.p-4.p-lg-5 
          figure
            img(src='@/assets/curso/temas/t3/fig2.svg', alt='Elementos de plataforma PaaS que administra el usuario y el proveedor.') 


    Separador


    // 3.3
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.3.	#[em Software] como servicio (SaaS)

    .row.mb-4
      .col-lg-9.mb-2(data-aos="fade-right")
        p En este modelo el proveedor se encarga de la infraestructura, sistemas operativos y plataformas tecnológicas que dan soporte a servicios de #[em software] que son expuestos para el consumo por parte de los usuarios. Ejemplos de este tipo de modelo de servicios son: Facebook, Google Docs, Microsoft Office 365.
      .col-lg-3.mb-2(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/img4.png', alt='')   

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-acento-contenido.titulo-img
          p.mb-0 #[b Figura 3.] Administración de componentes en SaaS
        .bg-1.br-19.p-4.p-lg-5 
          figure
            img(src='@/assets/curso/temas/t3/fig3.svg', alt='Elementos de administración de SaaS que administra el proveedor.') 


    Separador


    // 3.4
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.4.	Diferencias entre IaaS, PaaS y SaaS     

    .row.mb-4
      .col-lg-7.mb-2(data-aos="fade-right")
        p La selección de los modelos de servicio depende finalmente de las necesidades de la empresa o de los profesionales encargados de la toma de decisiones respecto al proceso de aprovisionamiento de la infraestructura dentro de la organización. Sin embargo, se debe tener en cuenta que tanto los modelos PaaS y SaaS se montan sobre una IaaS.
        p Según lo compartido en los puntos anteriores, la principal diferencia entre un modelo y otro viene determinada por la responsabilidad de los usuarios y proveedores sobre el proceso de mantenimiento y soporte, en segundo lugar están los aspectos de seguridad. En un modelo IaaS, el usuario es responsable de la seguridad de las aplicaciones instaladas mientras que en modelos SaaS y PaaS, la seguridad recae sobre el proveedor del servicio.
        h5 En la tabla 1 se comparte  un ejemplo de los posibles tipos de roles involucrados con cada una de las modelos y algunos ejemplos de aplicaciones. 
      .col-lg-5.mb-2(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/img5.png', alt='') 


    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          p.mb-0 #[b Tabla 1.] Modelos de servicios de computación en la nube
        .tabla-b.color-acento-botones
          table
            thead.tabla-b__header
              tr
                td 
                  h4.mb-0 Modelo de Servicio
                td 
                  h4.mb-0 Roles relacionados
                td 
                  h4.mb-0 Ejemplo de aplicaciones  
            tbody.text-center
              tr.bg-2
                td SaaS
                td.b-table Usuarios finales
                td Office 365, Google WorkSpace (G-Suite), WordPress.
              tr.bg-3
                td PaaS
                td.b-table Desarrolladores de #[em Software]
                td Firebase, SAP Cloud Platform, Google App Engine.
              tr.bg-2
                td IaaS
                td.b-table Administradores de TI
                td Amazon Web Services (AWS), Microsoft Azure, Google Cloud.
        


</template>

<script>
export default {
  name: 'Tema3',
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
