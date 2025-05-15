<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.fondo_img
      p.mb-4 En la industria de la fabricación de calzado, la precisión en el desarrollo de moldes resulta esencial para asegurar la calidad y estandarización de los productos. Este proceso requiere el dominio de técnicas manuales, así como el conocimiento de principios de diseño y patronaje.
      .row.align-items-center
        .col-xl
          p Este componente formativo presenta los pasos fundamentales para la creación de moldes patrón y moldes de corte, desde la preparación inicial de la horma hasta la obtención de piezas listas para la producción. El recorrido comienza con el enmascarado de la horma, etapa clave para trazar las líneas y formas que estructuran el modelo. A continuación, se elabora de manera manual la camisa o trepa, que sirve de base para construir el molde patrón.
          p.mb-0.estilo___caja_1(data-aos="fade-right") A partir de la trepa, se procede a la elaboración del molde patrón, que actúa como referencia principal para la fabricación del calzado, asegurando medidas y proporciones adecuadas. Finalmente, se profundiza en la elaboración de moldes específicos para los modelos tipo <em>Derby</em>, incluyendo el despiece, referenciado y comprobación de los moldes, un proceso crucial para identificar y organizar las piezas necesarias para el ensamble del calzado.
        .col-xl-auto
          figure.d-none.d-xl-block(data-aos="fade-left")
            img(src="@/assets/curso/intro/img2.svg", alt="" style="max-width: 450px").m-auto

</template>

<script>
export default {
  name: 'Introduccion',
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
