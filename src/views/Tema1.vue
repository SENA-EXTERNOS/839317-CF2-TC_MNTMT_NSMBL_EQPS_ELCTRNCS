<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.cblanco 1
      h1 Identificación e interpretación de los diferentes elementos presentes en un plano esquemático

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t1/f1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 A continuación, se presentan algunos conceptos que le permitirán comprender e interpretar los elementos, estructuras y tipos de planos esquemáticos presentes en los diferentes equipos electrónicos. Estos conocimientos facilitarán la identificación de los diversos componentes electrónicos para su caracterización y posterior medición.
        
    Separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Planos esquemáticos

    .row.justify-content-end.align-items-center.mb-4
      .col-md-6
        .tarjeta.tarjeta--gris(style='padding-right: 40%;margin-right:-40%')
          .p-4
            p.mb-0 
      .col-md-5
        figure
          img(src="@/assets/curso/temas/t1/f2.svg", alt="Computadora y chip")
    
    h3 Simbología

    p 

    .bg1.my-4
      SlyderF(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f3.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f4.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f5.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f6.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f7.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f8.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f9.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f10.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f11.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 
        .tarjeta.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f12.png' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center 



</template>

<script>
import Separador from 'ecored-base-pkg/src/components/Separador.vue'
export default {
  name: 'Tema1',
  components: { Separador },
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
