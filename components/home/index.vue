<template>
  <section id="home" class="container">
    <v-row>
      <v-col lg="6" md="12" align="start" justify="center">
        <div class="main-left">
          <profil class="profil" />
          <profil-description class="profil-desc" />
        </div>
      </v-col>
      <v-col class="main-right" lg="6" md="12" align="center" justify="center">
        <portfolio-description class="portfolio-desc" />
        <frontend class="front-end" />
        <timeline class="timeline" />
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12">
        <portfolio-footer />
      </v-col>
    </v-row>
  </section>
</template>

<script>
import ProfilDescription from "./profilDescription.vue";
import profil from "./profil.vue";
import PortfolioDescription from "./portfolioDescription.vue";
import Frontend from "./frontend.vue";
import Timeline from "./timeline.vue";
import PortfolioFooter from "../portfolioFooter.vue";
export default {
  components: {
    profil,
    ProfilDescription,
    PortfolioDescription,
    Frontend,
    Timeline,
    PortfolioFooter,
  },
};
</script>

<style lang="scss">
#home {
  .main-left {
    min-height: 100vh;
    position: fixed;
    @media screen and (max-width: $medium) {
      position: relative;
      min-height: 0 !important;
    }
    .profil {
      animation-name: up;
      animation-duration: 1s;
    }
    .profil-desc {
      animation-name: up;
      animation-duration: 2s;
    }
  }
  .main-right {
    .portfolio-desc {
      animation-name: up;
      animation-duration: 1s;
    }
    .front-end {
      animation-name: up;
      animation-duration: 2s;
    }
    .timeline {
      animation-name: up;
      animation-duration: 2.5s;
    }
  }
}
@keyframes up {
  from {
    transform: translateY(-100vw);
  }
  to {
    transform: translateY(0px);
  }
}

</style>