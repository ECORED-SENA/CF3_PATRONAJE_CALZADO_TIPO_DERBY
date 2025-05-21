<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 8
      h1 Elaborar moldes para el modelo tipo <em>Derby</em> con chapeta
    
    <!-- BLOQUE 0 -->
    .row.align-items-center.mb-5.m-0
      .col-xl.estilo___caja_1.ajuste___8(data-aos="fade-right")
        p.mb-0 El calzado <em>Derby</em> con chapeta es una variante del clásico <em>Derby</em>, reconocible por la incorporación de una pieza adicional en la parte superior denominada chapeta. Esta no solo aporta un elemento decorativo, sino que también refuerza estructuralmente el diseño. A continuación, se describen sus características más relevantes:
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img118.svg" style="max-width: 400px").m-auto
    
    .bg--img_03.espacio___movil_1
      .row.h-100.align-items-center
        .col-lg-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/temas/img119.png", alt="" style="width: 382px").m-auto
        .col-lg
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Construcción y diseño").ajuste-cajaAcordion
              p.mb-0 La chapeta se superpone a la capellada, brindando un detalle distintivo y un refuerzo estructural adicional. La capellada está conformada por varias piezas, lo que permite combinar materiales y colores, otorgando mayor versatilidad. Se conserva la estructura de cordonera abierta, característica del modelo <em>Derby</em>, lo que facilita el ajuste y mejora la comodidad.
            .row(titulo="Estilo y funcionalidad").ajuste-cajaAcordion
              p.mb-0  Este modelo es versátil y puede adaptarse tanto a contextos formales como informales, dependiendo del material y acabado empleados. La chapeta, así como otras partes del calzado, puede incorporar perforaciones decorativas (brogueado), aportando un toque sofisticado. Su sistema de ajuste también favorece la comodidad, adaptándose a diferentes tipos de pie. 
            .row(titulo="Proceso de elaboración").ajuste-cajaAcordion
              p.mb-0 Para desarrollar esta variación, se utiliza el patrón cambrado con su respectivo aumento de montaje, adaptándolo según las características propias del modelo <em>Derby</em> con chapeta.
    
    Separador
    <!-- BLOQUE 1 -->
    #t_8_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 8.1 Elaborar molde patrón para el modelo tipo <em>Derby</em> con chapeta
    
    p.mb-4.espacio___movil_1 El proceso de elaboración de la cordonera es similar al del modelo <em>Derby</em> liso, con una variación: la cordonera se dividirá en dos partes. Recuerde trabajar a partir de la máscara compensada.

    .row.m-0.align-items-center.mb-5.justify-content-center
      .col-lg-10.estilo___caja_20(data-aos="zoom-in")
        <ul class="fa-ul">
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Trace una línea paralela a 25 mm de la línea de empeine, ubicada sobre la cabeza de la cordonera.</li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut"></i></span>Dibuje otra línea paralela a 20 mm de la línea metatarsiana.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span>Suavice las curvas de la nueva pieza resultante; esta será una sección de la cordonera.</li>
        </ul>

    .fondo_color_21
      .px-5 
        p.mb-4.espacio___movil_1 Esta sección puede integrarse como una pieza independiente o emplearse como una costura decorativa.

        .row.mb-5.justify-content-center
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 43.
              span Sección adicional de la cordonera trazada sobre el molde
            figure
              img(src="@/assets/curso/temas/img121.svg", alt="Trazado de la sección adicional de la cordonera para el modelo con chapeta.").m-auto
        
        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Construcción de la chapeta

        p.mb-4.espacio___movil_1 La línea de la chapeta se obtiene durante el proceso de enmascarado, marcando el perfil de la parte delantera de la horma. Esta línea debe quedar representada en el patrón.

        h5.mb-4 Pasos para la correcta ubicación y ajuste:

        .row.mb-5.justify-content-center
          .col-lg-5(data-aos="zoom-in")
            .estilo___caja_15.h-100
              .row.justify-content-center.mb-3
                .col-lg
                  figure.mb-4.d-none.d-xl-block
                    img(src='@/assets/curso/temas/img122.png', alt="").m-auto
                h3.mb-4 Ajuste de la posición de la chapeta
                p.mb-0 A partir de la línea de chapeta, retrase su posición 5 mm respecto al punto original. Este ajuste se realiza para compensar la tensión del cuero durante el montaje de la capellada, evitando que la chapeta se desplace hacia la punta.
          .col-lg-5.espacio___movil_3(data-aos="zoom-in")
            .estilo___caja_15.ajuste___9.h-100
              .row.justify-content-center.mb-3
                .col-lg
                  figure.mb-4.d-none.d-xl-block
                    img(src='@/assets/curso/temas/img123.png', alt="").m-auto
                h3.mb-4 Reducción de los laterales
                p.mb-0 Reduzca 3 mm en los laterales y asegúrese de que la línea finalice en el punto de atraque original. Estos ajustes pueden variar según el comportamiento del material con el que se elaborará el calzado.
    
    .fondo_color_22.mb-5.espacio___movil_1
      .px-5
        .row.m-0.mb-5.justify-content-center
          .col-lg-10.estilo___caja_6.ajuste___10(data-aos="zoom-in")
            h5.mb-4 La construcción de la lengüeta: 
            <ul class="fa-ul">
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span>Marque un punto 15 mm por encima del punto de entrada.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span>Desde allí, trace una línea perpendicular hacia abajo con una longitud de 35 mm.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span>Dibuje una línea perpendicular a esta, asegurándose de que no exceda los límites de la cordonera.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span>A partir de este trazo, delimite la parte superior de la lengüeta con una línea paralela a la línea metatarsiana, ubicada 20 mm por encima.</li>
              <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span>Finalmente, suavice las intersecciones con curvas continuas para dar forma definitiva a la lengüeta.</li>
            </ul>
        
        .row.mb-5.justify-content-center
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 44.
              span Construcción completa de la lengüeta y chapeta sobre el molde del calzado
            figure
              img(src="@/assets/curso/temas/img125.svg", alt="Construcción completa de la lengüeta y chapeta sobre el molde del calzado.").m-auto
        
        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Construcción capellada

        p.mb-4.espacio___movil_1 Para obtener la capellada, incremente 10 mm sobre la línea de chapeta ajustada y la línea de boca de talón. Luego, ajuste la intersección de ambas líneas para garantizar una correcta unión en el diseño.
    
    .fondo_color_23.mb-5
      .px-5
        .row.justify-content-center.espacio___movil_1
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 45.
              span Aumento de 17 mm para montaje
            figure
              img(src="@/assets/curso/temas/img127.svg", alt="Aumento de 17 mm en el molde de capellada para permitir el montaje.").m-auto
            
        Separador
        <!-- BLOQUE 2 -->
        #t_8_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 8.2 Despiece de moldes para el modelo tipo <em>Derby</em> con chapeta

        p.mb-4.espacio___movil_1 El despiece de los moldes en este modelo sigue los principios aplicados en versiones anteriores, pero incorpora adaptaciones puntuales según el diseño.
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Cordonera
    
    p.mb-4.espacio___movil_1 Se elabora siguiendo el mismo procedimiento que en los modelos anteriores, con la diferencia de que se modifica el despiece en la zona de la cabeza de la cordonera, adaptándolo según el diseño específico. Realice los aumentos de dobla y unión en el talón.

    .fondo_color_24.mb-5
      .px-5
        .row.justify-content-center
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 46.
              span Molde de cordonera
            figure
              img(src="@/assets/curso/temas/img129.svg", alt="Molde final de la cordonera adaptado para el modelo con chapeta.").m-auto
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Capellada

    .fondo_color_25.mb-5
      .px-5
        p.mb-4.espacio___movil_1 Para el desarrollo del molde de la capellada, se utiliza como referencia el eje central de la misma, sobre el cual se dobla la cartulina para realizar simetría.
        .row.justify-content-center.mb-5
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 47.
              span Molde de capellada
            figure
              img(src="@/assets/curso/temas/img131.svg", alt="Molde simétrico de capellada recortado a partir del eje central de la cartulina.").m-auto
    
        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Chapeta

        p.mb-4.espacio___movil_1 Dibuje la chapeta sobre una cartulina exactamente como aparece en el molde patrón.

    .fondo_color_26.mb-5
      .px-5
        .row.justify-content-center.mb-5
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 48.
              span Molde base de chapeta trazado sobre cartulina
            figure
              img(src="@/assets/curso/temas/img133.svg", alt="Molde inicial de chapeta dibujado con contorno superior e inferior, tal como aparece en el patrón original.").m-auto
        
        .row.mb-5.justify-content-center.espacio___movil_1
          .col-lg-10
            .row.align-items-center.estilo___caja_6(data-aos="zoom-in")
              .col-xl-auto
                figure.d-none.d-xl-block
                  img(src="@/assets/curso/temas/img134.png" style="max-width: 400px").m-auto
              .col-xl
                h5.mb-5 Cuando el molde se encuentra en dos ejes, es necesario realizar un giro para completar su trazado. Para ello:
                <ul class="fa-ul">
                  <li class="mb-4"><span class="fa-li"><i class="fas fa-cut"></i></span>Ubique el eje de capellada de la chapeta sobre el eje de simetría de la cartulina.</li>
                  <li class="mb-4"><span class="fa-li"><i class="fas fa-cut"></i></span>Trace la parte que va desde la punta hasta la línea perpendicular trazada desde el punto de calzada.</li>
                  <li class="mb-4"><span class="fa-li"><i class="fas fa-cut"></i></span>A continuación, utilizando el punto de calzada como eje de rotación, gire la pieza gradualmente.</li>
                  <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span>Continúe dibujando, de forma perpendicular, la parte superior de la chapeta hasta que el eje del empeine coincida con el eje de simetría.</li>
                </ul>
        
        .row.justify-content-center.mb-5
          .col-lg-8(data-aos="zoom-in")
            .titulo-sexto.color-acento-contenido.mb-2
              h5 Figura 49.
              span Inicio del giro del molde de chapeta desde el punto de calzada
            figure
              img(src="@/assets/curso/temas/img135.svg", alt="Imagen del molde girado sobre el eje de capellada, comenzando desde el punto de calzada hasta la línea perpendicular trazada desde ese mismo punto.").m-auto
    
    p.mb-4.espacio___movil_1 Por último, suavice las curvas de la parte superior de la chapeta para lograr una transición armónica en el diseño. Luego, realice la simetría correspondiente para completar el molde. Si la chapeta va doblada, añada un aumento de 5 mm.

    .row.justify-content-center
      .col-lg-8(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 50.
          span Desarrollo del giro y trazado perpendicular de la chapeta
        figure
          img(src="@/assets/curso/temas/img136.svg", alt="Secuencia de trazado de la parte superior de la chapeta al girar la plantilla, conectando el eje de capellada con el eje del empeine para lograr una figura simétrica.").m-auto 

    Separador
    <!-- BLOQUE 3 -->
    #t_8_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 8.3 Moldes forro para el modelo tipo <em>Derby</em> con chapeta

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.espacio___movil_1(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img137.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los moldes de forro se construyen de la misma forma que en el modelo <em>Derby</em> con puntera. Estas son las principales variaciones del modelo <em>Derby</em>, a partir de las cuales se pueden crear múltiples diseños con diferencias en las cordoneras, talones y detalles adicionales, como adornos, costuras o perforaciones, entre otros.


</template>

<script>
export default {
  name: 'Tema8',
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
