<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Establecimientos de alojamiento y hospedaje


    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-12
        .bloque-texto-g.bloque-texto-g--inverso.bg-color-1.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Un establecimiento de alojamiento u hospedaje se define como una unidad prestadora de servicios turísticos que ofrece estancia temporal a personas fuera de su lugar de residencia habitual, garantizando condiciones de descanso, seguridad y atención durante su permanencia. Estos establecimientos, que incluyen hoteles, hostales, apartahoteles y posadas, cumplen un papel fundamental en la cadena de valor del turismo, ya que facilitan la permanencia del visitante en un destino y contribuyen a la calidad de la experiencia turística. Además, el servicio de alojamiento no se limita al espacio físico, sino que integra procesos operativos, atención al cliente y servicios complementarios que responden a estándares definidos dentro del sector (Ministerio de Comercio, Industria y Turismo (MinCIT), 2017).

    .row.justify-content-center.mb-0
      .col-lg-10(data-aos="fade-right")
        .tarjeta.bg-color-1.p-4
          .row.justify-content-around.align-items-center
            .col-lg-2.col-md-2.col-4.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/img02.svg", alt="")
            .col-lg-7.col-md-7.col-12.mb-3.mb-lg-0
              p.mb-0 En el siguiente recurso podrá aprender qué es un establecimiento de alojamiento o de hospedaje, cuáles son los factores de servicio, los criterios de evaluación para el otorgamiento del certificado de categorización por estrellas y cuál es su clasificación.
            .col-lg-3.col-md-3.col-12
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=fAg0gdOyEt4" target="_blank")
                span Ver video
                i.fas.fa-play-circle

    separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.1 Clasificación de hoteles

    .row.mb-4.justify-content-center.align-items-center
      .col-lg-2.col-md-8.mb-4.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/img03.png", alt="").mx-auto
      .col-lg-10.col-md-12
        p.mb-0 En Colombia, la clasificación de los establecimientos de alojamiento se fundamenta en criterios definidos por la normativa turística y las normas técnicas sectoriales, las cuales permiten organizar y diferenciar los tipos de servicios ofrecidos al huésped. De acuerdo con el Ministerio de Comercio, Industria y Turismo, los establecimientos se clasifican en categorías como hoteles, apartahoteles, hostales, centros vacacionales, viviendas turísticas y otros tipos de alojamiento, cada uno con características específicas en cuanto a infraestructura, capacidad, servicios y nivel de atención. Esta clasificación facilita la regulación del sector, garantiza mayor claridad para el usuario y permite estandarizar la prestación del servicio en función de la calidad y la experiencia esperada por el cliente (Ministerio de Comercio, Industria y Turismo (MinCIT), 2017).
        
      

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-9.mb-3.mb-lg-0
        .bg-fondo-4.px-5.py-4
          .col-11.col-md-12
            p.mb-0 Asimismo, la clasificación de los establecimientos de alojamiento también se relaciona con sistemas de categorización, como la asignación de estrellas para hoteles, que responde a estándares de calidad definidos en normas técnicas sectoriales como las NTSH. Estos criterios consideran aspectos como el confort de las instalaciones, la variedad de servicios, la atención al cliente y la gestión operativa del establecimiento. De esta manera, la categorización no solo orienta al huésped en la elección del servicio, sino que también impulsa a los prestadores a mejorar continuamente sus procesos y a cumplir con los requisitos establecidos para fortalecer la competitividad del sector turístico en el país (ICONTEC, 2015).
      .col-lg-3.col-md-8
        figure
          img(src="@/assets/curso/tema2/img05.png", alt="").mx-auto

    p.mb-5 En la infografía a continuación, se describen los criterios de evaluación para el otorgamiento del certificado de categorización por estrellas de los diferentes establecimientos de alojamiento y hospedaje.

    //- figura
    
    .row.justify-content-center.mb-5
      .col-md-12.col-lg-12
        .titulo-sexto.color-acento-contenido
          h5 
            b Figura 2.
          span Criterios de evaluación para otorgamiento y categorización de estrellas 
        figure.mb-0
          img.mb-3(src="@/assets/curso/tema2/img06.png", alt="En la figura 1 se enuncian los criterios de evaluación para el otorgamiento y categorización de estrellas en los hoteles de acuerdo a la norma NTSH006.").d-none.d-lg-block
          img.mb-3(src="@/assets/curso/tema2/img07.png", alt="En la figura 1 se enuncian los criterios de evaluación para el otorgamiento y categorización de estrellas en los hoteles de acuerdo a la norma NTSH006.").d-block.d-lg-none
        figcaption <strong>Nota.</strong> SENA, (2026).


    
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
