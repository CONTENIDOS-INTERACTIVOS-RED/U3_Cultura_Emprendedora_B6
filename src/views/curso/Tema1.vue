<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Ejecución de plan emprendedor y gestión empresarial'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-11.p-3.h-100(data-aos="fade-left")
          p(data-aos="fade-left") Emprender no es solo tener una idea brillante, sino el arte de hacer que las cosas sucedan. Ejecutar un plan emprendedor implica transformar una visión en una realidad tangible mediante la planificación, acción y evaluación constante. Por otra parte, la gestión empresarial abarca el conjunto de estrategias y procesos que permiten administrar adecuadamente recursos, operaciones y objetivos empresariales, asegurando así sostenibilidad y crecimiento.
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/1.png" data-aos="zoom-in")
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-3.p-3.h-100(data-aos="fade-left")
          p(data-aos="fade-left") Desde tiempos antiguos, la humanidad ha buscado maneras de organizar y optimizar recursos para crear valor. Desde los comerciantes fenicios hasta las <em>startups</em> tecnológicas actuales, estructurar, ejecutar y administrar negocios ha resultado fundamental para la evolución económica. Hoy, en un mundo altamente competitivo en el que innovación y tecnología marcan la diferencia, es esencial contar con herramientas que faciliten la toma de decisiones y mejoren el desempeño empresarial.
    
    p.mb-5 En este módulo, se explorarán los aspectos clave relacionados con la ejecución efectiva de planes emprendedores y su adecuada gestión, con el fin de que estudiantes en cultura emprendedora comprendan la importancia de planificar, ejecutar y gestionar sus ideas de negocio con metodologías comprobadas y apoyadas por la inteligencia artificial.

    h2.mb-5(data-aos="fade-left") Importancia del plan de negocios
    
    .row
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema1/2.svg", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-2.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El plan de negocios constituye la hoja de ruta de cualquier emprendimiento, detallando objetivos, estrategias, análisis de mercado, estructura financiera y operativa de la empresa. Independientemente del sector económico, tamaño o mercado objetivo, contar con un plan de negocios resulta fundamental para reducir riesgos, evaluar la viabilidad del proyecto y optimizar recursos.
        p(data-aos="fade-left") Organizaciones como el Banco Mundial (2020) señalan que los emprendimientos con una planificación estructurada tienen hasta un 30% más posibilidades de éxito en comparación con aquellos que no lo tienen. Además, instituciones como la Administración de Pequeñas Empresas de EE. UU. (SBA) y el Instituto Nacional del Emprendedor de México (INADEM) destacan su importancia para acceder a financiamiento, atraer inversionistas y definir estrategias claras de crecimiento.
    
    .bg-full-width.bg-fondo-2
      .px-4.px-md-5.pb-md-3
        h2(data-aos="fade-left") Componentes clave del plan de negocios
        p.mb-5 Para construir un plan de negocios sólido, se recomienda la siguiente estructura organizada en una tabla:

        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-lg-2
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/5.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Resumen ejecutivo
                p.text-center Breve descripción del negocio, misión, visión, objetivos y propuesta de valor.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/6.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Descripción del negocio
                p.text-center Información detallada sobre la empresa, historia, modelo de negocio y mercado objetivo.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/7.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Análisis de mercado
                p.text-center Evaluación del sector, competencia, tendencias y oportunidades de crecimiento.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Plan de mercadeo
                p.text-center Estrategia para atraer clientes, posicionar la marca y generar ventas (ampliado en temas 3.3, 3.4 y 3.5).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/9.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Plan operativo
                p.text-center Definición de procesos internos, cadena de suministros y gestión del talento humano.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/10.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Plan financiero
                p.text-center Proyecciones económicas, análisis de costos, rentabilidad y estrategias de financiamiento.
    
          .col-lg-4.order-lg-1
            figure
              img(src='@/assets/curso/tema1/4.png', alt='')

    h2(data-aos="fade-left") Ejemplo real de la estructura de un plan de negocios
    p.mb-5 A continuación, se presenta un ejemplo práctico que orienta a los estudiantes sobre cómo estructurar adecuadamente un plan de negocios, tomando como referencia una idea emprendedora real: <b>Café Orgánico Vida Verde</b>.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/11.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Resumen ejecutivo
              p Empresa que ofrece café 100% orgánico y sostenible, producido en Colombia con certificación de comercio justo. Dirigida a consumidores conscientes del impacto ambiental y social.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/12.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Descripción del negocio
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Misión:</b> Proporcionar café de alta calidad, cultivado responsablemente y con impacto positivo en comunidades cafeteras.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Visión:</b> Ser la marca líder en café orgánico sostenible en América Latina para 2030.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Modelo de negocio:</b> Venta en tiendas físicas, plataformas digitales, supermercados y cafeterías ecológicas.

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/13.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Análisis de mercado
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Segmento:</b> Consumidores de productos orgánicos y sostenibles.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Competencia:</b> Juan Valdez, Starbucks, marcas artesanales.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Tendencias:</b> Crecimiento del mercado ecológico y mayor consumo de café premium.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/14.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Plan de mercadeo
              p Estrategias digitales en redes sociales, contenido educativo sobre café sostenible, programas de fidelización y alianzas con <em>influencers</em> especializados.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/15.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Plan operativo
              p Producción con proveedores locales certificados, envasado biodegradable y distribución mediante alianzas logísticas y venta en línea.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/16.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 financiero
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Inversión inicial:</b> $50,000 USD en infraestructura, insumos y marketing inicial.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Proyecciones:</b> $200,000 USD en ingresos el primer año.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-4
                  p.mb-0 <b>Financiamiento:</b> Crowdfunding y créditos orientados a pymes sostenibles.

    h2(data-aos="fade-left") Paso a paso para elaborar un plan de negocios
    p.mb-5 Para estructurar un plan de negocios efectivo se recomienda seguir este proceso detallado:

    .row.mb-5
      .col-lg-3.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/17.svg", data-aos="zoom-in")
      .col-lg-9
        .tabla-a.color-acento-botones
          table
            thead
              tr
                td.text-bold.bg-color-13(width='30%') Investigar y analizar el mercado	
                td.bg-color-14.p-4 Usar herramientas como encuestas, entrevistas y bases de datos económicas para comprender profundamente el mercado objetivo.
            tbody
              tr
                td.text-bold.bg-color-15 Definir la propuesta de valor	
                td.bg-color-16.p-4 Identificar qué distingue claramente al negocio frente a la competencia, destacando cómo beneficia específicamente al cliente.
              tr
                td.text-bold.bg-color-17 Establecer estrategias de marketing	
                td.bg-color-18.p-4 Basarse en estudios previos para desarrollar tácticas de promoción, captación y fidelización de clientes.
              tr
                td.text-bold.bg-color-19 Planificar la operatividad	
                td.bg-color-20.p-4 Diseñar procesos internos adecuados para garantizar una producción fluida o una prestación de servicios de calidad.
              tr
                td.text-bold.bg-color-21 Realizar proyecciones financieras		
                td.bg-color-22.p-4 Determinar costos, ingresos proyectados, rentabilidad esperada y necesidades específicas de financiamiento.
              tr
                td.text-bold.bg-color-23 Redactar y revisar el documento final	
                td.bg-color-24.p-4 Garantizar claridad, estructura y contenido convincente que sea atractivo para potenciales inversionistas o financiadores.
        




    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.sba.gov/es/guia-de-negocios/planifique-su-empresa/redacte-su-plan-de-negocios" target="_blank" rel="noopener noreferrer") U.S. Small Business Administration. (s.f.). Redacte su plan de negocios. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.scu.edu/mobiespanol/plantilla-del-plan-de-negocios-gratis/plantilla-del-plan-de-negocios-gratis/" target="_blank" rel="noopener noreferrer") Universidad de Santa Clara. (s.f.). Plantilla del Plan de Negocios GRATIS - MOBI @ SCU. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=eRwQdUxLHtk&ab_channel=Networkers4Life" target="_blank" rel="noopener noreferrer") Networkers 4Life (2025, 11 de enero). Plan de acción Pte 1 y Estrategia 2025. Dr Herminio Nevarez [Video].Youtube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
