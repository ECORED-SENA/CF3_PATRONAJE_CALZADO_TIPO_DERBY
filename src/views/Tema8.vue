<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 8
      h1 Elaborar moldes para el modelo tipo <em>Derby</em> con chapeta

    
    Separador
    <!-- BLOQUE  -->
    #t_8_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 8.1 Elaborar molde patrón para el modelo tipo <em>Derby</em> con chapeta



    Separador
    <!-- BLOQUE  -->
    #t_8_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 8.2 Despidiese de moldes para el modelo tipo <em>Derby</em> con chapeta



    Separador
    <!-- BLOQUE  -->
    #t_8_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 8.3 Moldes forro para el modelo tipo <em>Derby</em> con chapeta


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
