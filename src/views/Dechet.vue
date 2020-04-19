<template>
  <b-row class="mt-5">
    <b-row class="mx-2 mt-5 justify-content-around">
      <b-card
        class="col-10 mb-4 col-md-5"
        style="background-color: #eedada;"
        title=" Les bacs bleus/jaunes:"
      >
        <b-card-text class="bacbleu">
          -Les bouteilles, flacons et bidons en plastique avec leur
          bouchon
          <br />
          <br />-Les emballages en métal
          <br />
          <br />-Les cartons et papiers
        </b-card-text>
      </b-card>

      <b-card
        class="col-10 mb-4 col-md-5"
        style="background-color: #eedada;"
        title="Les bacs vert ou gris:"
      >
        <b-card-text class="bacvert">
          -Les sacs poubelles bien fermés, qui contiennent tes déchêts
          alimentaire et résiduels: du genre mouchoirs, lingettes, les
          emballages en plastique très légers
        </b-card-text>
      </b-card>
    </b-row>
    <b-row class="mx-2 mb-4 d-flex justify-content-center" style="width:100%">
      <b-card
        class="col-10 col-md-10"
        style="background-color: #eedada;"
        title="Les cas spécifiques:"
      >
        <b-card-text class="specifique">
          -Les piles, ampoules et cartouches: tu trouveras des collectes
          dans les magasins qui vendent ce type de produits.
          <br />
          <br />-Les vêtement usagers: tu peux les déposer dans les containers de
          collecte installés en ville ou alors dernièrement les revendre sur
          différents application.
          <br />
          <br />-Les médicaments inutilisés ou périmés: tu les rends à ton
          pharmacien tout simplement.
        </b-card-text>
      </b-card>
    </b-row>
    <b-row id="video" class="pl-4 justify-content-center">
      <iframe
        style="height:20em"
        class="col-12 col-md-8"
        src="https://www.youtube.com/embed/rNwtMO_Hay4"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </b-row>
  </b-row>
</template>
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

    
    
    
<style >
#video {
  width: 100%;
}
</style>