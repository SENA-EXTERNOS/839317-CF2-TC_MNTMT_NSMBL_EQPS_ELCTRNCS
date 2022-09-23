<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.cblanco 2
      h1 Comprobación del correcto funcionamiento de los circuitos de acuerdo con procedimientos técnicos normativos

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos='flip-right')
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t2/f1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Para realizar una comprobación adecuada del funcionamiento de los circuitos electrónicos y eléctricos se debe tener en cuenta definiciones y leyes presentes en estos dispositivos. A continuación, se presentan de manera discriminada cada una de ellas.

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido
      h2 Variables eléctricas y electrónicas

    p Conocer la definición de las principales variables y principios en los circuitos electrónicos es de suma importancia para la caracterización de las piezas o elementos a intervenir.

    PasosA.color-acento-contenido.mb-5(tipo="n")
      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Corriente
          p La corriente se define como el flujo de carga eléctrica que pasa por dos puntos de un circuito en un determinado instante de tiempo. Mileaf, H. (2002) afirma que la corriente se produce, cuando en un conductor hay muchos electrones libres que se mueven en la misma dirección. Dependiendo de su comportamiento en el tempo se clasifican en corriente continua o alterna. 
          p La dirección del flujo de carga en un circuito determina la polaridad, la cual puede ser positiva o negativa, en el caso de la corriente alterna esta polaridad cambia con el tiempo. 
          p La corriente continua mantiene una de las dos polaridades fijas.
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f2.svg", alt="imagen relacionada")
      .row.align-items-center.justify-content-center
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f3.svg", alt="imagen relacionada")
        .col-md-7
          h4 Voltaje
          p El voltaje o tensión es la diferencia de potencial eléctrico que existe entre dos puntos de un circuito. Esta variable nos dice que tan difícil es llevar un electrón de un punto determinado a otro. En otras palabras: “La carga eléctrica que adquiere un objeto se llama potencial eléctrico, debido a que los electrones desplazados acumulan energía potencial que se puede utilizar para mover a otros electrones. Puesto que se necesitan dos cargas para completar un circuito, la diferencia de potencial entre estas dos cargas es lo que proporciona la fuerza eléctrica.” (Mileaf, H., 2002). Al igual que en el caso anterior el voltaje se divide en dos grupos. Voltaje continuo, se caracteriza por tener una polaridad fija. Voltaje alterno, se caracteriza por tener una polaridad cambiante en el tiempo.
      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Potencia
          p La potencia eléctrica dentro de un circuito mide la cantidad de energía (recurso eléctrico) suministrada o usada por un elemento, la potencia es la cantidad de trabajo que una carga puede llevar a cabo en cierta cantidad estándar de tiempo, generalmente un segundo. (Mileaf, H., 2002). Ya que la energía no puede ser destruida algunos elementos disipan calor, este motivo obliga a tener cuidado a la hora de manipular piezas electrónicas.
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f4.svg", alt="imagen relacionada")
      .row.align-items-center.justify-content-center
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f5.svg", alt="imagen relacionada")
        .col-md-7
          h4 Resistencia
          p La resistencia eléctrica cuantifica el nivel oposición al flujo de corriente eléctrica que tiene un material o elemento; los materiales de baja conductancia se oponen o resisten al flujo de la corriente eléctrica. (Mileaf, H., 2002).
      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Continuidad
          p Colocar texto explicativo o información correspondiente
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f6.svg", alt="imagen relacionada")
      .row.align-items-center.justify-content-center
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f7.svg", alt="imagen relacionada")
        .col-md-7
          h4 Ley de 
            em Ohm
          p La ley de ohm establece la relación que existe entre la tensión, la corriente y la resistencia eléctrica. Es parte fundamental en la interpretación de circuitos electrónicos y se define como:
          p I = VR
          p Donde:
          p I = corriente eléctrica.
          p R = resistencia eléctrica.
          p V = al voltaje o tensión eléctrica.
      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Ley de 
            em Watt
          p La ley de watt establece la relación que existe entre la potencia consumida, la tensión y la corriente eléctrica de una carga, se define como         :
          p P = V  *  I
          p Donde P es la potencia.
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f8.svg", alt="imagen relacionada")
      .row.align-items-center.justify-content-center
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f9.svg", alt="imagen relacionada")
        .col-md-7
          h4 Semiconductores
          p Los semiconductores son todos los materiales cuyo estado depende de factores físicos como la temperatura, presión campos magnéticos, etc. Es decir, son todos aquellos materiales que se comportan como aislantes o conductores dependiendo de factores externos. Más precisamente puesto que los conductores tienen sus capas de valencia llenas a menos de la mitad, y los aisladores tienen las suyas llenas a más de, la mitad, las substancias que tienen átomos con cuatro electrones de valencia reciben el nombre de semiconductores. (Mileaf, H., 2002).
      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Diodos
          p Este componente electrónico es un semiconductor que se comporta como un interruptor que se activa mediante unas condiciones específicas y permiten el paso de corriente en una única dirección.
        .col-md-5
          figure
            img(src="@/assets/curso/temas/t2/f10.svg", alt="imagen relacionada")
      .row.align-items-center.justify-content-center
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f11.png", alt="imagen relacionada")
        .col-md-7.text-left
          h4 Ley de 
            em Kirchoff
          p Esta ley establece el comportamiento que tiene la corriente y el voltaje en los nodos y mallas de un circuito:
          ol.lista-ol--cuadro
            li.text-small 
              .lista-ol--cuadro__vineta
                span.cblanco a
              | Ley de corriente de Kirchhoff.
              br 
              | Esta ley establece que la sumatoria de corrientes entrantes a un nodo debe ser igual a la sumatoria de corrientes salientes del mismo nodo. 
            li.text-small 
              .lista-ol--cuadro__vineta
                span.cblanco b
              | Ley de voltaje de Kirchhoff.
              br
              | Esta ley establece que la sumatoria de voltajes en una trayectoria cerrada o malla de un circuito debe ser igual a cero

      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Ley de 
            em Coulomb
          p La ley de Coulomb establece que la fuerza eléctrica de atracción o repulsión entre dos cargas en reposo es directamente proporcional al producto de las cargas y a la constante de Coulomb e inversamente proporcional a la distancia de separación al cuadrado. En otras palabras la intensidad de las líneas electrostáticas de fuerza es inversamente proporcional al cuadrado de la distancia entre las cargas (Mileaf, H., 2002).
          figure
            img(src="@/assets/curso/temas/t2/coulomb.jpg", alt="imagen relacionada", style='width:120px !important')
          p Donde:
          p K=Constante de Coulomb 
          p Q1=Carga 1
          p Q2=Carga 2
          p r= distancia de separación de las cargas.
          p F=Fuerza eléctrica.
        .col-md-5
          figure
            img(src="@/assets/curso/temas/t2/f12.png", alt="imagen relacionada")
      .row.align-items-center.justify-content-center
        .col-md-5(data-aos='fade-left')
          figure
            img(src="@/assets/curso/temas/t2/f13.png", alt="imagen relacionada")
        .col-md-7.text-left
          h4 Ley de 
            em Faraday
          p La ley de Faraday establece la relación que existe entre un campo magnético variante de una superficie y el campo eléctrico producido por estas variaciones. La ley de Faraday establece:
          figure
            img(src="@/assets/curso/temas/t2/faraday1.jpg", alt="imagen relacionada", style='width:120px !important')
          p Donde:
          p E=Fuerza electromotriz.
          p.d-inline 
            img.text-left(src="@/assets/curso/temas/t2/faraday2.jpg", alt="", style='width:60px !important') 
            | = A la razón de cambio del flujo magnético.
      .row.align-items-center.justify-content-center
        .col-md-7.order-sm-last.order-md-first
          h4 Estática
          p La estática se define como el exceso de carga en movimiento acumulada por un cuerpo u objeto. Cuando este excedente supera el límite de retención del elemento provoca una descarga eléctrica que puede llegar a ocasionar accidentes o averías en los equipos.
        .col-md-5
          figure
            img(src="@/assets/curso/temas/t2/f14.png", alt="imagen relacionada")

    Separador

    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2 Gestión de documentación 

    p Gestionar en documentos todos los procedimientos realizados a un equipo permite agendar todos los mantenimientos preventivos y correctivos futuros, consolida un historial de intervenciones que pueden guiar a futuros procedimientos con características similares a pasadas revisiones.

    .bg5
      .row.justify-content-around.align-items-center.mb-3
        .col-md-7
          h3 Gestión de documentación
          p Gestionar en documentos todos los procedimientos realizados a un equipo permite agendar todos los mantenimientos preventivos y correctivos futuros, consolida un historial de intervenciones que pueden guiar a futuros procedimientos con características similares a pasadas revisiones.
        .col-md-5.order-sm-first.order-md-last
          figure
            img(src="@/assets/curso/temas/t2/f15.svg", alt="imagen relacionada")
      .row.justify-content-around.align-items-center.mb-3
        .col-md-2
          figure
            img(src="@/assets/curso/temas/t2/f16.svg", alt="imagen relacionada")
        .col-md-8.tarjeta.tarjeta--gris
          .p-4
            h5 Protocolo de pruebas 
            p Para realizarlas pruebas de cada uno de los equipos a intervenir se debe seguir las recomendaciones brindadas por el manual de usuario del fabricante y de las normas asociadas al tipo de dispositivo que se esté manipulando.
      .row.justify-content-around.align-items-center.mb-3
        .col-md-8.tarjeta.tarjeta--gris
          .p-4
            h5 Registro y reporte de resultados 
            p Con las pruebas realizadas se debe generar una bitácora de cada uno de los procedimientos realizados junto con sus respectivos resultados. Este paso garantiza un historial de los procedimientos hechos a los equipos y puede ayudar en caso de accidentes a determinar las causas de este, servir de guía en futuras intervenciones y tener control sobre los materiales o equipos usados en cada uno de los diagnósticos.
        .col-md-2
          figure
            img(src="@/assets/curso/temas/t2/f17.svg", alt="imagen relacionada")
      .row.justify-content-around.align-items-center.mb-3
        .col-md-2
          figure
            img(src="@/assets/curso/temas/t2/f18.svg", alt="imagen relacionada")
        .col-md-8.tarjeta.tarjeta--gris
          .p-4
            h5 Normas técnicas
            p Con el fin de mantenerla integridad y la funcionalidad de los equipos se debe caracterizar cada uno de los dispositivos electrónicos para saber qué tipo de requerimientos se deben seguir.
            p La norma de INCONTEC 60601-1 es usada comúnmente en equipos electromédicos para garantizar la seguridad el paciente, del operador y del entorno.
      .row.justify-content-around.align-items-center
        .col-md-7
          h3 Lineamientos de calidad
          p Los lineamientos de calidad son aquellas normas establecidas a nivel internacional que deben seguir cada uno de los diseños electrónicos. Busca garantizar por medio de pruebas que cada uno de los equipos electrónicos cumplan con los requerimientos necesarios en cada una de las normas establecidas. La IEC se encarga de establecer normas internacionales para todas las tecnologías eléctricas, electrónicas y áreas afines.
          p Adicionalmente, cada uno de los países tienen normas que se deben adjuntar en cada una de las pruebas para mantener la seguridad de todos los agentes involucrados en el uso de los equipos. 
        .col-md-5.order-sm-first.order-md-last
          figure
            img(src="@/assets/curso/temas/t2/f19.svg", alt="imagen relacionada")

    Separador

    #t_2_3.titulo-segundo.color-acento-contenido
      h2 2.3 Protocolo de pruebas

    p Una de las funciones del personal de mantenimiento es evitar que las fallas se presenten o se prolonguen por demasiado tiempo, generando gastos operacionales adicionales a los previstos. Es por esto, por lo que se debe realizar un procedimiento adecuado para la localización de la o las fallas existentes en los equipos electrónicos.

    .tarjeta.tarjeta--gris.p-4.bgslide2
      PasosB.color-primario
        .row.justify-content-between(titulo="A")
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f20.svg', alt='imagen relacionada')
          .col-md-7.text-white
            h3 Técnica de caza fallas
            p La técnica caza fallas trata de establecer una secuencia lógica de las posibles fallas de un equipo. 
            p Para realizar este procedimiento se busca inspeccionar desde la causa más simple a la más compleja, todo esto en pro de reducir el tiempo de inactividad del equipo. Este procedimiento se conoce como Troubleshooting
        .row.justify-content-between(titulo="B")
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f21.svg', alt='imagen relacionada')
          .col-md-7.text-white
            h3 Listado de errores
            p Realizar un listado de cada uno de los errores encontrados o descartados es de suma importancia para evitar la redundancia en las intervenciones y en la focalización de las fallas.
        .row.justify-content-between(titulo="C")
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f22.svg', alt='imagen relacionada')
          .col-md-7.text-white
            h3 Reporte de diagnóstico
            p Una vez finalizada las pruebas de los equipos se debe generar un reporte con todos los procedimientos realizados, las fallas encontradas, los elementos reemplazados y una descripción de las observaciones de los técnicos que intervinieron. 
            p Toda esta información guiará a los profesionales en futuras intervenciones.

    Separador

    #t_2_4.titulo-segundo.color-acento-contenido
      h2 2.4 Normativa de seguridad y salud en el trabajo

    p Las normativas de seguridad y salud en el trabajo tienen como objetivo establecer reglas, rutas y pautas que se deben seguir dentro de las instalaciones laborales con el fin de evitar o reducir accidentes personales o comprometer la integridad de los equipos.

    .tarjeta.tarjeta--azul.p-4.bgslide1(data-aos='fade-left')
      SlyderA(tipo="b")
        .row.align-items-center.justify-content-between
          .col-md-7.mb-4.mb-md-0
            h4 Tipos de equipos
            p Los equipos de protección personal (EPP) tienen la función de proteger al usuario de accidentes o riesgos para la salud. De acuerdo con el área de protección los EPP se dividen en los siguientes grupos: protecciones oculares, cabeza y cuello, oídos, manos y brazos, pies y piernas, pulmones, cuerpo.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f23.png', alt='Texto que describa la imagen')
        .row.align-items-center.justify-content-between
          .col-md-7.mb-4.mb-md-0
            h4 Tipos de elementos
            p De acuerdo con el tipo de equipos de protección personal, se tiene una amplia gama de elementos que cumplen con su respectivo objetivo, los cuales se deben seleccionar dependiendo de la actividad a desarrollar. Dentro del área de mantenimiento de equipos electrónicos se tienen comúnmente los siguientes elementos: guantes antiestáticos, pulseras antiestáticas, tapabocas, botas aislantes, gafas de protección, casco y overol.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f24.png', alt='Texto que describa la imagen')
        .row.align-items-center.justify-content-between
          .col-md-7.mb-4.mb-md-0
            h4 Herramientas
            p Cada una de las herramientas que se van a usar dentro del laboratorio o área laboral tienen unos manuales de uso lo cuales se deben seguir para evitar los malos resultados o los accidentes. Además, se debe seguir algunas recomendaciones antes de manipular cada uno de los equipo y herramientas: realizar una inspección visual para verificar el estado de las herramientas, realizar pruebas de control para verificar la calidad de las mediciones, no manipular ningún elemento si ha consumido alguna clase de bebida alcohólica, droga o medicamentos con fuertes reacciones, no usar prendas mojadas, siempre estar bajo la supervisión del personal más calificado para la intervención a realizar.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f25.png', alt='Texto que describa la imagen')
        .row.align-items-center.justify-content-between
          .col-md-7.mb-4.mb-md-0
            h4 Riesgo eléctrico
            p El riesgo eléctrico es uno de los accidentes laborales más comunes en la manipulación de equipos electrónicos, se produce en ocasiones como resultado de la estática, pero también es producto del contacto de una extremidad con conductores o conexiones de circuitos electrónicos. Dependiendo de la magnitud y naturaleza de la corriente y voltaje puede ocasionar lesiones o incluso la muerte. 
            p Se debe señalizar en todo momento con letreros o con cualquier tipo de advertencia aquellos componentes propensos a provocar descargar eléctricas para evitar accidentes laborales.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f26.png', alt='Texto que describa la imagen')
        .row.align-items-center.justify-content-between
          .col-md-7.mb-4.mb-md-0
            h4 Puesto de trabajo
            p Es importante la identificación de riesgos laborales en el área de trabajo para señalizarlos y mantener un orden adecuado de cada una de las piezas que estén en el proceso de diagnóstico en conjunto con las herramientas y equipos evitan lesiones personales.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t2/f27.png', alt='Texto que describa la imagen')

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
