<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-sexto.color-acento-botones.mb-4
      h3 Mantenimiento y ensamble de equipos electrónicos
      span Síntesis: descripción y funcionamiento de equipos electrónicos.

    p A lo largo de todo el componente formativo se trataron temas importantes para la interpretación de circuitos electrónicos por medio de sus características, identificación de elementos comunes dentro de un diseño y los conocimientos para la puesta en marcha de motores electrónicos. Se cubrieron contenidos asociados a las variables comunes a los cuales un profesional se enfrentará a la hora de aplicar los conocimientos, factores a tener en cuenta en la redacción de informes de diagnóstico y las herramientas y equipos necesarios para la intervención de dispositivos electrónicos en conjunto con las reglas o consideraciones a tener en cuenta en el momento de su manipulación.

    .titulo-sexto.color-acento-contenido.mb-4
      p.mb-0 
        b Figura 1. 
        | Descripción y funcionamiento de equipos electrónicos

    .row.justify-content-center.tarjeta
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
