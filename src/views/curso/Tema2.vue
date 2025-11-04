<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2.Plan de <em>marketing</em>'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-1.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema2/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") El plan de <em>marketing</em> constituye una estrategia clave que permite a las empresas identificar con claridad su público objetivo, crear campañas eficaces y lograr un sólido posicionamiento de marca. Un plan bien diseñado ayuda a diferenciarse en el mercado, optimiza la relación con los clientes e impulsa el crecimiento de las ventas.

    h2(data-aos="fade-left") Componentes principales del plan de <em>marketing</em>
    p.mb-5 Para alcanzar eficazmente a la audiencia deseada, el plan debe contemplar estrategias tanto tradicionales como digitales, distribuidas en los siguientes componentes:

    .row.align-items-center.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/2.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") 
        
        LineaTiempoD.color-primario.large(data-aos="fade-left")
          div(numero="1" titulo="Análisis de mercado") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Identificación de audiencia objetivo.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Análisis de competencia y tendencias.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Segmentación según características demográficas y comportamiento.
          div(numero="2" titulo="Definición de objetivos") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Reconocimiento de marca.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Captación de nuevos clientes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Fidelización y retención de clientes. 
          div(numero="3" titulo="<em>Marketing</em> tradicional") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Publicidad impresa, radio y TV.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Ferias comerciales y eventos.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Estrategias boca a boca y alianzas estratégicas. 
    
    .row.align-items-center.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/3.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8
        p(data-aos="fade-left") 
        
        LineaTiempoD.color-primario.large(data-aos="fade-left")
          div(numero="4" titulo="<em>Marketing</em> digital") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>SEO:</b> Optimización en buscadores.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Redes sociales:</b> Campañas en Facebook, Instagram, LinkedIn.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Email <em>marketing</em>:</b> Automatización de mensajes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Publicidad (PPC):</b> Anuncios en Google y redes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Contenido:</b> Blogs, videos educativos y materiales de valor.
          div(numero="5" titulo="Estrategia de marca") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Identidad visual (logotipo, colores).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Mensajes clave y valores.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Diferenciación frente a competencia. 
          div(numero="6" titulo="Comunicación y promoción") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Definición de canales de difusión.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Frecuencia y formatos de publicación.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Promociones, descuentos y fidelización.
          div(numero="7" titulo="Medición y análisis") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 KPIs: Conversión, ROI, engagement.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Herramientas: Google Analytics, Facebook Business.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 Ajustes basados en datos.
    
    h2(data-aos="fade-left") Paso a paso para elaborar y aplicar un plan de marketing
    p.mb-5 La elaboración del plan debe seguir una secuencia lógica para lograr óptimos resultados:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/4.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Investigar mercado y competencia
              p Usar encuestas, análisis de tendencias y herramientas digitales como Google Trends y SEMrush para reunir información sobre la industria y los consumidores.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/5.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Definir objetivos SMART
              p Establecer metas específicas, medibles, alcanzables, relevantes y con tiempo definido, como aumentar el tráfico web en un 20% en seis meses o captar 500 nuevos clientes trimestrales.

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/6.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Seleccionar canales adecuados
              p Elegir los medios en los que interactúe la audiencia objetivo, como redes sociales, email <em>marketing</em> o medios tradicionales.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/7.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Crear mensajes y contenido específicos
              p Elaborar publicaciones atractivas, campañas publicitarias efectivas y contenido relevante, como blogs educativos o videos demostrativos.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/8.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Implementar estrategias tradicionales y digitales
              p Ejecutar campañas en redes sociales, realizar eventos presenciales y aplicar promociones tanto en tiendas físicas como digitales.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/9.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Medir rendimiento y ajustar estrategias
              p Analizar el comportamiento de los consumidores, interpretar métricas clave y optimizar la inversión publicitaria en cada canal.
    
    h2(data-aos="fade-left") Ejemplo práctico: Caso Tesla
    p.mb-5 Tesla revolucionó el sector automotriz con una estrategia innovadora, alejándose del marketing tradicional e invirtiendo principalmente en acciones digitales y eventos exclusivos.

    .row.justify-content-center.align-items-stretch.mb-3
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/10.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 SEO y <em>marketing</em> de contenido	
              p.mb-0 Elon Musk genera contenido viral, noticias en redes sociales sin inversión publicitaria directa.

      .col-lg-4.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/11.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Estrategia de marca	
              p.mb-0 Valores clave: innovación tecnológica y sostenibilidad.
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/12.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 <em>Marketing</em> digital	
              p.mb-0 Campañas en redes sociales, blogs y participación activa en foros tecnológicos.

    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/13.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 <em>Marketing</em> tradicional	
              p.mb-0 Eventos exclusivos y pruebas de conducción para potenciales clientes.

      .col-lg-4.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/14.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Medición de resultados		
              p.mb-0 Análisis constante de datos para mejorar experiencia y aumentar retención de clientes.
    
    .bg-full-width.bg-h85
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
                p.mb-0.text-white.mt-5 Este enfoque permitió a Tesla posicionarse como una de las marcas más innovadoras y reconocidas a nivel mundial, sin depender de publicidad convencional. Este nivel detallado y práctico ayuda a los estudiantes a comprender claramente la estructura de un plan de marketing completo, además de ofrecer un referente real de éxito empresarial contemporáneo.
              .col-lg-5(data-aos="zoom-in").order-lg-1
                img.img-fluid(src='@/assets/curso/tema2/15.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.revistasice.com/index.php/CICE/article/view/6031/6031" target="_blank" rel="noopener noreferrer") De Castro Emilio Cerdá, F. J. A. L. M. (s/f). Las energías renovables en el ámbito internacional. Revistasice.com. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://www.un.org/spanish/esa/sustdev/agenda21/riodeclaration.htm" target="_blank" rel="noopener noreferrer") De Janeiro, R. (1992). La declaración del Río sobre el Medio Ambiente y el Desarrollo. Río de Janeiro República Federativa del Brasil., aprobada en Estocolmo el, 16.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/QKLjwCMyv3M?si=uAWhO9tnyghljaJg" target="_blank" rel="noopener noreferrer") Innovación y sostenibilidad.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
