<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 9
      h1 Elaboración maqueta de comprobación
    
    .row.align-items-center.m-0.mb-5
      .col-xl.estilo___caja_1.ajuste___8(data-aos="fade-right")
        p.mb-0 La maqueta es una representación tridimensional del diseño del calzado, elaborada a partir de los moldes iniciales. Se emplea como herramienta de verificación durante el desarrollo del patrón, permitiendo al patronista analizar de manera práctica cómo se ajustan y se comportan las piezas del diseño sobre la horma.
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img138.svg" style="max-width: 400px").m-auto

    <!-- BLOQUE 1 -->
    #t_9_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.1 Funciones principales de la maqueta

    p.mb-4.espacio___movil_1 La maqueta cumple varias funciones esenciales dentro del proceso de patronaje:

    .bg--img_03
      .row.h-100.align-items-center
        .col-lg-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/temas/img119.png", alt="" style="width: 382px").m-auto
        .col-lg
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Verificar el ajuste").ajuste-cajaAcordion
              p.mb-0 Permite comprobar si las piezas del molde encajan correctamente sobre la horma, identificando tensiones, pliegues o sobrantes.
            .row(titulo="Evaluar el diseño").ajuste-cajaAcordion
              p.mb-0  Ayuda a revisar la distribución estética de las piezas (capellada, cordonera, talón, puntera, entre otras) y confirmar que respeten las proporciones y líneas proyectadas.
            .row(titulo="Corregir inconsistencias").ajuste-cajaAcordion
              p.mb-0 Facilita la detección de errores o desajustes en el trazado del molde, permitiendo hacer correcciones antes de cortar en materiales definitivos.
            .row(titulo="Optimizar tiempos y materiales").ajuste-cajaAcordion
              p.mb-0 Al identificar errores tempranamente, se reduce el desperdicio de material y se evitan retrabajos durante la producción.

    Separador
    <!-- BLOQUE 2 -->
    #t_9_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.2 Materiales comunes para la elaboración de maquetas

    p.mb-4.espacio___movil_1 Los materiales más utilizados para construir maquetas de comprobación son:

    .row.fondo-slider
      .ajuste-slider(data-aos="fade-up")
        SlyderA(tipo="b")
          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4.mb-4 Papel <em>kraft</em> o cartulina
              p.mb-0 Fáciles de manipular y económicos, ideales para pruebas preliminares.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img139.svg', alt='' style="max-width: 400px").m-auto

          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4.mb-4 <em>Telford</em>
              p.mb-0 Plástico delgado y flexible que ofrece mayor precisión en el ajuste y permite una revisión detallada del diseño.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img140.svg', alt='' style="max-width: 400px").m-auto

          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4.mb-4 <em>Cambrelle</em>
              p.mb-0 Tejido no tejido que simula mejor el comportamiento de materiales reales como la lona o el forro.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img141.svg', alt='' style="max-width: 400px").m-auto

          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4.mb-4 Cuero (retales)
              p.mb-0 Utilizado en maquetas más avanzadas cuando se requiere una verificación más cercana al calce y acabado reales.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img142.svg', alt='' style="max-width: 400px").m-auto 

    Separador
    <!-- BLOQUE 3 -->
    #t_9_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.3 Importancia de la maqueta

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.espacio___movil_1(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img143.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El uso de maquetas es una práctica clave en el diseño de calzado, ya que permite detectar oportunamente fallas estructurales o estéticas. Gracias a este paso, se garantiza que el producto final no solo cumpla con las condiciones de funcionalidad y comodidad, sino que también conserve una composición visual equilibrada.


</template>

<script>
export default {
  name: 'Tema9',
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
