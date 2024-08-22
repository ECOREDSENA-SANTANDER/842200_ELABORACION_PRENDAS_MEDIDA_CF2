<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      p Todas las personas son consumidoras de prendas de vestir, y dependiendo de sus necesidades y requerimientos escogen una prenda u otra, en este componente se detallan las características que pueden adquirir las prendas y diferentes procedimientos para cambiar el aspecto. El siguiente diagrama presenta los conceptos y temas más importantes trabajados dentro del componente.  
      .row.justify-content-center
        .col-lg-12.mb-5
          figure
            img(src="@/assets/curso/sintesis.svg", alt="el diagrama de flujo presenta el contenido de la unidad, describiendo cada tema y sus subtemas")
        .col-auto
          a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              p Anexo. Síntesis
  
  </template>

<script>
export default {
  name: 'Sintesis',
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
