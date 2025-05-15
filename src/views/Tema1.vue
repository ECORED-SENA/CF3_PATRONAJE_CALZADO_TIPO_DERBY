<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Líneas y puntos básicos para el desarrollo del patronaje

    .fondo_color_1
      .px-5
        p.mb-4 En la industria de fabricación de calzado, la precisión en el desarrollo de moldes resulta fundamental para garantizar la calidad y la estandarización de los productos. La elaboración de moldes requiere el dominio de diversas técnicas manuales, así como el conocimiento de principios relacionados con el diseño y el patronaje.
        .row.align-items-center.mb-5
          .col-xl
            p.mb-0.estilo___caja_1(data-aos="fade-right") Este componente formativo explica los pasos esenciales para crear moldes patrón y moldes de corte, desde la preparación inicial de la horma hasta la obtención de piezas listas para producción. El proceso comienza con el enmascarado de la horma, etapa clave en la que se trazan las líneas y formas que definen la estructura del modelo. A continuación, se elabora manualmente la camisa o trepa, que sirve como base para construir el molde patrón.
            p.mb-0.mt-4 A partir de la trepa se desarrolla el molde patrón, el cual se convierte en la principal referencia en la fabricación del calzado, asegurando medidas y proporciones correctas. Luego, se avanza en la creación de moldes específicos para modelos tipo <em>Derby</em>, incluyendo el despiece, la referenciación y la comprobación de los moldes; pasos que permiten identificar y organizar las piezas requeridas en el proceso de ensamble.
          .col-xl-auto
            figure.estilo___img_1.d-none.d-xl-block(data-aos="fade-left")
              img(src="@/assets/curso/temas/img2.svg", alt="" style="max-width: 270px").m-auto

        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-up")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/img3.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Al iniciar el patronaje, es indispensable conocer los puntos y líneas guía básicas, pues constituyen referencias esenciales para cualquier modelo. Aunque pueden variar según el diseño, estas guías deben marcarse siempre sobre la horma. El dominio de su uso permite al patronista alcanzar un alto nivel de exactitud en la elaboración de los moldes.

        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Punto metatarsiano
      
    .row.align-items-center.mb-5
      .col-xl
        p.mb-0.estilo___caja_1.espacio___movil_1(data-aos="fade-right") Para trazar las líneas básicas, primero se deben identificar los puntos metatarsianos, que corresponden a los cinco huesos del pie articulados con los dedos. Estos puntos, ubicados entre el primer y el quinto metatarsiano, se encuentran en las zonas más sobresalientes a cada lado de la base de la horma.
        p.mb-0.mt-4 Para obtenerlos, se coloca la horma apoyada sobre una superficie recta, asegurando que la línea de plantilla quede perpendicular a dicha superficie. La parte posterior de la horma debe tocar completamente la base; el otro punto de contacto con la superficie, conocido como punto tangencial, corresponde al punto metatarsiano. Este procedimiento se realiza en ambas caras de la horma, como se aprecia en la imagen siguiente.
      .col-xl-auto
        figure.d-none.d-xl-block(data-aos="fade-left")
          img(src="@/assets/curso/temas/img5.svg", alt="" style="max-width: 400px").m-auto

    .row.align-items-center.mb-5.espacio___movil_1
      .col-xl-6(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 1.
          span Punto metatarsiano externo
        figure
          img(src="@/assets/curso/temas/img6.png", alt="Vista lateral de una horma con indicación del punto metatarsiano externo, marcado en la zona sobresaliente del costado." style="max-width: 600px").m-auto
      .col-xl-6.espacio___movil_3(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 2.
          span Punto metatarsiano interno
        figure
          img(src="@/assets/curso/temas/img7.png", alt="Vista opuesta de la horma donde se señala el punto metatarsiano interno." style="max-width: 600px").m-auto
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Línea metatarsiana

    p.mb-4.espacio___movil_1 Para trazar esta línea, se emplea una cinta métrica, alineándola de forma que una los puntos metatarsianos interno y externo. Luego, se marca el trazo con un portaminas, tal como se ilustra en la imagen siguiente.

    .fondo_color_2.mb-5
      .px-5
        .row.align-items-center.mb-5.justify-content-center(data-aos="zoom-in")
          .col-lg-8
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 3.
              span Trazado de la línea metatarsiana
            figure
              img(src="@/assets/curso/temas/img9.png", alt="Imagen del trazado de la línea metatarsiana que conecta los puntos metatarsianos interno y externo. " )
        
        p.mb-4.espacio___movil_1 Este punto se obtiene en la intersección entre el eje del empeine y la línea metatarsiana, tal como se presenta en la imagen.

        .row.align-items-center.justify-content-center(data-aos="zoom-in")
          .col-lg-8
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 4.
              span Identificación del punto de calzada
            figure
              img(src="@/assets/curso/temas/img10.svg", alt="Diagrama del punto de calzada ubicado en la intersección entre el eje del empeine y la línea metatarsiana ").m-auto

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Punto de atraque

    p.mb-4.espacio___movil_1 Este punto se ubica en la mitad de la distancia entre el punto de calzada y la línea de plantilla, siguiendo el trazo de la línea metatarsiana. Se determina en ambos lados de la horma, tanto en el interno como en el externo, como se presenta en las siguientes imágenes.

    .row.mb-5
      .col-xl-6(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 5.
          span Determinación del punto de atraque externo 
        figure
          img(src="@/assets/curso/temas/img11.svg", alt="Identificación del punto de atraque externo sobre la horma. " style="max-width: 600px").m-auto
      .col-xl-6.espacio___movil_3(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 6.
          span Determinación del punto de atraque interno
        figure
          img(src="@/assets/curso/temas/img12.svg", alt="Identificación del punto de atraque interno sobre la horma." style="max-width: 600px").m-auto

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Punto de altura de talón

    p.mb-4.espacio___movil_1 Este punto se obtiene midiendo desde la línea de plantilla hacia la parte superior, específicamente sobre el eje del talón. La altura se calcula sumando una medida fija al número de la horma, según el tipo de calzado:
    
    .row.align-items-center.mb-5.justify-content-center
      .col-lg-10
        .row.align-items-center.mb-5
          .col-lg-6.estilo___caja_2(data-aos="fade-right")
            <ul class="fa-ul">
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Para calzado de hombre: número de la horma + 20 mm.</li>
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Para calzado de mujer: número de la horma + 18 mm.</li>
            </ul>
          .col-lg-6.estilo___caja_3.espacio___movil_3(data-aos="fade-left")
            h5.mb-3 Ejemplo:
            <ul class="fa-ul">
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Horma n.º 40 + 20 mm = 60 mm (altura del talón para hombre).</li>
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Horma n.º 40 + 18 mm = 58 mm (altura del talón para mujer).</li>
            </ul>
        
        .titulo-sexto.color-acento-contenido.mb-2.espacio___movil_1(data-aos="zoom-in")
          h5 Figura 7.
          span Cálculo de la altura del talón
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/temas/img13.png", alt="Representación del cálculo de la altura del talón a partir de la línea de plantilla. " style="max-width: 1030px").m-auto
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Línea de profundidad

    p.mb-4.espacio___movil_1 Esta línea se obtiene al unir, con ayuda de una cinta métrica, el punto de altura del talón con el punto de atraque. Una vez alineados, se marca el trazo, como se indica en la figura.

    .row.align-items-center.mb-5.justify-content-center(data-aos="zoom-in")
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 8.
          span Trazado de la línea de profundidad
        figure
          img(src="@/assets/curso/temas/img14.png", alt="Imagen del trazado de la línea de profundidad que une el punto de altura del talón con el punto de atraque. " ).m-auto

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Punto de entrada

    p.mb-4.espacio___movil_1 Este punto se determina midiendo desde el punto de calzada hacia arriba una distancia equivalente al número de la horma, sumando:

    .row.align-items-center.mb-5.justify-content-center
      .col-lg-10
        .row.align-items-center.mb-5
          .col-lg-6.estilo___caja_2.ajuste___1(data-aos="fade-right")
            <ul class="fa-ul">
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>28 milímetros si se trata de una horma de dama o niño.</li>
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>30 milímetros si es una horma de hombre.</li>
            </ul>
          .col-lg-6.estilo___caja_3.espacio___movil_3(data-aos="fade-left")
            h5.mb-3 Ejemplo:
            <ul class="fa-ul">
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Horma n.º 40 + 30 mm = 70 mm.</li>
              <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Horma n.º 40 + 28 mm = 68 mm.</li>
            </ul>
    
    p.mb-4.espacio___movil_5 Así se establece la ubicación del punto de entrada, como se indica en la siguiente imagen.

    .row.mb-5.justify-content-center
      .col-lg-6(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 9.
          span Punto de entrada
        figure
          img(src="@/assets/curso/temas/img15.svg", alt="Ubicación del punto de entrada determinado a partir del punto de calzada." ).m-auto

    .fondo_color_3.mb-5
      .px-5
        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Línea de entrada

        p.mb-4.espacio___movil_1 Esta línea se obtiene ubicando el metro en escuadra a 90 grados justo debajo del punto de entrada y dejándolo caer libremente sobre la horma hasta que alcance la línea de plantilla. Este procedimiento se realiza en ambos lados de la horma, como se presenta en la siguiente imagen.
      
        .row.mb-5.justify-content-center
          .col-lg-6(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 10.
              span Trazado de la línea de entrada
            figure
              img(src="@/assets/curso/temas/img17.svg", alt="Proceso para obtener la línea de entrada mediante escuadra desde el punto de entrada hacia la línea de plantilla." ).m-auto
    
    .fondo_color_4.mb-5
      .px-5
        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Línea de tobillo

        p.mb-4.espacio___movil_1 Esta línea se obtiene colocando la cinta métrica desde el punto de entrada hasta la parte inferior de la línea del talón. Luego, se traza el recorrido en ambos lados de la horma, como se indica en la siguiente imagen.
      
        .row.mb-5.justify-content-center
          .col-lg-6(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 11.
              span Trazado de la línea de tobillo
            figure
              img(src="@/assets/curso/temas/img19.svg", alt="Trazado de la línea de tobillo desde el punto de entrada hasta la base del talón. " ).m-auto
    
    .fondo_color_5.mb-5
      .px-5
        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Línea de chapeta o vena

        p.mb-4.espacio___movil_1 Esta línea se traza siguiendo el quiebre o filo de la parte delantera de la horma (capellada), como se muestra en la imagen.
      
        .row.mb-5.justify-content-center
          .col-lg-6(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 12.
              span Ubicación de la línea de chapeta o vena
            figure
              img(src="@/assets/curso/temas/img21.svg", alt="Indicación de la línea de chapeta o vena sobre la parte frontal de la horma.  " ).m-auto
    
    p.mb-4.espacio___movil_1 Una vez obtenidos los puntos y las líneas guía, se retira la máscara de la horma y se adhiere sobre una cartulina, asegurándola desde la línea de profundidad hacia afuera. Luego, se perfilan y rectifican los puntos y las líneas guía, y se marca la referencia, la talla de la horma y si corresponde a la cara externa o interna, como se presenta en la imagen.

    .row.justify-content-center
      .col-lg-6(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 13.
          span Retiro de la máscara y marcación de líneas guía
        figure
          img(src="@/assets/curso/temas/img22.png", alt="Máscara retirada de la horma y adherida a cartulina con líneas guía marcadas." ).m-auto
        
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
