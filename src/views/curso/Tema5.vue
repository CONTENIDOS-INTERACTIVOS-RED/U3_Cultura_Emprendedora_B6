<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'5.	Propiedad Intelectual en Colombia en el Siglo XXI'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema5/1.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") La <b>propiedad intelectual</b> protege las creaciones del intelecto humano, incluyendo invenciones, marcas, diseños industriales, derechos de autor y secretos empresariales. En Colombia, la normativa sobre propiedad intelectual se ha fortalecido en el siglo XXI con el fin de incentivar la innovación y resguardar los activos intangibles de empresas y emprendedores.
    
        .bg-color-11.p-4.mb-5(data-aos="fade-left")
          p.mb-0 Este tema busca que los estudiantes comprendan la importancia de la propiedad intelectual en el desarrollo empresarial, identifiquen los mecanismos de protección disponibles y aprendan a gestionar estos derechos dentro del marco legal colombiano.
        p(data-aos="fade-left") La importancia de la propiedad intelectual es: 
    
    .row.justify-content-center.align-items-stretch.mb-3
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Protección legal
              p.mb-0 Evita la copia o el uso no autorizado de creaciones.

      .col-lg-6.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Ventaja competitiva
              p.mb-0 Resguarda los activos intangibles, aumentando el valor de la empresa.
    .row.justify-content-center.align-items-stretch.mb-3
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/4.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Fomento de la innovación	
              p.mb-0 Incentiva la investigación y el desarrollo de nuevas ideas.

      .col-lg-6.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/5.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Acceso a financiación	
              p.mb-0 Puede utilizarse como garantía para inversionistas o bancos.
    
    h2(data-aos="fade-left") Normativa Colombiana Vigente
    p.mb-5 La propiedad intelectual en Colombia está regulada por diferentes entidades y leyes:

    .bg-full-width-1.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-3.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema5/6.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Superintendencia de Industria y Comercio (SIC)
                p.mb-0 Registra y protege marcas, patentes y diseños industriales.
          .col-lg-3.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema5/7.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Dirección Nacional de Derechos de Autor (DNDA)
                p.mb-0 Protege obras literarias, artísticas, científicas y <em>software</em>.
          .col-lg-3.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema5/8.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Decisión 486 de la Comunidad Andina
                p.mb-0 Régimen común sobre propiedad industrial aplicable en Colombia, Ecuador, Perú y Bolivia.
          .col-lg-3.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema5/9.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Ley 1915 de 2018
                p.mb-0 Reforma del régimen de derechos de autor y derechos conexos en Colombia.
    
    p.mb-4 Los tipos de propiedad intelectual y su aplicación con ejemplos son: 

    .titulo-figura.mb-4
      h5 Tabla 1.
      span Tipos de propiedad intelectual
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr
            th.bg-color-26 Tipo de protección
            th.bg-color-26 Características
            th.bg-color-26 Ejemplo en Colombia
        tbody
          tr
            th.text-bold Derechos de autor
            td 
              p.mb-0 Protege obras literarias, artísticas, científicas y software. 
              p.mb-0 <b>Duración:</b> Vida del autor + 80 años.
            td Cien años de soledad, de Gabriel García Márquez, cuyos derechos protegen su comercialización y regalías.
          tr
            td.text-bold Patentes
            td 
              p.mb-0 Protege invenciones o mejoras tecnológicas. 
              p.mb-0 <b>Duración:</b> 20 años.
            td LifePack, empresa colombiana que patentó su tecnología de empaques biodegradables con semillas.
          tr
            td.text-bold Marcas y nombres comerciales
            td
              p.mb-0 Protege signos distintivos de productos o servicios. 
              p.mb-0 <b>Duración:</b> 10 años, renovables.
            td Juan Valdez, marca registrada por la Federación Nacional de Cafeteros.
          tr
            td.text-bold Diseños industriales
            td 
              p.mb-0 Protege la apariencia estética de un producto. 
              p.mb-0 <b>Duración:</b> 10 años.
            td TOTTO, empresa colombiana que registró el diseño de sus maletas para evitar copias.
          tr
            td.text-bold Secretos empresariales
            td
              p.mb-0 Protege información confidencial con valor comercial. 
              p.mb-0 <b>Duración:</b> Indefinida (mientras se mantenga en secreto).
            td La receta secreta de Colombiana de Postobón, protegida como secreto industrial.
    
     

    .bg-full-width-1.bg-fondo-2
      .px-4.px-md-5
        p.mb-5 El paso a paso para registrar la propiedad intelectual en Colombia son:
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-lg-2
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Identificar el tipo de protección
                p.text-center Determinar si la creación requiere protección como marca, patente, diseño industrial o derecho de autor.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Verificar la disponibilidad
                p.text-center Consultar las bases de datos de la <b>Superintendencia de Industria y Comercio (SIC)</b> para evitar conflictos con registros previos.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Preparar la documentación
                p.text-center Reunir los formularios y descripciones técnicas necesarias según el tipo de registro.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Solicitar el registro
                p.text-center Radicar la solicitud ante la SIC o la Dirección Nacional de Derechos de Autor (DNDA) según corresponda.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Seguimiento y mantenimiento
                p.text-center Una vez aprobado, es clave renovarlo o actualizarlo según las normativas vigentes para mantener la protección.
    
          .col-lg-4.order-lg-1
            figure
              img(src='@/assets/curso/tema5/10.png', alt='')
    
    h2.mb-5(data-aos="fade-left") Ejemplo de aplicación: Marca Colombiana "Juan Valdez"

    .bg-full-width.bg-h85
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                p.mb-0.text-white.mt-5 La marca <b>Juan Valdez</b>, registrada por la <b>Federación Nacional de Cafeteros de Colombia</b>, es un caso exitoso de gestión de propiedad intelectual. Su registro ha permitido proteger su identidad, expandirse internacionalmente y generar confianza entre los consumidores, consolidando el café colombiano como un producto premium en el mercado global.
              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema5/12.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .bg-full-width.bg-color-2.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.order-2
            h2.mb-4(data-aos="flip-up") Registro de Marca
            p.mb-4(data-aos="fade-right") Los invitamos a leer <b>Registro de Marca</b>, un análisis detallado sobre la importancia de proteger la identidad comercial de un negocio. En este documento se explican los tipos de marcas que pueden registrarse, el marco normativo en Colombia y el paso a paso del proceso ante la Superintendencia de Industria y Comercio (SIC).
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_2.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Registro de Marca.
    
          .col-lg-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/13.png', alt='')


    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://ojs.austral.edu.ar/index.php/ripi" target="_blank" rel="noopener noreferrer") Rodríguez-Jaime, J. (2024). ¿Derecho de autor y censura periodística en Colombia? Un análisis de los desafíos jurídicos por el uso de videos y fotografías con relevancia noticiosa. Revista Iberoamericana de la Propiedad Intelectual, (11), 11-62. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=LjqiooEktzs&ab_channel=LeFil" target="_blank" rel="noopener noreferrer") LeFil (2024, 5 de Agosto). Tendencias de Marketing para 2025. [Video]. Youtube.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema5',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto: '¿Cuál es el principal objetivo de un plan de negocios? ',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Definir los colores y el diseño del logotipo de la empresa. ',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Establecer la estructura financiera y operativa de un negocio.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Realizar encuestas de satisfacción de los clientes. ',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Elaborar únicamente estrategias de marketing. ',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto: '¿Qué se entiende por etnomarketing? ',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'La adaptación de estrategias de marketing según las características culturales de un mercado. ',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'La publicidad masiva sin segmentación de público. ',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto:
                  'El uso exclusivo de redes sociales para vender productos. ',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'La gestión financiera de las empresas en mercados internacionales.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto: '¿Cuál de los siguientes NO es un indicador de marketing? ',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Costo de Adquisición de Cliente (CAC). ',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Retorno de Inversión en Marketing (ROMI). ',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Tasa de Conversión.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Estado de Resultados de la empresa. ',
                esCorrecta: true,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué tipo de sociedad permite un solo socio y ofrece flexibilidad en su administración en Colombia?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Sociedad Anónima (S.A.). ',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Sociedad Colectiva. ',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Sociedad por Acciones Simplificada (S.A.S.). ',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Sociedad en Comandita Simple.',
                esCorrecta: true,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto: '¿Por qué es importante el registro de una marca? ',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Para asegurar la exclusividad y diferenciación en el mercado. ',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Para evitar que los empleados usen el logotipo de la empresa. ',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto:
                  'Para aumentar los costos administrativos de la empresa. ',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Para limitar la expansión del negocio.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
