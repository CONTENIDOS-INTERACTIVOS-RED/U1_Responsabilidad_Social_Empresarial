<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Conceptos Fundamentales de la RSE'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-5 La Responsabilidad Social Empresarial (RSE) es un enfoque estratégico que invita a las empresas a integrar, de manera voluntaria, consideraciones sociales, ambientales y económicas en sus operaciones diarias, así como en sus relaciones con las partes interesadas. Su desarrollo se remonta a mediados del siglo XX, cuando comenzó a cuestionarse el rol exclusivo de las empresas como generadoras de beneficios económicos, planteándose nuevas responsabilidades relacionadas con su impacto en la sociedad y el medio ambiente (Lozano, 2019).


    .bg-full-width.bg-fondo-3.mb-5
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.align-items-center
          .col-lg-6(data-aos="fade-left").order-2
            h5 Principios Clave de la RSE:
            p.mb-1 Transparencia en las acciones empresariales.
            p.mb-1 Prácticas basadas en la ética y responsabilidad.
            p.mb-1 Respeto y promoción de los derechos humanos.

          .col-lg-6(data-aos="zoom-in").order-1
            figure
              img(src="@/assets/curso/tema1/1.svg", data-aos="zoom-in").mb-4.mb-lg-0

    p.mb-5 La RSE, además de promover valores éticos, busca crear un desarrollo sostenible que equilibre el crecimiento económico, la protección ambiental y el bienestar social. Implementar prácticas de RSE, como las sugeridas en la norma ISO 26000, permite a las organizaciones fortalecer su reputación, optimizar relaciones con sus stakeholders y generar un impacto positivo en las comunidades donde operan.
    #t_1_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.1] Subtítulo tema

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
