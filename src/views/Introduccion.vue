<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info.cblanco
      h1 Introducción

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7
        p 
        p 
      .col-md-5
        figure
          img(src="@/assets/curso/temas/f1.svg", alt="imagen relacionada")

    figure
      .video
        iframe(width='560' height='315' src='https://www.youtube.com/embed/jASywqOHrQM' title='YouTube video player' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen='allowfullscreen')

    
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
