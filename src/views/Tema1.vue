<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(style='overflow:hidden')
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.cblanco 1
      h1 Identificación e interpretación de los diferentes elementos presentes en un plano esquemático

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos='flip-right')
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
        .tarjeta.tarjeta--gris(style='padding-right: 30%;margin-right:-30%')
          .p-4
            p.mb-0 Los diagramas o planos esquemáticos son mapas que indican el montaje y el funcionamiento de los circuitos electrónicos. Gracias al entendimiento general del dispositivo electrónico que proporciona esta representación gráfica son ampliamente usados en la construcción, depuración y mantenimiento de equipos electrónicos. Por lo anterior, es de suma importancia ser capaces de identificar todos los elementos presentes en un plano esquemático.
      .col-md-5
        figure(data-aos='fade-left')
          img(src="@/assets/curso/temas/t1/f2.svg", alt="Computadora y chip")
    
    h3 Simbología

    p La simbología dentro de los planos esquemáticos ayuda a diferenciar los distintos componentes electrónicos, debido a esto se debe aprender a identificar cada uno de los símbolos presentes en este tipo de representación. A continuación, se presentan algunos de ellos.

    .bg1.my-4(data-aos='fade-down')
      SlyderF(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f3.png' alt='Condensadores o capacitores')
          h2.text-center Condensadores o capacitadores
          p.text-center.text-small Este tipo de elemento se caracteriza por almacenar energía a través de un campo eléctrico, Mileaf, H. (2002) lo define como propiedad de un circuito eléctrico, que le permite almacenar energía eléctrica por medio de un campo electrostático y liberar esta energía posteriormente”. Se representa por medio de una letra C, no posee continuidad y su unidad de medida es el faradio. Además, dependiendo del tipo de condensador este puede o no tener polaridad.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f4.png' alt='Bobinas')
          h2.text-center Bobinas
          p.text-center.text-small Al igual que los capacitores, las bobinas o inductores almacenan energía con la diferencia que estos elementos lo hacen mediante un campo magnético, Mileaf, H. (2002) lo define como: “La inductancia es la propiedad de un circuito eléctrico que se opone a cualquier cambio de corriente en el circuito. Se representan por una letra L, su unidad de medida es el Henrio y se caracterizan por poseer conductividad.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f5.png' alt='Resistencia o resistores')
          h2.text-center Resistencia o resistores
          p.text-center.text-small Este tipo de elementos tiene la función de oponerse al paso de la corriente, carecen de polaridad, se representan por medio de una letra R y su unidad de medida son los ohmios.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f6.png' alt='Termistores')
          h2.text-center Termistores
          p.text-center.text-small Los termistores son elementos, y al igual que los resistores, tiene la capacidad de oponerse al paso de la corriente, con la particularidad que su nivel de resistencia depende de la temperatura; se representan con la letra T, su unidad de medida es el ohmio y, dependiendo de si su resistencia es inversa o directamente proporcional a la temperatura se clasifican en NTC o PTC respectivamente.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f7.png' alt='Diodos')
          h2.text-center Diodos
          p.text-center.text-small Los diodos son elementos semiconductores que se caracterizan por oponerse al paso de corriente eléctrica en un sentido, gracias a esto pueden resistir o controlar la corriente dependiendo de la dirección del flujo eléctrico. Se representan por medio de la letra D y su polarización puede ser directa o inversa.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f8.png' alt='Transistores')
          h2.text-center Transistores
          p.text-center.text-small Este componente electrónico es un semiconductor capaz de entregar una señal de salida a partir de una señal de entrada, de acuerdo con el tipo de transistor esta señal de salida puede ser una amplificación, oscilación o rectificación de la señal entrante. Se representa con la letra Q y sus terminales se denomina base, emisor y colector.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f9.png' alt='Circuitos integrados')
          h2.text-center Circuitos integrados
          p.text-center.text-small Los circuitos integrados o IC, por sus siglas en inglés, son chips o microchips presentes en los diferentes circuitos electrónicos, poseen un encapsulado y en su interior están compuestos por miles o millones de transistores. Dependiendo de la referencia del IC y del fabricante podremos acceder a su hoja de datos para conocer los detalles de su estructura, composición y función dentro de un circuito electrónico.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f10.png' alt='Tierra')
          h2.text-center Tierra
          p.text-center.text-small Este símbolo denota el punto de referencia del plano o diagrama esquemático de un circuito electrónico.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f11.png' alt='Cables')
          h2.text-center Cables
          p.text-center.text-small Este símbolo nos indica las conexiones que existen entre los diferentes elementos de un plano esquemático.
        .tarjeta.color-secundario.p-4(style='height:535px')
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/t1/f12.png' alt='Fuentes de alimentación')
          h2.text-center Fuentes de alimentación
          p.text-center.text-small Este tipo de elementos se encargan de suministrar energía eléctrica a todo el sistema, dependiendo de su naturaleza podemos encontrar fuentes de tensión y corriente. Además, también podemos encontrar fuentes de tipo alterna o continua.

    h3 Tipos, características y especificaciones
    
    p Además de poder identificar de forma correcta los elementos presentes en los planos esquemáticos, es importante conocer los tipos y características de los diferentes diagramas circuitales; información que será de utilidad a la hora de diseñar estos diagramas, caracterizarlos o interpretarlos.
    p A continuación, se presentan los tipos, características y especificaciones de los diagramas circuitales.

    TabsB.color-acento-botones.mb-4(data-aos='fade-left')
      .p-4.p-md-5(titulo="Esquemas topográficos" :icono="require('@/assets/curso/temas/t1/f13.svg')")
        .row
          .col-md-6.mb-4.mb-md-0
            h4 Esquemas topográficos
            p Este tipo de esquemático se caracteriza por realizar un diagrama circuital, teniendo en cuenta el lugar en donde se realizará la instalación de los elementos. 
            p Se caracteriza por dar una sensación de realidad en el espacio disponible para la instalación de los elementos o dispositivos electrónicos.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t1/f17.png', alt='imagen relacionada')
      .p-4.p-md-5(titulo="Esquema unifilar" :icono="require('@/assets/curso/temas/t1/f14.svg')")
        .row
          .col-md-6.mb-4.mb-md-0
            h4 Esquema unifilar
            p Este tipo de esquemático es más complejo de entender debido a su representación simplificada de los planos electrónicos, se caracteriza por incluir todos los conductores de un mismo tramo. De esta manera su simplicidad gráfica y complejidad de entendimiento aumentan.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t1/f18.png', alt='imagen relacionada')
      .p-4.p-md-5(titulo="Esquema multifilar" :icono="require('@/assets/curso/temas/t1/f15.svg')")
        .row
          .col-md-6.mb-4.mb-md-0
            h4 Esquema multifilar
            p A diferencia del esquema unifilar, el esquema multifilar tiene complejidad en su representación debido a su exactitud, en consecuencia, su comprensión es más elevada.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t1/f19.png', alt='imagen relacionada')
      .p-4.p-md-5(titulo="Esquema funcional" :icono="require('@/assets/curso/temas/t1/f16.svg')")
        .row
          .col-md-6.mb-4.mb-md-0
            h4 Esquema funcional
            p Este tipo de gráfico es una representación abreviada del esquema unifilar, lo que permite una visualización y comprensión más fácil del diagrama esquemático, por ende, es una de las representaciones más usadas.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/t1/f20.png', alt='imagen relacionada')

    h3 Tipos de software
    
    .row.justify-content-center.mb-4
      .col-md-5
        figure(data-aos='fade-right')
          img(src="@/assets/curso/temas/t1/f21.png", alt="Persona frente a la pantalla de un computador")
      .col-md-7
        .bloquetl.p-4.p-relative
          p.mb-0 La utilización de herramientas especializadas para el diseño de planos esquemáticos es de suma importancia hoy por hoy. Gracias a los softwares de diseño asistido por computadora actuales se puede probar cada uno de los diseños realizados sin la necesidad de materializarlos, reduciendo costos por cualquier tipo de fallo u operación. Por este principal motivo debemos familiarizarnos con los programas que se utilizarán en el desarrollo de este componente formativo.
            br
            br
            | A continuación, se presenta de manera general dos 
            em softwares 
            | que suelen ser empleados para el diseño de planos esquemáticos:

        TabsA.color-acento-botones.mb-4 
          .tarjeta.color-secundario--borde.p-4(titulo="Proteus")
            h4 Proteus
            p Proteus es un software especializado que permite el diseño de PCB, pruebas de sistemas integrados, por medio de simulaciones y construcción de entornos integrados con IoT. Dando como resultado una herramienta versátil y especializada para el diseño esquemático de circuitos electrónicos.
          .tarjeta.color-secundario--borde.p-4(titulo="Multisim")
            h4 Multisim
            p Es un 
              em software 
              | dedicado para la simulación y captura de planos esquemáticos electrónicos. Desarrollado por 
              em National Instruments 
              | y basado en el simulador de circuitos 
              em Berkeley.

    h3 Simulación de circuitos

    .bg2
      p Dentro de la comprobación de los diseños o planos esquemáticos de los circuitos electrónicos se pueden encontrar dos grandes grupos: circuitos analógicos y circuitos digitales.
      p A continuación, se presenta la definición y características de algunos de ellos.

      .col-md-8.mx-auto.mb-4
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t1/f22.svg' alt='alt' style='width:120px')
          .tarjeta.tarjeta--gris
            .p-4
              h5 Circuitos analógicos
              p Este tipo de circuitos se caracterizan por el manejo de señales eléctricas continuas, las cuales cambian con el transcurso del tiempo en valores infinitos o se mantienen fija a lo largo del mismo. Dentro de los elementos más comunes presentes en los circuitos analógicos se tienen: resistencias, capacitores, inductores, diodos, transistores, etc.
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t1/f23.svg' alt='alt' style='width:120px')
          .tarjeta.tarjeta--gris
            .p-4
              h5 Circuitos digitales
              p Este tipo de circuitos controlan señales que solo pueden tener dos estados posibles, ausencia o presencia de tensión o corriente, y se componen de aquellos elementos usados para representar salidas como: lámparas, timbres, motores, etc. Y también aquellos elementos usados para representar entradas como interruptores pulsadores, sensores, entre otros.

    h3 Motores eléctricos
    p Los motores eléctricos son componentes muy frecuentes en el entorno industrial debido a sus múltiples aplicaciones dentro de este entorno. Este principal motivo obliga a profundizar en los conceptos propios de los motores eléctricos, entre ellos su funcionamiento, partes y definición. Más precisamente: “El motor eléctrico es una máquina que puede convertir la electricidad en movimiento rotatorio, con objeto de que efectúe un trabajo útil.” (Mileaf, H. (2002). Electricidad. Limusa. p. 7-1). Para conocer un poco más de ellos, su funcionamiento, características y tipo, lo invitamos a observar con atención el siguiente video.

    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
    .bg3
      h3 Conexiones
      p Dependiendo del tipo de motor el cual se quiere poner en marcha, se debe realizar algunas configuraciones que están dadas por el tipo de conexión, entre ellas encontramos: conexión motor DC, conexión tipo estrella, conexión tipo Delta, puesta en marcha, arranque directo, arranque Y/∆. 
      p A continuación, se describen cada una de ellas: 

      .row.justify-content-center
        .col-md-5
          figure(data-aos='fade-right')
            img(src='@/assets/curso/temas/t1/f22.png' alt='motor')
        .col-md-7
          AcordionA(tipo="a" clase-tarjeta="tarjeta fcs80")
            div(titulo="Conexión Motor DC")
              p Esta conexión es la más simple, solo se debe conectar los dos pines o cables del motor en una fuente de tensión DC con el nivel sugerido por el fabricante. De acuerdo con la polaridad u orden de conexión el motor girará en un sentido u otro.
            div(titulo="Conexión Tipo estrella")
              p Este tipo de conexión es usada para los motores trifásicos; se caracteriza por conectar todas las fases en un punto común, es decir, todas las fuentes o fases conducen su energía aún mismo nodo. Es usado comúnmente en motores que requieran una baja corriente eléctrica para su arranque y alta tensión.
            div(titulo="Conexión tipo Delta")
              p La conexión tipo delta o triángulo se caracteriza por tener una fase en cada uno de sus lados sin la necesidad de punto común. A lo no existir este punto, no es necesario tener un neutro por lo cual, si una de las tres fases llega a fallar no se verá comprometido el funcionamiento del motor, ventaja muy importante a tener en cuenta en el diseño de este tipo de dispositivos. A diferencia de la configuración estrella, este tipo de conexión se usa en motores que demanden una alta corriente en el arranque y baja tensión.
            div(titulo="Puesta en marcha")
              p Para la puesta en marcha o arranque de un motor eléctrico se debe realizar una vez verificadas las características de este en su estructura, hoja de datos o manual. Dentro del arranque de los motores eléctricos se tienen las siguientes configuraciones.
            div(titulo="Arranque directo")
              p En este tipo de arranque se debe observar en la chapa del motor o en el manual del dispositivo el tipo de conexión admisible por el equipo. En ocasiones algunos motores admiten un arranque directo con conexión delta o estrella, para ello debemos seguir las instrucciones del fabricante para realizar una de estas configuraciones.
            div(titulo="Arranque Y/∆")
              p En motores con este tipo de arranque podremos alternar el funcionamiento del motor con las configuraciones delta o estrella, por ejemplo, arrancar el motor con la configuración estrella y cambiar después de un determinado tiempo a la conexión delta. Al igual que en el caso anterior se debe seguir las instrucciones del fabricante. En ocasiones se encontrarán motores capaces de operar con un arranque directo (Única configuración) o un arranque y funcionamiento combinado.

    Separador

    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Equipos, instrumentos y medidas

    p En física, química e ingeniería, un instrumento de medición es un dispositivo utilizado para comparar magnitudes físicas a través de un proceso de medición. En los tiempos modernos, se han desarrollado varios tipos de instrumentos de medición y se utilizan en laboratorios, entornos industriales y la vida cotidiana.
    p A continuación, se describen los equipos, instrumentos y medidas.

    .tarjeta.p-3.bgslide1(data-aos='fade-left')
      SlyderA(tipo="b")
        .row.align-items-center.justify-content-around
          .col-md-8.mb-4.mb-md-0
            h4 Tipos y variables
            p Dentro del área de trabajo un profesional va a encontrar múltiples dispositivos o señales que se necesitan medir para verificar su funcionalidad. Con esto en mente se procede a identificar el tipo de variable que se va a medir, dentro de las más comunes se tienen: corriente, tensión, resistencia, conductividad, conductancia, inductancia, capacitancia.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t1/f23.png', alt='Texto que describa la imagen')
        .row.align-items-center.justify-content-around
          .col-md-6.mb-4.mb-md-0
            h4 Unidades de medida
            p Una vez se ha identificado el tipo de variable, se procede a seleccionar el equipo idóneo de acuerdo con su unidad de medida y magnitud o variable a medir, acto seguido se debe corroborar el tipo de corriente con la cual funciona el equipo o circuito, es decir, se debe observar en el manual del fabricante si el tipo de corriente es continua o alterna.
          .col-md-5
            img(src='@/assets/curso/temas/t1/tablaSlide.svg')
            
        .row.align-items-center.justify-content-around
          .col-md-8.mb-4.mb-md-0
            h4 Rangos y calibración
            p Antes de proceder a medir las variables en los equipos es necesario garantizar las óptimas condiciones de los dispositivos, para esto, se debe definir los rangos y la calibración:
            ol.lista-ol--cuadro
              li.text-small 
                .lista-ol--cuadro__vineta
                  span.cblanco
                    i.fas.fa-angle-right
                | Rangos: este tipo de información proporciona el margen en el cual un equipo es capaz de medir de forma correcta una variable. Revisar el manual de usuario para verificar los rangos de medición de los equipos y los dispositivos a examinar es de suma importancia para evitar daños o accidentes a la hora de realizar cualquier procedimiento.
              li.text-small 
                .lista-ol--cuadro__vineta
                  span.cblanco
                    i.fas.fa-angle-right
                | Calibración: finalmente, es de suma importancia garantizar que los equipos se encuentren correctamente calibrados, esto para obtener valores precisos y confiables. Cada uno de los dispositivos de medición tiene una forma correcta de calibrarse; toda esta información se debe buscar en el manual de usuario y seguir las instrucciones al pie de la letra, de esta manera se garantiza un procedimiento adecuado y precisión en los resultados de las medidas.
          .col-md-4
            figure
              img(src='@/assets/curso/temas/t1/f24.png', alt='Texto que describa la imagen')
     
    Separador

    #t_1_3.bg4
      .titulo-segundo.color-acento-contenido
        h2 1.3 Circuitos eléctricos
      
      p Un circuito electrónico es una estructura compuesta por componentes pasivos, activos y semiconductores conectados entre sí formando trayectorias cerradas que inician y terminan en un mismo punto.

      .row.justify-content-center
        .col-md-5
          figure(data-aos='fade-right')
            img(src='@/assets/curso/temas/t1/f25.png' alt='motor')
        .col-md-7
          AcordionA(tipo="a" clase-tarjeta="tarjeta fcs80")
            div(titulo="Tipos")
              p Los circuitos electrónicos se dividen en dos grupos. El primer grupo son aquellos circuitos que manejan señales analógicas, aquellas cuyo valor de tensión o corriente varía en el tiempo o bien se mantiene constante. El segundo grupo son los circuitos digitales y son aquellos en donde sus tensiones o corrientes solo pueden poseer dos valores.
            div(titulo="Inspección visual y fallas")
              p La inspección visual es un apartado muy importante a la hora de verificar la calidad en los resultados de diseño o de buscar fallas en los circuitos electrónicos. Dentro de este apartado se debe buscar pistas mal diseñadas, rotas o con las especificaciones incorrectas, componentes mal ubicados o en mal estado. Lo anterior para lo calizar las posibles imperfecciones o averías dentro de un circuito electrónico.
            div(titulo="Planimetría")
              p La planimetría es la técnica o método por medio del cual se disponen los componentes de un circuito electrónico dentro de una representación gráfica a escala detallando el funcionamiento y ubicación de cada elemento, permitiendo así, su reproducibilidad, materialización, interpretación y comprensión del diseño electrónico.
            div(titulo="Pruebas de funcionamiento y normativas")
              p La industria eléctrica tiene muchos equipos especializados que deben probarse antes de usarse. Algunos equipos comunes que necesitan pruebas incluyen generadores de energía, sistemas de aire acondicionado y sistemas de comunicación. 
                br
                br
                | Para probar estos equipos se usa herramientas especiales para testear los componentes internos de los dispositivos y circuitos electrónicos y así, verificar primero la funcionalidad. Esto les permite identificar cualquier problema con el equipo antes de que alguien se lastime al usarlo en un lugar público. Una vez que se han identificado y solucionado los problemas con el equipo, se finaliza la prueba para que el equipo se pueda utilizar sin demora. Todos los procedimientos realizados a los equipos se deben hacer bajo las normas estipuladas por el fabricante, esto significa que se debe usar el manual de usuario en todo momento.

    Separador

    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4 Herramientas

    p Un profesional no solo debe contar con los conocimientos teóricos necesarios para realizar el diagnóstico o mantenimiento de equipos sino también debe contar con las herramientas adecuadas para cada procedimiento. A continuación, se presentan los tipos, características, uso y manejo y orden de trabajo.

    ImagenInfografica.color-acento-botones
      template(v-slot:imagen)
        figure
          img(src="@/assets/curso/temas/t1/f26.jpg", alt="", srcset="")

      .tarjeta.color-secundario.p-3(x="39%" y="40%" numero="1" style='width:90%')
        .h5.mb-2 Tipos
        p.cblanco.text-small Las herramientas usadas en el diagnóstico y mantenimiento de equipos se dividen en los siguientes grupos:
        ol.lista-ol--cuadro
          li.cblanco.text-small 
            .lista-ol--cuadro__vineta
              span a
            | Montaje y desmontaje: este tipo de herramientas permiten acceder a los elementos internos de cada uno de los componentes del equipo, comúnmente se suelen encontrar: desarmadores, pinzas, alicates, cautín, pistolas de calor, tercera mano con lupa, etc.
          li.cblanco.text-small 
            .lista-ol--cuadro__vineta
              span b
            | Limpieza: estas herramientas son esenciales para mantener los componentes libres de impurezas, comúnmente se tienen: paño de microfibra, isopos, brochas, alcohol isopropílico, limpia pantallas, limpiador de circuitos, etc.
          li.cblanco.text-small 
            .lista-ol--cuadro__vineta
              span c
            | Medición: son equipos diseñados para monitorear el comportamiento o estado de los elementos electrónicos existentes en un circuito. Dentro de este tipo de dispositivos se tiene los multímetros, osciloscopios, etc.
          li.cblanco.text-small 
            .lista-ol--cuadro__vineta
              span d
            | Seguridad: este tipo de herramientas mantienen la integridad del profesional y de los equipos. Dentro de este grupo se tienen: tapabocas, manillas o pulseras antiestáticas, guantes de látex o antiestáticos, etc.
      .tarjeta.color-secundario.p-3(x="20%" y="70%" numero="2")
        .h5.mb-2 Características
        p.cblanco.text-small Conociendo la herramienta a usar en el proceso de diagnóstico o mantenimiento debemos observar las características físicas de la pieza que vamos a intervenir, esto para evitar dañar tanto la herramienta como la pieza.
      .tarjeta.color-secundario.p-3(x="61%" y="15%" numero="3")
        .h5.mb-2 Uso y manejo
        p.cblanco.text-small Con la herramienta adecuada para la intervención de la o las piezas se debe consultar el manual del fabricante para seguir las instrucciones correctas para el procedimiento, esto evita el daño de otras piezas o del equipo.
      .tarjeta.color-secundario.p-3(x="70%" y="65%" numero="4")
        .h5.mb-2 Orden de trabajo
        p.cblanco.text-small Para garantizar un correcto procedimiento se debe tener un orden adecuado de cada una de las herramientas a usar, ordenar de forma secuencial cada uno de los tornillos, piezas y demás para evitar la pérdida o confusión a la hora del montaje. Este tipo de prácticas garantiza la integridad y funcionalidad de todos los elementos de los dispositivos.

    div.mb-5

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
