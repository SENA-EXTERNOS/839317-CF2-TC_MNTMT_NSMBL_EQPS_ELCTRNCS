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
        p Apreciado aprendiz, sea bienvenido a este momento de aprendizaje orientado a la descripción y funcionamiento de equipos electrónicos. La descripción de planos esquemáticos y la interpretación de los componentes y variables asociadas a un equipo electrónico resulta de gran importancia a la hora de establecer las pruebas o procedimientos a realizar a futuro. Esto pues, son las responsables de establecer qué tipo de herramientas, técnicas o rangos se deben tener en cuenta en cada una de las fases del mantenimiento y reparación de equipos electrónicos.
        p Antes de empezar, se sugiere revisar el siguiente video donde podrá identificar el contexto de aprendizaje.

      .col-md-5(data-aos='fade-left')
        figure
          img(src="@/assets/curso/temas/f1.svg", alt="imagen relacionada")

    figure
      .video
        iframe(width='560' height='315' src='https://www.youtube.com/embed/2L91WMqw96A' title='YouTube video player' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen='allowfullscreen')

    
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
