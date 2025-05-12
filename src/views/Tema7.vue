<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 7
      h1 Elaborar moldes para el modelo tipo <em>Derby</em> con Bigotera


    Separador
    <!-- BLOQUE  -->
    #t_7_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.1 Elaborar molde patrón para el modelo tipo <em>Derby</em> con Bigotera


    Separador
    <!-- BLOQUE  -->
    #t_7_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.2 Despidiese de moldes para el modelo tipo <em>Derby</em> con Bigotera



    Separador
    <!-- BLOQUE  -->
    #t_7_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.3 Moldes forro para el modelo tipo <em>Derby</em> con Bigotera


</template>

<script>
export default {
  name: 'Tema5',
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
