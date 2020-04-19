<template>
  <!-- <section class="section section-lg section-shaped overflow-hidden my-0"> -->
  <section>
    <b-row class="justify-content-center">
      <div id="jumbotron" class="jumbotron col-lg-10 mt-5 mx-5 my-0 text-center text-lg-left">
        <h2 class="display-5">Bienvenue et Félicitations pour ce premier pas !</h2>
        <p class="haut">
          Sur GreenDistrict, on te conseille sur les différents gestes que tu
          peux changer ou améliorer au quotidien. Ne change pas tes habitudes
          trop radicalement, on y va progressivement pour pas que tu ne sombres
          du côté obscur.
          <br />
          <br />A ta disposition, trois secteurs qui demandent un léger
          effort :
        </p>
        <b-row>
          <div class="col-lg-6">
            <p class="milieu">
              - Comment recycler ses
              <a href="dechets.html">Déchets</a>
              <br />- Réduire sa consommation d'
              <a href="energie.html">energie</a> chez
              soi
              <br />- Adapter son
              <a href="alimentation.html">alimentation</a> vis-à-vis
              de la situation actuelle
            </p>

            <p class="bas">
              Tu es déjà très prometteur si tu lis toujours!
              <br />Ta planète croit en toi.
              <br />
              <br />Si jamais tu as des questions ou besoin de support,
              <br />contacte-nous via
              <a href="aide.html">Aide</a>!
              <br />On se tient à
              ta disposition dès que tu en as besoin !
            </p>
          </div>
          <b-carousel class="col-sm-12 col-lg-6 px-0 mt-5" id="carousel1" controls indicators>
            <!-- Text slides with image -->
            <b-carousel-slide img-src="img/green/handshake.jpg"></b-carousel-slide>
            <b-carousel-slide img-src="img/green/barbele.jpg"></b-carousel-slide>
            <b-carousel-slide img-src="img/green/hyppocampe.jpg"></b-carousel-slide>
          </b-carousel>
        </b-row>
      </div>
    </b-row>
  </section>
</template>
<style >
#jumbotron {
  border-radius: 50;
  background-color: #eedada;
}
#jumbotron a {
  color: #7c9465;
}
</style>


<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";
import { BCard } from "bootstrap-vue/esm/components/card";
import { BContainer, BCol, BRow } from "bootstrap-vue/esm/components/layout";

export default {
  components: {
    BCarousel,
    BCarouselSlide,
    BCard,
    BContainer,
    BCol,
    BRow
  }
};
</script>
