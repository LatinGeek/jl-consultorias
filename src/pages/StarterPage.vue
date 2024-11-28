<template>
  <div class="starter-page">
    <div style="height: 0em;"></div>
    <div class="section text-center">
      <CarouselSection class="carousel"></CarouselSection>
      <div class="container" style="margin-top: 7em;">
        <p class="text-primary">Más del 80 % de los productos elaborados que presentan desvíos en indicadores biológicos
          y/o microorganismos
          patógenos nocivos para el consumidor, provienen del ambiente en el que se producen <br> <b>asesoramos para
            lograr una
            producción en un ambiente bajo control e higiene.</b> <br>
          Realizamos diagnóstico de contaminación cruzada, realizamos la búsqueda de Indicadores biológicos,
          vectorización,
          nichos contaminantes.
        </p>
      </div>
      <h1 class="title" id="title">Servicios</h1>
      <card class="col-10">
        <tabs centered type="neutral" tab-nav-wrapper-classes="card-header" tab-content-classes="card-body text-center"
          data-background-color="orange">
          <tab-pane>
            <template slot="label">
              <div class="serviceLabel">
                <i class="now-ui-icons objects_umbrella-13"></i>
                Auditorías
              </div>
            </template>
            <p class="paragraph">
              Nuestra evaluación y diagnóstico de inocuidad alimentaria es el primer paso hacia la garantía de la
              seguridad de tus productos. Nuestro equipo de expertos llevará a cabo una revisión exhaustiva de tus
              procesos y operaciones para identificar posibles riesgos y áreas de mejora.
            </p>
          </tab-pane>
          <tab-pane>
            <template class='serviceLabel' slot="label">
              <i class="now-ui-icons shopping_cart-simple"></i> Capacitación


            </template>
            <p class="paragraph">
              Cuando hablamos de Inocuidad Alimentaria, en general hablamos de alimentos libres de patógenos para el
              consumidor, o en aquellos microrganismos que potencialmente puedan causar pérdida de la calidad, lograr su
              concentración en el producto dentro de un margen de aceptabilidad reglamentario o normativo durante su vida
              útil, basado en un profundo y real análisis de riesgo .
              Entendemos que establecer una “Cultura de trabajo” es posible <b>si la primera línea de operarios en
                producción
                están capacitados, motivados e involucrados con su tarea</b>, logrando excelentes estándares de producción
              responsable.



            </p>
          </tab-pane>
          <tab-pane>
            <template class='serviceLabel' slot="label">
              <i class="now-ui-icons shopping_shop"></i> Asesorías


            </template>
            <p class="paragraph">
              Los programas de Seguridad Alimentaria, control y gestión de peligros biológicos son fundamentales para
              asegurar la inocuidad alimentaria en tu empresa.
              En <b>JL Consultorías</b>, ofrecemos mediante trabajo en equipo , el diagnóstico , apoyo , capacitación y
              planes que
              se adapten a tus necesidades productivas y metas económicas.



            </p>
          </tab-pane>
          <tab-pane>
            <template class='serviceLabel' slot="label">
              <i class="now-ui-icons education_paper"></i> Diagnóstico


            </template>
            <p class="paragraph">
              Ofrecemos mediante apoyo analítico, un diagnóstico de situación real y planes de trabajo que permitan
              erradicar la presencia de microorganismos “problema” en el ambiente de elaboración de alimentos.
              <b>Capacitar de forma remota o presencial, al personal de Calidad y Seguridad alimentaria</b>, de los
              atributos
              moleculares, estructurales, metabólicos y de resistencia, que poseen los microorganismos por lo cual, a
              pesar del cumplimiento de estándares de limpieza y sanitizado, fallamos en el control de los mismos.




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

              <p class="paragraph">La inocuidad alimentaria se refiere a la seguridad de los alimentos, de forma tal que
                <b>no causen daño a la salud de los consumidores debido a contaminantes, microorganismos o sus
                  toxinas.</b>
                La calidad alimentaria se centra en los atributos organolépticos, como sabor, textura y apariencia, entre
                otros.
                Aunque son conceptos relacionados, la inocuidad es esencial, ya que un producto de alta calidad pero no
                seguro puede poner en riesgo la salud de los consumidores y la reputación de tu negocio.
              </p>
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
                  <p class=" text-primary">Microbiólogo MD</p>
                  <p class="description text-primary">
                    Experto microbiólogo en la evaluación de peligros biológicos de diferentes matrices alimentarias e
                    insumos en equipos HACCP.
                    Amplia experiencia en procesos productivos por más de 35 años.
                  </p>
                  <p class="description text-primary">
                    <b>Doctor en Medicina</b> – Universidad de la República O. del Uruguay ( UDELAR ) <br>
                    <b>Especialista en Microbiología</b> – Instituto de Higiene - Facultad de Medicina <br>
                    <b>Posgrado</b> - Universidad de la República O. del Uruguay <br>
                    <b>Especialista en Seguridad Alimentaria </b>- UNIT <br>
                    <b>Responsable en Gestión de Riesgos </b> - LATU <br>
                    <b>Consultor Asesor</b> - Microbiología industrial <br>

                  </p>

                  <p class="description">jlamela005@gmail.com</p>
                  <p class="description">+598 98 300 386</p>
                  <div clas="row" style="display: inline-flex;">
                    <a href="https://wa.me/+59898300386" class="socialbtn btn btn-primary btn-icon btn-round"><i
                        class="fab fa-whatsapp"></i></a>
                    <a href="https://www.linkedin.com/in/julio-lamela-94743647/"
                      class="socialbtn btn btn-primary btn-icon btn-round"><i class="fab fa-linkedin"></i></a>
                  </div>
                </div>
              </div>

            </div>
          </div>
        </div>
      </div>



      <h1 class="title" id="title">Trabajemos juntos</h1>
      <div class="row inforow">
        <div class="col-sm-12 col-xl-6">
          <img src="/img/food-safety-logo.png" style="width: 100%; max-width: 40em; padding: 2em 10em 2em 10em;" />
        </div>
        <div style='margin: auto; padding: 5em;' class="col-sm-12 col-xl-6 description">
          <p class="text-primary">
            <b>Agenda una reunión de 30 minutos para conocer acerca de tu situación y poder brindarte una propuesta de
              valor
              que garantice la satisfacción de tu negocio en términos de Seguridad Alimentaria</b>
          </p>
        </div>
      </div>
      <h1 class="title" id="title">Participaciones</h1>

      <Card>
        <div style="display: flex; justify-content: space-evenly;" class="linkedinContainer">

          <LinkedinCard
            imageSrc="img\1609283167775.jpg"
            title="BARCELONA 201, UAB" desc="Workshop de metodos rápidos y automatización en microbiologia alimentaria.
          Ponente." />
          <LinkedinCard imageSrc="https://indufarma.com.uy/wp-content/uploads/2020/10/Indufarma-SETIEMBRE.jpg"
            title="Indufarma"
            desc="Una visión de la contaminación biológica de los alimentos con el foco puesto en el ambiente. Gracias Indufarma por la invitación y el interés." />
          <LinkedinCard
            imageSrc="https://i.postimg.cc/pdNyYwgW/1559347218683.jpg"
            title="Hotel Estancia San Pedro del Timote"
            desc="Charla de Inocuidad y atributos microbianos favorecedores de la contaminación cruzada. Capacitación de todo el personal del servicio gastronómico y chef responsable." />
 <LinkedinCard
            imageSrc="img\176f2acf-7ea2-4e4b-b954-17c4e839760c.jpg"
            title="Workshop MRAMA - Memorial DYCFung"
            desc="'Rapid methods and automation in Food Microbiology' Universitat Autónoma de Barcelona" />

        </div>


      </Card>

      <h1 class="title" id="title">Agenda una reunión</h1>
      <vue-calendly url="https://calendly.com/germanlamela98/30min" height=900></vue-calendly>

  
    </div>



  </div>
