<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.justify-content-center.mb-5
      .col-lg-12
        p.mb-0  El componente formativo Formulación de los componentes de estudio para proyectos agropecuarios, integra el análisis de mercado, técnico, administrativo, ambiental y financiero con el fin de determinar la viabilidad del proyecto. El estudio de mercado permite identificar y cuantificar la demanda insatisfecha, analizar las preferencias del consumidor, proveedores, normatividad y requisitos técnicos, sanitarios y legales, además de definir estrategias de mercadeo, segmentación de clientes y promoción del producto. El estudio técnico establece las condiciones operativas del sistema productivo, como la localización, el tamaño del proyecto, el proceso productivo, la organización y el cronograma de actividades, permitiendo valorar económicamente las variables técnicas. El estudio administrativo aporta herramientas de gestión mediante la planeación estratégica, misión, visión, objetivos, políticas, valores, análisis DOFA, organigrama y cumplimiento de la normatividad vigente. El estudio ambiental se orienta al uso adecuado de los recursos naturales, la gestión de residuos y la reducción de impactos negativos para promover prácticas sostenibles. Finalmente, el estudio financiero organiza costos e ingresos, analiza costos fijos y variables, proyecta el flujo de caja y aplica indicadores como VPN, TIR y relación beneficio-costo para evaluar la rentabilidad del proyecto.
        
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="En la síntesis de formulación de los componentes de estudio para proyectos agropecuarios son: estudio de mercado, estudio técnico, estudio administrativo, estudio ambiental y estudio financiero.")
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
