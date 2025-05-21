<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Tipología calzado <em>Derby</em> y sus variaciones
    
    .fondo_color_6
      .px-5

        .row.align-items-center.mb-5
          .col-xl(data-aos="fade-right")
            p.mb-0.estilo___caja_1 La tipología del calzado <em>Derby</em> representa una de las construcciones más reconocidas y utilizadas dentro del diseño clásico de zapatos. Su estructura abierta en el sistema de cordones le otorga una notable funcionalidad y adaptabilidad, cualidades que han asegurado su permanencia a lo largo del tiempo en contextos tanto formales como informales. Este apartado aborda los orígenes históricos del modelo <em>Derby</em>, explora su evolución a través de los siglos y presenta sus principales variaciones, ofreciendo una comprensión detallada de su relevancia en la industria del calzado.
          .col-xl-auto(data-aos="fade-left")
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img36.svg" style="max-width: 400px").m-auto

        <!-- BLOQUE 1 -->
        #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 3.1 Reseña histórica

        p.mb-5.espacio___movil_1 El calzado <em>Derby</em>, también conocido como <em>Blucher</em>, es un modelo clásico que se distingue por su sistema de cordones abiertos, a diferencia del modelo <em>Oxford</em>, que presenta una construcción de cordones cerrados. Gracias a su diseño versátil y cómodo, el <em>Derby</em> se ha consolidado como una opción popular tanto en contextos formales como informales.

        .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
          .col-lg-auto
            figure
              img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
          .col
            h3 Origen y evolución

        .row.align-items-center.espacio___movil_1
          .col-xl-auto(data-aos="fade-right")
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img37.svg" style="max-width: 400px").m-auto
          .col-xl(data-aos="fade-left")
            p.mb-0.estilo___caja_5 Con el tiempo, especialmente durante el siglo XIX y principios del XX, el <em>Derby</em> pasó de ser un calzado funcional para actividades al aire libre y deportes como la caza a convertirse en una prenda de uso diario para hombres de diferentes clases sociales.

        Separador
        <!-- BLOQUE 2 -->
        #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 3.2 Variaciones del Modelo <em>Derby</em>

        p.mb-5.espacio___movil_1 Con el aumento de su popularidad, el calzado <em>Derby</em> adoptó distintas variaciones, adaptándose a diferentes necesidades, estilos y contextos de uso.

        .row.fondo-slider.mb-4.espacio___movil_1
          .ajuste-slider(data-aos="fade-up")
            SlyderA(tipo="b")
              .row.h-100.justify-content-center.align-items-center
                .col-lg-6.mb-4.col-xs-12
                  h4 <em>Derby</em> liso
                  p.mb-0 Versión sencilla, sin detalles ni perforaciones, conformada por una capellada y dos cordoneras. Ideal para eventos formales.
                .col-lg-6
                  figure
                    img(src='@/assets/curso/temas/img38.svg', alt='' style="max-width: 400px").m-auto

              .row.h-100.justify-content-center.align-items-center
                .col-lg-6.mb-4.col-xs-12
                  h4 <em>Derby</em> con puntera
                  p.mb-0 La capellada se secciona en la punta. Puede ser liso o incluir perforaciones y costuras en la puntera y/o cordonera, lo que le da un aspecto más casual. 
                .col-lg-6
                  figure
                    img(src='@/assets/curso/temas/img39.svg', alt='' style="max-width: 400px").m-auto

              .row.h-100.justify-content-center.align-items-center
                .col-lg-6.mb-4.col-xs-12
                  h4 <em>Derby</em> con bigotera
                  p.mb-0 Presenta una puntera en forma de "W" o "ala", comúnmente combinada con perforaciones y costuras decorativas.
                .col-lg-6
                  figure
                    img(src='@/assets/curso/temas/img40.svg', alt='' style="max-width: 400px").m-auto

              .row.h-100.justify-content-center.align-items-center
                .col-lg-6.mb-4.col-xs-12
                  h4 <em>Derby</em> con chapeta
                  p.mb-0 Se caracteriza por la división de la capellada desde el filo de la horma, generando una pieza adicional llamada chapeta. Aporta un diseño distintivo y una estructura particular.
                .col-lg-6
                  figure
                    img(src='@/assets/curso/temas/img41.svg', alt='' style="max-width: 400px").m-auto

              .row.h-100.justify-content-center.align-items-center
                .col-lg-6.mb-4.col-xs-12
                  h4 <em>Derby</em> con correa
                  p.mb-0 Sustituye los cordones por una o más correas con hebillas. Combina la estructura clásica del <em>Derby</em> con un toque de sofisticación, adecuado para estilos formales o casuales según el material y acabado.
                .col-lg-6
                  figure
                    img(src='@/assets/curso/temas/img42.svg', alt='' style="max-width: 400px").m-auto

        p.mb-0 Hoy en día, el <em>Derby</em> continúa siendo un zapato icónico tanto en la moda masculina como femenina, disponible en materiales como cuero, gamuza y textiles sintéticos. Su versatilidad lo convierte en una prenda clave en cualquier guardarropa, al combinar elegancia y comodidad.

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
