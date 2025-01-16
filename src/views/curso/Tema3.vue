<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Instrumentos de Gestión de la RSE'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-8       
        p(data-aos="fade-left") La Responsabilidad Social Empresarial  es un enfoque en el cual las empresas integran prácticas sostenibles y socialmente responsables en sus operaciones y estrategias, yendo más allá del cumplimiento legal para contribuir de manera positiva al bienestar social y ambiental. La puesta en marcha de RSE requiere el uso de herramientas y metodologías como la norma ISO 26000, así como la evaluación y medición de su impacto mediante indicadores clave de rendimiento. La adopción de RSE no solo mejora la reputación de la empresa, sino que también refuerza las relaciones con los empleados, inversores, clientes y comunidades, promoviendo un desarrollo sostenible y beneficios a largo plazo tanto para la sociedad como para la empresa misma.

      .col-lg-4.d-none.d-sm-block
        figure
          img(src="@/assets/curso/tema3/1.png", data-aos="zoom-in").mb-4.mb-lg-0
    
    .bg-full-width.bg-color-5.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.order-2
            h2.mb-4(data-aos="flip-up") Políticas y prácticas de Responsabilidad Social Empresarial
            p.mb-4(data-aos="fade-right") En el documento se destacan las políticas y prácticas de Responsabilidad Social Empresarial (RSE), subrayando su integración con los valores corporativos para promover equidad de género, combatir la pobreza y gestionar responsablemente los recursos naturales.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Políticas y prácticas de Responsabilidad Social Empresarial.

          .col-lg-4.order-1
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/2.png', alt='')

    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] Herramientas y metodologías para implementar la RSE
    
    .bg-color-7.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema3/3.png', alt='')
        .col-lg.order-1
          .p-4
            p.mb-0(data-aos="fade-up") La implementación de la Responsabilidad Social Empresarial (RSE) requiere herramientas y metodologías que guíen a las organizaciones hacia prácticas sostenibles y responsables. Entre estas herramientas, la norma ISO 26000 destaca como una de las principales directrices para la sostenibilidad empresarial.
    
    h2.mb-3(data-aos="fade-right") ISO 26000: Directrices sobre Responsabilidad Social

    p.mb-5 La norma ISO 26000, publicada en 2010 por la Organización Internacional de Normalización (ISO), proporciona recomendaciones para que las empresas y organizaciones operen de manera socialmente responsable. Aunque no es certificable, constituye una referencia valiosa para integrar la responsabilidad social en los procesos organizacionales. La norma abarca siete materias fundamentales:


    .titulo-figura.mb-4
      h5 Figura 2. 
      span Norma ISO 26000.
    .row.mb-5.justify-content-center.py-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema3/4.svg", data-aos="zoom-in")

    h2.mb-3(data-aos="fade-right") Metodología RESILIO: Implementación Estratégica de la RSE
    p.mb-5 La metodología <b>RESILIO</b>, desarrollada por la agencia ResponSable, establece un marco práctico para integrar la Responsabilidad Social Empresarial (RSE) en la estrategia organizacional. Consta de siete pasos clave que garantizan una implementación coherente y efectiva:

    .bg-full-width.bg-color-info
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-10
            ImagenInfografica.color-secundario
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/tema3/5.svg', alt='', style="max-width: 1106px;").mx-auto

                .bg-color-white.box-shadow.p-3(x="3%" y="94.5%" numero="+")
                  h5 Reflexionar
                  p Definir los objetivos estratégicos de la inversión en RSE, como mejorar las relaciones con los grupos de interés o mitigar riesgos empresariales.

                .bg-color-white.box-shadow.p-3(x="18%" y="7%" numero="+")
                  h5 Estudiar
                  p Realizar un diagnóstico de la situación actual de la empresa en sostenibilidad, identificando riesgos y oportunidades específicas.

                .bg-color-white.box-shadow.p-3(x="32%" y="95%" numero="+")
                  h5 Solicitar
                  p Involucrar a los grupos de interés mediante encuestas y entrevistas para conocer sus percepciones y expectativas respecto a la empresa.

                .bg-color-white.box-shadow.p-3(x="42%" y="6%" numero="+")
                  h5 Institucionalizar
                  p Diseñar una estrategia de RSE acompañada de un plan de acción con asignación de responsabilidades y recursos.

                .bg-color-white.box-shadow.p-3(x="53.5%" y="95%" numero="+")
                  h5 Lograr Implementar
                  p Ejecutar la estrategia en las operaciones y la cadena de valor, asegurando que las acciones reflejen los objetivos corporativos.
                .bg-color-white.box-shadow.p-3(x="73%" y="6%" numero="+")
                  h5 Informar
                  p Comunicar los avances y resultados obtenidos a las partes interesadas, fomentando la transparencia y confianza.
                .bg-color-white.box-shadow.p-3(x="85%" y="95%" numero="+")
                  h5 Optimizar
                  p Evaluar el desempeño en la gestión de la RSE, identificando oportunidades de mejora y ajustando las estrategias según sea necesario.


    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Esta metodología estructurada asegura que las acciones de RSE sean coherentes con los objetivos corporativos y alineadas con las expectativas de los grupos de interés.


    h2.mb-3(data-aos="fade-right") Otras herramientas y modelos para implementar la RSE
    p.mb-5 Además de la metodología RESILIO, las empresas pueden emplear otras herramientas y modelos para fortalecer su estrategia de RSE:


    .bg-full-width.bg-fondo-6.mb-5
      .px-4.px-md-5.pb-md-3
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema3/7.svg"
                alt=""
                style="width: 90px"
              )
              h5.text-center Indicadores Ethos de RSE
              p.mb-0.text-center Permiten evaluar y monitorear la gestión de la responsabilidad social empresarial, ayudando en la planificación estratégica y la implementación de políticas responsables.
          
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema3/8.svg"
                alt=""
                style="width: 90px"
              )
              h5.text-center Guía de relación y compromiso con los grupos de interés
              p.mb-0.text-center Ayuda a las empresas a identificar y priorizar sus grupos de interés, diseñando estrategias que fortalezcan la comunicación y el compromiso mutuo.
          
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema3/9.svg"
                alt=""
                style="width: 90px"
              )
              h5.text-center Distintivo Empresa Socialmente Responsable (ESR)
              p.mb-0.text-center Reconocimiento público que acredita a las empresas por sus buenas prácticas en RSE, destacando su compromiso con colaboradores, inversionistas, clientes y la sociedad.

        h2.mb-3(data-aos="fade-right") Importancia para la Seguridad y Salud en el Trabajo (SST)
        p.mb-5 Para los estudiantes de Seguridad y Salud en el Trabajo, comprender la RSE es crucial, ya que su implementación fomenta la creación de entornos laborales seguros y saludables. Algunas ventajas incluyen:




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
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/274611" target="_blank" rel="noopener noreferrer") De Castro Emilio Cerdá, F. J. A. L. M. (s/f). Las energías renovables en el ámbito internacional. Revistasice.com. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              span De Janeiro, R. (1992). La declaración del Río sobre el Medio Ambiente y el Desarrollo. Río de Janeiro República Federativa del Brasil., aprobada en Estocolmo el, 16.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/QKLjwCMyv3M?si=uAWhO9tnyghljaJg" target="_blank" rel="noopener noreferrer") Innovación y sostenibilidad.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
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
            texto:
              '¿Cuál de las siguientes es una característica fundamental de los derechos humanos?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Son temporales y cambiantes',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Son universales y aplican a todas las personas',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Son exclusivos de ciertos grupos',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Son opcionales',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Cuál de las siguientes afirmaciones sobre la diversidad cultural es correcta?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Fomenta la homogeneización cultural',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Promueve el respeto y la aceptación de las diferencias',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Debilita la identidad cultural de los pueblos',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Limita las oportunidades de interacción',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              'La mediación en un conflicto tiene como objetivo principal:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Imponer una solución rápida',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Facilitar el diálogo entre las partes',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Determinar la culpabilidad',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Ignorar las preocupaciones de una parte',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto: 'En un foro comunitario, es importante:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Escuchar solo a las autoridades',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Fomentar la participación de todos los miembros',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Decidir por votación sin consultar a los demás',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Excluir las opiniones de los más jóvenes',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué busca la justicia restaurativa en el contexto de un conflicto?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Aplicar una sanción severa',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Reparar el daño y restablecer las relaciones',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Castigar a las partes involucradas',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Ignorar el contexto del conflicto',
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
