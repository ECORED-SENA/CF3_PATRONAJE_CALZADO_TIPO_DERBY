<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Obtener camisa (trepa) de forma manual
    
    .row.align-items-center.mb-5
      .col-xl(data-aos="fade-right")
        p.mb-0.estilo___caja_4 El desarrollo de moldes para calzado requiere precisión y dominio técnico en cada una de sus etapas. Uno de los pasos fundamentales es el trazado de puntos y líneas guía sobre la horma, ya que permiten definir la forma y las proporciones del modelo. A partir de este trazado, se realiza el enmascarado de la horma, se obtiene la camisa y, posteriormente, se genera la máscara compensada, que sirve como base para el diseño del molde patrón. Este proceso garantiza simetría, ajuste y funcionalidad en la fabricación del calzado.
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img23.svg" style="max-width: 350px").m-auto

    .row.fondo-slider.mb-5
      .ajuste-slider(data-aos="fade-up")
        SlyderA(tipo="b")
          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4 Enmascarado de la horma para obtener la camisa
              p.mb-0 Durante el proceso de elaboración de la camisa, es fundamental realizar el enmascarado en ambas caras de la horma, tanto interna como externa, con el objetivo de obtener un perfil preciso que garantice la correcta construcción del molde.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img25.svg', alt='Esquema comparativo de mascaras externa e interna para diseño de calzado, con líneas geométricas que definen segmentos sobre la silueta lateral de un zapato.' style="max-width: 300px").m-auto

          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4 Superposición de máscaras externa e interna
              p.mb-0 Una vez se han obtenido ambas máscaras, estas se superponen procurando que coincidan la altura del talón y la línea de profundidad, lo que permite asegurar la simetría y precisión del molde.   
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img26.svg', alt='Esquema de superposición de máscaras externa e interna para molde de calzado, donde se alinean la altura del talón y la línea de profundidad.' style="max-width: 400px").m-auto

          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4 Promediado de curvas para obtener la máscara compensada
              p.mb-0 Se realiza un promedio entre las curvas obtenidas de ambas máscaras para generar una nueva curva más precisa y equilibrada, que servirá como base para el desarrollo de la camisa.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img27.svg', alt='Esquema de promediado de curvas de máscaras externa e interna para calzado, con líneas negras, rojas y azules que representan las siluetas individuales y la curva resultante.' style="max-width: 400px").m-auto

          .row.h-100.justify-content-center.align-items-center
            .col-lg-6.mb-4.col-xs-12
              h4 Esquema de máscara compensada para diseño de molde patrón de calzado
              p.mb-0 De esta manera se obtiene la máscara compensada, producto del ajuste y promediado de ambas curvas, la cual proporciona una base simétrica y precisa para el trazado del molde patrón. Para este procedimiento, se tomarán como referencia las líneas y puntos guías correspondientes a la cara externa de la horma.
            .col-lg-6
              figure
                img(src='@/assets/curso/temas/img28.svg', alt='Esquema de la máscara compensada para calzado que representa el contorno lateral de una horma con líneas guía rectas y puntos de referencia.' style="max-width: 400px").m-auto
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img4.svg" style="max-width: 60px").m-auto
      .col
        h3 Recorte de las piezas simétricas de la camisa
    
    p.mb-4.espacio___movil_1 A partir de la máscara compensada, se procede a recortar dos piezas simétricas que serán ensambladas para conformar la camisa de la horma. Estas piezas pueden elaborarse en diversos materiales, como papel, <em>telfor</em> o <em>cambrelle</em>; en este caso, se utilizará papel para facilitar el trazado y los ajustes necesarios.

    .row.mb-5.justify-content-center
      .col-lg-8(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 14.
          span Recorte de las piezas simétricas de la camisa
        figure
          img(src="@/assets/curso/temas/img29.png", alt="Recorte de dos piezas simétricas de la camisa a partir de la máscara compensada." ).m-auto

    p.mb-4.espacio___movil_1 Las piezas se unen en las zonas del empeine y del talón utilizando cinta de enmascarar, asegurando un ajuste firme que permita dar forma a la camisa sobre la horma.

    .row.mb-5.justify-content-center
      .col-lg-10(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 15.
          span Unión de piezas de la camisa sobre la horma
        figure
          img(src="@/assets/curso/temas/img30.png", alt="Unión de las piezas recortadas de la camisa sobre la horma con cinta adhesiva.").m-auto
    
    p.mb-4.espacio___movil_1 La camisa se arruga ligeramente para facilitar su colocación sobre la horma, lo que permite que se adapte mejor a su forma durante el proceso de ajuste.

    .row.mb-5.justify-content-center
      .col-lg-10(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 16.
          span Adaptación de la camisa a la horma
        figure
          img(src="@/assets/curso/temas/img31.png", alt="Proceso de adaptación de la camisa arrugada sobre la horma para mayor ajuste. ").m-auto
    
    p.mb-4.espacio___movil_1 Se verifica que la camisa ajuste correctamente sobre la horma, realizando los ajustes necesarios para asegurar que se adapte con precisión a su forma y contorno.

    .row.mb-5.justify-content-center
      .col-lg-8(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 17.
          span Verificación del ajuste de la camisa
        figure
          img(src="@/assets/curso/temas/img32.png", alt="Verificación del ajuste preciso de la camisa sobre la horma.").m-auto
    
    p.mb-4.espacio___movil_1 Finalmente, se obtiene el perfil de la horma, el cual servirá como base para la elaboración precisa del molde patrón.

    .row.mb-5.justify-content-center
      .col-lg-8(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 18.
          span Perfil de la horma como base del molde patrón
        figure
          img(src="@/assets/curso/temas/img33.png", alt="Perfil final de la horma obtenido a partir de la camisa.").m-auto

    p.mb-4.espacio___movil_1 Una vez compensada la máscara, se dibuja sobre una cartulina incluyendo los puntos y líneas guía, como se presenta en la imagen.

    .row.justify-content-center
      .col-lg-8(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 19.
          span Dibujo de la máscara compensada sobre cartulina
        figure
          img(src="@/assets/curso/temas/img34.svg", alt="Máscara compensada dibujada sobre cartulina con puntos y líneas guía.").m-auto

</template>

<script>
export default {
  name: 'Tema2',
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