</template>
<script>

import CarouselSection from './components/CarouselSection.vue';
import { Card, Tabs, TabPane } from '@/components';
import { Collapse, CollapseItem } from '@/components'
import LinkedinCard from '../components/LinkedinCard.vue'

export default {
  name: 'starter',
  components: {
    CarouselSection, Card, Tabs, TabPane, Collapse,
    CollapseItem,
    LinkedinCard
  },

};
</script>
<style>
.starter-page {
  min-height: calc(100vh - 95px);
  background-color: black;
}

h1 {
  padding-left: 0.5em;
  padding-right: 0.5em;
}

.socialbtn {
  height: 100px !important;
  width: 100px !important;
  font-size: 50px !important;
  display: grid !important;
  left: 0 !important;
  top: 0 !important;
  text-align: center !important;
  transform: translate(0) !important;
  justify-items: center !important;
  align-content: center !important;
}

.socialbtn>i {
  display: grid !important;
  height: 100% !important;
  justify-items: center !important;
  align-content: center !important;
  width: 100% !important;
  top: 0 !important;
  left: 0 !important;
  transform: translate(0) !important;

  position: relative !important;

}

#title {
  margin-top: 1em;
  color: white;
}

.title {
  color: white;
}

@media screen and (max-width: 700px) {
  .paragraph {
    font-size: 1em;
  }

  .faqTitle {
    font-size: 15px;
    font-weight: 600;

  }

  .text-primary {
    font-size: 1.25em;
  }

  .linkedinContainer {
    flex-direction: column;
    align-items: center;
  }

}

@media screen and (min-width: 701px) {
  .paragraph {
    font-size: large;
  }

  .faqTitle {
    font-size: 20px;

  }

  .inforow {
    padding: 10em;
  }

  .linkedin-grid {
    display: grid !important;
    justify-content: center;
    width: 100vw !important;
  }
}



.paragraph {
  font-weight: 500;
}

.carousel {
  box-shadow: 10px 10px 10px 10px;
}

.faqTitle {
  color: black;
}

.profile-image {
  height: 200px;
  width: 200px;
}

.calendly .calendly-overlay .calendly-popup {
  max-height: 780px !important;
}
</style>
