<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Indicadores del marketing'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-1.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema4/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") Los indicadores de <em>marketing</em> son métricas clave utilizadas para medir el desempeño de las estrategias de mercadeo y su impacto en el crecimiento empresarial. Su función principal es evaluar la efectividad de las campañas, la rentabilidad de las inversiones en publicidad y la interacción del público con la marca. Gracias a estos indicadores, las empresas pueden tomar decisiones basadas en datos, optimizar estrategias y mejorar la conversión de clientes.
    
    p.mb-4 En el siglo XXI, la integración de estos indicadores con los estados financieros es una necesidad. No solo permiten medir la eficacia de una campaña, sino que también impactan directamente en la sostenibilidad financiera de una organización.

    h2(data-aos="fade-left") Importancia de los indicadores de <em>marketing</em>
    p.mb-5 Los indicadores de <em>marketing</em> ofrecen múltiples beneficios para la toma de decisiones estratégicas:

    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-2.order-lg-1
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-4
                    p.mb-0 <b>Decisiones basadas en datos.</b> Permiten evaluar qué estrategias funcionan mejor y cuáles requieren ajustes.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-4
                    p.mb-0 <b>Medición del retorno de inversión (ROI).</b> Ayudan a determinar la rentabilidad de cada acción <em>de market</em>ing.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-4
                    p.mb-0 <b>Optimización de campañas.</b> Facilitan la identificación de los canales más efectivos para captar y fidelizar clientes.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-4
                    p.mb-0 <b>Segmentación de audiencia.</b> Brindan información detallada sobre el comportamiento y preferencias del consumidor.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-4
                    p.mb-0 <b>Impacto financiero.</b> Relacionan el costo de adquisición de clientes con su valor para la empresa.
              .col-lg-4(data-aos="zoom-in").order-1.order-lg-2.mb-3.mb-lg-0
                img.img-fluid(src='@/assets/curso/tema4/2.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-4 Los principales indicadores de <em>marketing</em> son: 

    .row.align-items-center.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/3.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8
        p(data-aos="fade-left") 
        
        LineaTiempoD.color-primario.large(data-aos="fade-left")
          div(numero="1" titulo="Adquisición de clientes") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 C<b>osto de Adquisición de Cliente (CAC):</b> Inversión necesaria para obtener un nuevo cliente. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Tasa de conversión:</b> Porcentaje de visitantes o prospectos que se convierten en clientes. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Tráfico web:</b> Número de personas que visitan el sitio web de la empresa.
          div(numero="2" titulo="Comportamiento y compromiso") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Tasa de rebote:</b> Porcentaje de usuarios que abandonan una página sin interactuar. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Tiempo en el sitio:</b> Duración promedio de navegación en la web de la empresa. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Engagement en redes sociales:</b> Nivel de interacción del usuario con el contenido digital de la marca.
          div(numero="3" titulo="Retención y fidelización") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Valor de Vida del Cliente (LTV):</b> Ingresos proyectados que un cliente generará durante toda su relación con la empresa. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Tasa de retención:</b> Porcentaje de clientes que continúan comprando después de la primera adquisición. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Índice de satisfacción del cliente (NPS):</b> Probabilidad de que un cliente recomiende la marca.
          div(numero="4" titulo="Indicadores financieros") 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Retorno de Inversión en Marketing (ROMI):</b> Ganancia obtenida por cada unidad monetaria invertida en marketing. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Costo por Lead (CPL):</b> Costo promedio de generar un prospecto interesado en el producto o servicio. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-4
                p.mb-0 <b>Participación en el mercado:</b> Comparación del volumen de ventas de la empresa con el de sus competidores.
    
    h2.mb-5(data-aos="fade-left") Conexión entre indicadores de marketing y los estados financieros

    
    .row.mb-5.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema4/4.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") <b>El Costo de Adquisición de Cliente (CAC) y el Retorno de Inversión en Marketing (ROMI)</b> son métricas clave que deben reflejarse en los estados financieros de una empresa. Según las International Financial Reporting Standards (IFRS), la transparencia en la información financiera es crucial, lo que incluye métricas de marketing que afectan la rentabilidad del negocio.
    
        .bg-color-3.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema4/5.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El <b>Cuadro de Mando Integral (CMI)</b> es una metodología ampliamente utilizada en la gestión empresarial, la cual integra indicadores financieros y no financieros. Su objetivo es alinear las estrategias de marketing con los objetivos financieros, permitiendo una visión más integral del negocio.
        p(data-aos="fade-left") Los paso a paso para implementar indicadores de marketing en una empresa son: 

    .bg-full-width-1.bg-fondo-2
      .px-4.px-md-5
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-lg-2
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema4/7.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Definir objetivos claros
                p.text-center Establecer qué se quiere lograr con las estrategias de marketing (aumento de ventas, fidelización de clientes, mejora de imagen de marca, etc.).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema4/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Seleccionar los indicadores más relevantes
                p.text-center Elegir los KPIs que mejor reflejen el desempeño de la estrategia aplicada.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema4/9.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Utilizar herramientas de análisis de datos
                p.text-center Emplear plataformas como Google <em>Analytics</em>, Facebook Business Manager y HubSpot para medir el desempeño de las campañas.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema4/10.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Monitorear continuamente los resultados
                p.text-center Evaluar métricas en tiempo real y realizar ajustes estratégicos según el comportamiento del mercado.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema4/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Optimizar estrategias
                p.text-center Usar los indicadores para modificar anuncios, segmentación de clientes y presupuesto asignado a marketing.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema4/12.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Integrar los resultados en los estados financieros
                p.text-center Presentar el impacto del marketing en los informes financieros para respaldar decisiones informadas.
    
          .col-lg-4.order-lg-1
            figure
              img(src='@/assets/curso/tema4/6.png', alt='')
    
        h2(data-aos="fade-left") Ejemplo de aplicación: Netflix y su uso de indicadores de marketing
        p.mb-5 Netflix es una de las empresas que mejor utiliza los indicadores de marketing para mejorar sus estrategias y ofrecer contenido personalizado a sus usuarios.

    .bg-full-width.bg-fondo-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-12
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema4/13.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="8.2%" y="32.3%" numero="+")
                h5 Segmentación de audiencia
                p Netflix analiza patrones de consumo para personalizar las recomendaciones de contenido según el usuario.
    
              .bg-color-white.box-shadow.p-3(x="7%" y="54.5%" numero="+")
                h5 <em>Engagement</em> en plataforma
                p Evalúa cuánto tiempo los usuarios pasan viendo contenido y qué tipo de series o películas prefieren.
    
              .bg-color-white.box-shadow.p-3(x="78.2%" y="29.2%" numero="+")
                h5 Retención de clientes
                p Mide la tasa de cancelación de suscripciones y ajusta su estrategia de contenido y promociones.
    
              .bg-color-white.box-shadow.p-3(x="78.2%" y="50.3%" numero="+")
                h5 ROI en campañas digitales
                p Analiza la efectividad de los anuncios en redes sociales y otros medios digitales para atraer nuevos suscriptores.
    
    .bg-full-width.bg-color-25
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema4/14.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0.text-white Gracias a su enfoque basado en datos y a la optimización de estrategias mediante indicadores de marketing, Netflix ha logrado mantenerse como líder en la industria del streaming.
    
    .bg-full-width.bg-color-2.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Tipos de sociedades
            p.mb-4(data-aos="fade-right") Los invitamos a leer <b>Tipos de sociedades</b>, un análisis detallado sobre las diferentes estructuras legales disponibles para emprendedores y empresarios en Colombia. En este documento, se explican los beneficios, responsabilidades y aplicaciones recomendadas de cada tipo de sociedad, facilitando la toma de decisiones estratégicas para cualquier negocio.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Tipos de sociedades.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema4/15.png', alt='')


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.scotiabankcolpatria.com/educacion-financiera/finanzas-maestras/tipos-de-sociedades" target="_blank" rel="noopener noreferrer") Scotiabank Colpatria. (s.f.). Los tipos de sociedades que debe conocer. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=lWk0t4FPoLg&ab_channel=UniversidadIcesi" target="_blank" rel="noopener noreferrer") Universidad Icesi (2024, 16 de mayo). Endomarketing: Descifrando la marca empleadora como ser vivo. [Video]. Youtube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
export default {
  name: 'Tema4',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
