<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Estudio financiero
      
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-5.mb-3(data-aos="fade-right")
        img.mt-3.mx-auto.img-responsive(src='@/assets/curso/tema5/img_9.png'  alt='')
      .col-lg-7.mb-3(data-aos="fade-left")         
        p.mb-3 El aspecto financiero es el que nos va a mostrar la viabilidad del proyecto o no, para ello se utilizan una serie de herramientas financieras que podemos comparar con las de otros proyectos y así poder tomar la decisión de implementar el proyecto.
        h4 Para poder contar con las herramientas de evaluación, este estudio se divide en dos partes que son:
        
        ul.lista-ul--cuadro.lista-ul.color-primario
          li 
            .lista-ol--cuadro__vineta
              span A
            | La organización metódica y presentación de los costos de producción y los ingresos del proyecto agropecuario.
          li 
            .lista-ol--cuadro__vineta
              span B
            | La evaluación financiera del proyecto utilizando Valor Presente Neto (VPN), Tasa Interna de Retorno (TIR) y relación Beneficio / Costo (B/C).

    .row.justify-content-center.align-items-center.mb-2(date-aos="fade-zoom-in")
      .col-lg-12.mb-5
        .bloque-texto-g.bloque-texto-g--inverso.bg-93.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema5/img_2.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 En esta primera parte se va a trabajar la organización metódica (organizada) de los costos de producción y los ingresos del proyecto. El año uno o año cero es el momento en el que se realizan las inversiones iniciales del proyecto cuando se comienza a invertir en adecuaciones de terrenos, construcciones agrícolas o pecuarias, compra de semilla o semovientes, etc.; periodo de inversión o montaje.

    p.mb-5 En el análisis de los costos lo primero es identificar los dos tipos de costos que existen: costos fijos son aquellos que no cambian según el nivel de producción, por ejemplo, arriendo, vigilancia, depreciación de máquinas o seguros y los costos variables son los que aumentan o disminuyen dependiendo del volumen de producción como mano de obra, insumos, semilla, pie de cría, concentrado, vacunas, fertilizantes, etc.

    
    .row
      .col-12.col-lg-10.mx-auto
        p.mb-5 
          b Para la elaboración de la tabla de costos en la herramienta ofimática Excel debe tener en cuenta la siguiente clasificación de costos:

        .align-items-center.justify-content-star.mb-1.ps-2(data-aos="zoom-in-down")
          //- Subtitulo
          .align-items-center.justify-content-star.mb-2
            .div(data-aos="fade-left")
              h3.subtitle.position-relative Costos fijos
                img.image(src='@/assets/curso/tema1/img_62.svg', alt='Imagen decorativa')
          
        p.mb-4 Arriendo, sueldos administrativos, servicios públicos, amortizaciones, vigilancia, seguros, etc. Se mantienen más o menos constantes y generalmente no cambian en proporción directa con las ventas o unidades producidas.
                    
        .row.justify-content-center.mb-5
          .col-12
            .tarjeta-avatar-b.mb-3
              .tarjeta-avatar-b__img
                img.mx-auto(src='@/assets/curso/tema1/icon-tarjeta.svg' alt='', style="width: 100px;")
              .tarjeta.bg-tarjeta.align-content-center
                .row.align-items-center.justify-content-center.p-4
                  .col.mb-3.mb-sm-0
                    h4.mb-1 Tabla 2.
                    p.mb-0 Para ampliar la información acerca de costos fijos de proyecto asociado a sistema agroforestal de cacao, plátano y maderable, se invita a que acceda al material.
                  .col-sm-auto
                    a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo2_Tabla_2_Costos_fijos.xlsx')" target="_blank")
                      span Consultar tabla
                      i.fas.fa-file-excel
                      
    
        .row.align-items-center.justify-content-star.mb-1.ps-2(data-aos="zoom-in-down")
          //- Subtitulo
          .align-items-center.justify-content-star.mb-2
            .div(data-aos="fade-left")
              h3.subtitle.position-relative Costos variables
                img.image(src='@/assets/curso/tema1/img_62.svg', alt='Imagen decorativa')
            
          p.mb-3 Son aquellos que cambian en proporción directa con los volúmenes de producción y ventas, por ejemplo: materias primas, mano de obra a destajo, comisiones, semilla, pie de cría, concentrado, vacunas, fertilizantes, etc. Jiménez, 2010, p. 25.

          .row.justify-content-center.mb-5
            .col-12
              .tarjeta-avatar-b.mb-3
                .tarjeta-avatar-b__img
                  img.mx-auto(src='@/assets/curso/tema1/icon-tarjeta.svg' alt='', style="width: 100px;")
                .tarjeta.bg-tarjeta.align-content-center
                  .row.align-items-center.justify-content-center.p-4
                    .col.mb-3.mb-sm-0
                      h4.mb-1 Tabla 3.
                      p.mb-0 Para ampliar la información acerca de costos variables y análisis de costos e ingresos del proyecto cacao asociado a plátano, se invita a que acceda al material.
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo3_Tabla_3_Costos_variables.xlsx')" target="_blank")
                        span Consultar tabla
                        i.fas.fa-file-excel
                        
          .row.align-items-center.justify-content-center.mb-4
            .col-lg-10.mb-2(data-aos="fade-left")         
              .cajon.bg-99.p-4.ps-5.mb-5.mb-lg-3
                p.mb-2 El siguiente paso es la elaboración de los ingresos de los productos que se van a producir en la explotación; para ello se debe tener en cuenta el año de inicio de la producción, volúmenes iniciales (cantidad) de producción, unidad de medida que fue establecida para el proyecto y precio de venta.
                p.mb-2 Se establece que este análisis de costos e ingresos se proyecta a cinco (5) años, que sería el periodo por evaluar en el proyecto.
    


                  
    Separador

    #t_5_1.titulo-segundo.color-acento-contenido
      .h2(data-aos="fade-right") 5.1 Flujo de caja 
      
    .row.justify-content-center.align-items-center.mb-2(data-aos="fade-zoom-in")
      .col-lg-4.mb-5.align-items-center.justify-content-center
        .tarjeta.bg-04.p-4
          p.mb-0 Una forma sencilla para definir el flujo de caja puede darse como, la diferencia que existe entre las entradas (ingresos) y las salidas (egresos) de dinero o efectivo que tiene la empresa en un tiempo determinado (año). Por medio de este indicador se muestra el dinero que entra y sale en toda la operación del proyecto.
          p.mb-0 El flujo de caja para Mendieta (2005), posee cuatro elementos básicos que componen el flujo de fondos son:
      
      .col-lg-8.mb-5.align-items-center.justify-content-center
        .row.justify-content-center.align-items-stretch
          .col-lg-6.mb-2.d-flex
            .tarjeta-avatar-b.mb-3.w-100
              .tarjeta-avatar-b__img(style="z-index: 2;")
                img.img-t.m-auto.mt-2(src='@/assets/curso/tema5/img_3.svg', alt='')
              .tarjeta.bg-98.shadow-sm.position-relative.h-100.d-flex.align-items-center.w-100
                .p-3
                  p.pe-4.mb-0 Los beneficios (ingresos) de operación.
                h2.mb-0.position-absolute(style="bottom: 5px; right: 15px; color: #647A84;") A
          
          .col-lg-6.mb-2.d-flex
            .tarjeta-avatar-b.mb-3.w-100
              .tarjeta-avatar-b__img(style="z-index: 2;")
                img.img-t.m-auto.mt-2(src='@/assets/curso/tema5/img_4.svg', alt='')
              .tarjeta.bg-94.shadow-sm.position-relative.h-100.d-flex.align-items-center.w-100
                .p-3
                  p.pe-4.mb-0 Los costos (egresos) de inversión o montaje, o sea, los costos iniciales.
                h2.mb-0.position-absolute(style="bottom: 5px; right: 15px; color: #4F647A;") B
          
          .col-lg-6.mb-2.d-flex
            .tarjeta-avatar-b.mb-3.w-100
              .tarjeta-avatar-b__img(style="z-index: 2;")
                img.img-t.m-auto.mt-2(src='@/assets/curso/tema5/img_5.svg', alt='')
              .tarjeta.bg-98.shadow-sm.position-relative.h-100.d-flex.align-items-center.w-100
                .p-3
                  p.pe-4.mb-0 Los costos (egresos) de operación.
                h2.mb-0.position-absolute(style="bottom: 5px; right: 15px; color: #647A84;") C
          
          .col-lg-6.mb-2.d-flex
            .tarjeta-avatar-b.mb-3.w-100
              .tarjeta-avatar-b__img(style="z-index: 2;")
                img.img-t.m-auto.mt-2(src='@/assets/curso/tema5/img_6.svg', alt='')
              .tarjeta.bg-94.shadow-sm.position-relative.h-100.d-flex.align-items-center.w-100
                .p-3
                  p.pe-4.mb-0 El valor de desecho o salvamento de los activos del proyecto.
                h2.mb-0.position-absolute(style="bottom: 5px; right: 15px; color: #4F647A;") D
          

    .row.justify-content-center.align-items-center.mb-3
      .col-md-12
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Tabla 4. 
          span Presentación matricial del flujo de fondos
        
        .tabla-b.color-acento-botones.mb-5 
          table
            caption Nota. <span style="font-weight: normal !important;">Tomado de Formulación y evaluación de proyectos de inversión agropecuaria (2005) p 161.</span>
            thead
              tr.encabezado_tabla
                th 
                th Año 0
                th Año 1
                th Año 2 - Año (T-1)
                th Año T

            tbody 
              tr
                td.text-start(style="width: 23%") INGRESOS
                td -
                td -
                td -
                td -
              tr
                td.text-start.negrita Ventas
                td -
                td -
                td -
                td -
              tr
                td.text-start.negrita Producto 1
                td.text-end $ 0
                td.text-end $ 0
                td.text-end $ 120.000
                td.text-end $ 120.000
              tr
                td.text-start.negrita Producto 2
                td.text-end $ 0
                td.text-end $ 100.000
                td.text-end $ 150.000
                td.text-end $ 150.000
              tr
                td.text-start.negrita Subsidio
                td.text-end $ 500.00
                td.text-end $ 100.000
                td.text-end $ 0
                td.text-end $ 0
              tr
                td.text-start.negrita Valor de salvamento
                td.text-end -
                td.text-end -
                td.text-end -
                td.text-end $ 300.000
              tr.negrita(style="background-color: #D8E9FB")
                td.text-start Total ingresos
                td.text-end $ 500.000
                td.text-end $ 200.000
                td.text-end $ 270.000
                td.text-end $ 570.000
              tr.encabezado_tabla
                td.text-start COSTOS
                td -
                td -
                td -
                td -
              tr
                td.text-start.negrita Operación
                td -
                td -
                td -
                td -
              tr
                td.text-start.negrita Materiales
                td.text-end $ 600.000
                td.text-end $ 30.000
                td.text-end $ 50.000
                td.text-end $ 50.000
              tr
                td.text-start.negrita Mano de obra
                td.text-end $ 0
                td.text-end $ 30.000
                td.text-end $ 60.000
                td.text-end $ 60.000
              tr.negrita(style="background-color: #D8E9FB")
                td.text-start Total costos deducibles
                td.text-end $ 600.000
                td.text-end $ 60.000
                td.text-end $ 110.000
                td.text-end $ 110.000
              tr.negrita.encabezado_tabla
                td.text-start Ingresos netos gravables
                td.text-end $ -100.000
                td.text-end $ 140.000
                td.text-end $ 160.000
                td.text-end $ 460.000
          
      p.mb-3 Como se presenta en la tabla el flujo de caja está compuesto básicamente por ingresos y costos de inversión, operación y mantenimiento y los valores de salvamento, según Mendieta (2005), las siguientes son las características de ingresos y costos:
      
    .row.justify-content-center.align-items-center.mb-2
      .col-md-12.mb-3(data-aos="fade-zoom-in")
        LineaTiempoD.color-acento-contenido.mb-4
          .row(numero="1" titulo="Ingresos").justify-content-center.align-items-center
            .col-md-12.col-lg-7.mb-lg-4.mb-md-2
              p Es el dinero percibido por la venta del producto o productos que deben ser registrados en el año que se efectúa la venta; se debe anotar que los ingresos registrados en el flujo de fondos del proyecto deben incluir, tanto los ingresos operativos (por venta del producto o prestación del servicio) como los ingresos financieros (por inversión de reserva, por ejemplo). Mendieta, 2005 p. 162.
      
            .col-md-8.col-lg-5
              figure
                img(src='@/assets/curso/tema5/img_7.png', alt='Texto que describa la imagen')

          .row(numero="2" titulo="Costos").justify-content-center.align-items-center
            .col-md-12.col-lg-7.mb-lg-4.mb-md-2
              p Se clasifican en dos categorías, la primera es de costos de inversión que consisten en desembolsos correspondientes a la adquisición de activos fijos o activos nominales y a la financiación del capital de trabajo. Los costos por adquisición de activos fijos que representan los desembolsos por compra de terrenos y edificios, es decir, pago de obras civiles y compra de equipo, maquinaria y obras de instalación o apoyo. Los costos por concepto de activos nominales corresponden a inversiones en activos no tangibles, pero necesarios para poner a funcionar el proyecto, tramitación de patentes como licencias; transferencias de tecnología, además de asistencia técnica; gastos de constitución y organización; así como la capacitación y entrenamiento. Mendieta, 2005 p. 163.
      
            .col-md-8.col-lg-5
              figure
                img(src='@/assets/curso/tema5/img_8.png', alt='Texto que describa la imagen')
          
        p.mb-3 La segunda categoría son los costos de operación que consisten en los desembolsos por insumos y otros rubros necesarios para el ciclo productivo del proyecto a lo largo de su funcionamiento. Estos costos se pueden clasificar en costos de producción de ventas, administrativas y financieras, los cuales a su vez se desagregan, entre otros, en costos de mano de obra, materias primas e insumos, arriendos y alquileres, como costos financieros e impuestos. Mendieta, 2005 p. 164.
      
      .col-lg-10.mb-2(data-aos="fade-zoom-in")     
        .cajon.bg-96.p-4.ps-5.bg_18.mb-5.mb-lg-3
          p.mb-2 Con esta información ya es posible generar las tablas de ingresos, egresos y flujo de caja que nos sirven de insumo para la tercera etapa de proyectos que es, la evaluación financiera donde se determinarán indicadores tales como Tasa Interna de Retorno (TIR) y Valor Presente Neto (VPN).
    
</template>

<script>
export default {
  name: 'Tema5',
  components: {},
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
