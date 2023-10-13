<template>
  <div class="starter-page">
    <div class="section text-center">
      <CarouselSection class="carousel"></CarouselSection>
      <h1 class="title" id="title">Servicios</h1>
      <card class="col-10">
        <tabs centered type="neutral" tab-nav-wrapper-classes="card-header" tab-content-classes="card-body text-center"
          data-background-color="orange">
          <tab-pane>
            <template slot="label">
              <div class="serviceLabel">
                <i class="now-ui-icons objects_umbrella-13"></i>
                Control y Gestión de Riesgos
              </div>
            </template>
            <p class="paragraph">
              Los programas de control y gestión de riesgos son fundamentales para mantener la inocuidad alimentaria en tu
              empresa. En [Nombre de tu empresa], creamos programas personalizados que se adaptan a tus necesidades y
              metas específicas. Nuestra experiencia y conocimiento en la materia te ayudarán a establecer protocolos
              efectivos para prevenir contaminaciones, gestionar riesgos y garantizar la calidad de tus productos.
            </p>
          </tab-pane>
          <tab-pane>
            <template class='serviceLabel' slot="label">
              <i class="now-ui-icons shopping_cart-simple"></i> Auditorías Internas y Externas


            </template>
            <p class="paragraph">
              Mantenerse en cumplimiento con las normativas y regulaciones es crucial en la industria de la alimentación.
              Nuestros servicios de auditoría interna y externa te ayudarán a verificar el cumplimiento de tus operaciones
              con los estándares de seguridad alimentaria.


            </p>
          </tab-pane>
          <tab-pane>
            <template class='serviceLabel' slot="label">
              <i class="now-ui-icons shopping_shop"></i> Evaluación y Diagnóstico


            </template>
            <p class="paragraph">
              Nuestra evaluación y diagnóstico de inocuidad alimentaria es el primer paso hacia la garantía de la
              seguridad de tus productos. Nuestro equipo de expertos llevará a cabo una revisión exhaustiva de tus
              procesos y operaciones para identificar posibles riesgos y áreas de mejora. Utilizamos las mejores prácticas
              y estándares internacionales para asegurarnos de que cumplas con las normativas de seguridad alimentaria,
              minimices riesgos y protejas la salud de tus clientes.


            </p>
          </tab-pane>

        </tabs>
      </card>


      <card class="col-10">
        <Collapse>
          <CollapseItem>
            <div class="container">

              <p class="paragraph">La inocuidad alimentaria es crucial para tu negocio por varias razones. Garantizar
                alimentos seguros protege
                la salud de los consumidores, evita costosos retiros de productos y protege la reputación de tu marca,
                lo que
                a su vez aumenta la confianza del cliente y la lealtad a largo plazo.</p>
            </div>
            <template v-slot:title><span class="faqTitle"> ¿Por qué es importante la inocuidad alimentaria para mi
                negocio? </span></template>
          </CollapseItem>
          <CollapseItem>
            <div class="container">

              <p class="paragraph">Las regulaciones varían según la ubicación de tu negocio y el tipo de alimentos que
                produces o vendes. Nuestros asesores de inocuidad alimentaria pueden ayudarte a identificar y cumplir con
                las regulaciones locales, nacionales e internacionales aplicables, como el HACCP, BRC, SQF, y las
                normativas de la FDA en Estados Unidos, entre otras.</p>
            </div>
            <template v-slot:title><span class="faqTitle"> ¿Qué regulaciones de inocuidad alimentaria debo cumplir?
              </span></template>
          </CollapseItem>
          <CollapseItem>
            <div class="container">

              <p class="paragraph">Prepararse para una auditoría de inocuidad alimentaria implica documentar
                cuidadosamente tus procesos, capacitar a tu personal en buenas prácticas de manipulación de alimentos,
                llevar registros precisos y asegurarse de que tus instalaciones cumplan con los estándares. Nuestros
                asesores pueden ofrecer orientación personalizada y capacitación para garantizar que tu negocio esté listo
                para la auditoría.</p>
            </div>
            <template v-slot:title><span class="faqTitle"> ¿Cómo puedo preparar mi negocio para una auditoría de
                inocuidad alimentaria?
              </span></template>
          </CollapseItem>
          <CollapseItem>
            <div class="container">

              <p class="paragraph">La inocuidad alimentaria se refiere a la seguridad de los alimentos, es decir, que no
                causen daño a la salud de los consumidores debido a contaminantes o microorganismos peligrosos. La calidad
                alimentaria se centra en los atributos organolépticos, como sabor, textura y apariencia. Aunque son
                conceptos relacionados, la inocuidad es esencial, ya que un producto de alta calidad pero no seguro puede
                poner en riesgo la salud de los consumidores y la reputación de tu negocio.</p>
            </div>
            <template v-slot:title><span class="faqTitle"> ¿Cuál es la diferencia entre inocuidad alimentaria y
                calidad alimentaria?
              </span></template>
          </CollapseItem>
        </Collapse>

      </card>


      <div class="section section-team text-center">
        <div class="container">
          <div class="team">
            <div class="row">
              <div class="col-md-12">
                <div style="text-align: -webkit-center;" class="team-player ">
                  <div class="profile-image">
                    <img src="img/julio3.jpg" alt="Thumbnail Image" class="rounded-circle img-fluid img-raised" />
                  </div>
                  <h4 class="title">Julio C. Lamela</h4>
                  <p class=" text-primary">Microbiólogo</p>
                  <p class="description">
                    Experto microbiólogo en equipos HACCP en la evaluación de peligros biológicos de diferentes matrices
                    alimentarias e insumos

                    Gestión de Riesgos . Bioseguridad.

                    Profesión: Doctor en Medicina
                    Especialista en Microbiología - Posgrado UDELAR
                    Especialista UNIT en Seguridad Alimentaria
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"><i class="fab fa-twitter"></i></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"><i class="fab fa-instagram"></i></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"><i class="fab fa-facebook-square"></i></a>
                </div>
              </div>

            </div>
          </div>
        </div>
      </div>


    </div>



  </div>
</template>
<script>

import CarouselSection from './components/CarouselSection.vue';
import { Card, Tabs, TabPane } from '@/components';
import { Collapse, CollapseItem } from '@/components'

export default {
  name: 'starter',
  components: {
    CarouselSection, Card, Tabs, TabPane, Collapse,
    CollapseItem
  }
};
</script>
<style>
.starter-page {
  min-height: calc(100vh - 95px);
  background-color: black;
}

#title {
  margin-top: 2em;
  color: white;
}

.title {
  color: white;
}

.paragraph {
  font-weight: 500;
  font-size: x-large;
}

.carousel {
  box-shadow: 10px 10px 10px 10px;
}

.faqTitle {
  font-size: 20px;
  color: black;
}

.profile-image {
  height: 200px;
  width: 200px;
}
</style>
