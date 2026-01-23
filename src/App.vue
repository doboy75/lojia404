<template>
  <TesteComponentes1 />
  <TesteComponentes2 />
  <TesteComponentes3 />
  <CardeComponente />
  <CardSecound />
  <HeroComponente />
  <PhoneComponente />
  <CartoesComponentes />
  <FooterComponentes />
</template>

<script>
import CardeComponente from "./components/CardeComponente.vue";
import TesteComponentes1 from "./components/TesteComponentes1.vue";
import TesteComponentes2 from "./components/TesteComponentes2.vue";
import TesteComponentes3 from "./components/TesteComponentes3.vue";
import CardSecound from "./components/CardSecound.vue";
import HeroComponente from "./components/HeroComponente.vue";

import PhoneComponente from "./components/PhoneComponente.vue";
import CartoesComponentes from "./components/CartoesComponentes.vue";
import FooterComponentes from "./components/FooterComponentes.vue";

export default {
  name: "App",
  components: {
    TesteComponentes1,
    TesteComponentes2,
    TesteComponentes3,
    CardeComponente,
    CardSecound,
    HeroComponente,
    PhoneComponente,
    CartoesComponentes,
    FooterComponentes,
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
