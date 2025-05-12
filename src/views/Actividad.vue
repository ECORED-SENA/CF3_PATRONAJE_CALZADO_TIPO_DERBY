<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema:
        'Elaboración y comprobación de moldes para calzado tipo <em>Derby</em>',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> Identificar los conceptos, procesos y técnicas clave en la elaboración y verificación de moldes para calzado tipo <em>Derby</em>, según las especificaciones del diseño y los procedimientos técnicos.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!..',
      titulo_reprobado: 'VUELVA A INTENTARLO..',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Qué elemento se utiliza como base para trazar las líneas guía sobre la horma?',
          imagen: require('@/assets/actividad/imagen1.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Hormiguilla.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cambrado.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Enmascarado.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Lengüeta.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Cuál es la principal característica estructural del calzado tipo <em>Derby</em>?',
          imagen: require('@/assets/actividad/imagen1.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Lengüeta unida.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Sistema de cordones abiertos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Capellada alta.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Suela doble.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Qué indica el punto metatarsiano en el desarrollo del patrón?',
          imagen: require('@/assets/actividad/imagen1.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ubicación de la articulación del pie.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Altura del talón.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Inicio de la lengüeta.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Final del talón.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué medida se suma al número de la horma para obtener la altura del talón en calzado masculino?',
          imagen: require('@/assets/actividad/imagen1.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: '15 mm.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: '20 mm.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: '25 mm.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: '30 mm.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Cuál es el propósito del proceso de calado en el patrón?',
          imagen: require('@/assets/actividad/imagen2.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Aumentar el volumen del molde.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Facilitar el trazado y despiece.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Medir la suela del zapato.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reforzar las costuras.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué tipo de <em>Derby</em> presenta una puntera en forma de “W”?',
          imagen: require('@/assets/actividad/imagen2.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: '<em>Derby</em> con chapeta.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: '<em>Derby</em> con puntera.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: '<em>Derby</em> con bigotera.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: '<em>Derby</em> con correa.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Qué tipo de molde representa las piezas planas del calzado?',
          imagen: require('@/assets/actividad/imagen2.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Molde de forro.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Molde patrón.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Molde de ajuste.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Molde tridimensional.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto: '¿Qué material se recomienda para maquetas más avanzadas?',
          imagen: require('@/assets/actividad/imagen2.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Cartulina.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Papel <em>kraft</em>.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: '<em>Telford</em>.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Cuero.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué elemento se incorpora en el diseño del <em>Derby</em> con chapeta?',
          imagen: require('@/assets/actividad/imagen3.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Una bigotera.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Una pieza adicional sobre la capellada.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Correas con hebilla.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Perforaciones en la suela.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto: '¿Cuál es la función de la máscara compensada?',
          imagen: require('@/assets/actividad/imagen3.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Obtener una base simétrica del molde patrón.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Marcar el tamaño final del zapato.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Reducir el tiempo de montaje.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Crear la lengüeta.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'El punto de atraque se encuentra entre el punto de calzada y la línea de plantilla.',
          imagen: require('@/assets/actividad/imagen3.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'El <em>Derby</em> con puntera y talón no requiere molde cambrado.',
          imagen: require('@/assets/actividad/imagen3.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto: 'La bigotera no debe cruzarse con otras piezas del molde.',
          imagen: require('@/assets/actividad/imagen4.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto: 'Los moldes de forro deben incluir puntos y líneas guía.',
          imagen: require('@/assets/actividad/imagen4.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            'La maqueta permite detectar errores antes de la producción final.',
          imagen: require('@/assets/actividad/imagen4.svg'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
