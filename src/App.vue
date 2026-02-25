<template>
  <ComponenteHero />
  <ComponenteBeneficios />
  <ComoVender />
  <OqueVender />
  <CatalagoDigital />
  <VendasViaWhatsapp />
  <ExemplosDeLojas />
  <AppFooter />
</template>

<script>
import ComoVender from "./components/ComoVender.vue";

import ComponenteHero from "./components/ComponenteHero.vue";
import ComponenteBeneficios from "./components/ComponenteBeneficios.vue";
import OqueVender from "./components/OqueVender.vue";
import CatalagoDigital from "./components/CatalagoDigital.vue";

import VendasViaWhatsapp from "./components/VendasViaWhatsapp.vue";
import ExemplosDeLojas from "./components/ExemplosDeLojas.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    ComponenteHero,
    ComponenteBeneficios,
    ComoVender,
    OqueVender,
    CatalagoDigital,
    VendasViaWhatsapp,
    ExemplosDeLojas,
    AppFooter,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
