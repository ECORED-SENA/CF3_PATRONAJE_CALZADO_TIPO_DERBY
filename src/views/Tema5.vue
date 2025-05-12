<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Elaborar moldes para el modelo tipo <em>Derby</em> liso

    Separador
    <!-- BLOQUE  -->
    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.1 Elaborar molde patrón para el modelo tipo <em>Derby</em> liso


    Separador
    <!-- BLOQUE  -->
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.2 Despidiese de moldes para el modelo tipo <em>Derby</em> liso


    Separador
    <!-- BLOQUE  -->
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.2 Moldes forro para el modelo tipo <em>Derby</em> liso


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
