<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Moldes, conceptos y tipos

    .fondo_color_7
      .px-5

        .row.align-items-center.mb-5.m-0
          .col-xl.estilo___caja_1(data-aos="fade-right")
            p.mb-3 Los moldes o patrones son plantillas planas que representan las distintas piezas que conforman la capellada del calzado. A partir de ellos se realiza el corte y el ensamblaje de los materiales que darán forma al producto final. Son fundamentales para asegurar precisión, simetría, confort y diseño en cada referencia de calzado.
            p.mb-0 El desarrollo de los moldes parte del perfil de la horma, obtenido mediante técnicas como el enmascarado, el trazado de líneas guía y la creación de una máscara compensada. Con base en esta plantilla, se diseñan y trazan las piezas que luego se escalarán de acuerdo con las tallas requeridas.
          .col-xl-auto(data-aos="fade-left")
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img44.svg" style="max-width: 400px").m-auto
        
        p.mb-5.espacio___movil_1 Entre los principales tipos de moldes utilizados en la fabricación de calzado se encuentran:

        .row.fondo-img_1
          .row.mb-5
            .col-xl-4(data-aos="fade-right")
              figure.d-none.d-xl-block
                img(src='@/assets/curso/temas/img46.png', alt='' style="max-width: 350px").m-auto
            .col-xl-8(data-aos="fade-left")
              SlyderF(columnas="col-lg-6 col-xl-4")

                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/img47.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Moldes base o patrón
                  p.mb-0 Definen la estructura del modelo y sirven como referencia para generar variantes.

                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/img48.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Moldes de corte
                  p.mb-0 Se utilizan para cortar los materiales definitivos que conforman la capellada.

                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/img49.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Moldes de forro y refuerzo
                  p.mb-0 Corresponden a las piezas internas que aportan estructura, confort y durabilidad.

                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/img50.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Moldes de montaje o plantillas de armado
                  p.mb-0 Guían el proceso de ensamblaje del calzado.

                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/img51.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Moldes de rayado o marcación
                  p.mb-0 Permiten señalar sobre el material las líneas de doblez, costuras, piquetes, centros y otras marcas técnicas necesarias para un ensamblaje preciso.

          p.mb-0.espacio___movil_1 Cada uno de estos moldes cumple una función específica dentro del proceso de fabricación, y su correcta elaboración influye directamente en la calidad del calzado final.

</template>

<script>
export default {
  name: 'Tema4',
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
