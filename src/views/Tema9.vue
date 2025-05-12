<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 9
      h1 Elaboración maqueta de comprobación
    

    Separador
    <!-- BLOQUE  -->
    #t_9_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.1 Funciones principales de la maqueta



    Separador
    <!-- BLOQUE  -->
    #t_9_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.2 Materiales comunes para la elaboración de maquetas



    Separador
    <!-- BLOQUE  -->
    #t_9_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.3 Importancia de la maqueta


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
