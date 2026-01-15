<template>
  <TesteComponentes1 />
  <TesteComponentes2 />
  <TesteComponentes3 />
</template>

<script>
import TesteComponentes1 from "./components/TesteComponentes1.vue";
import TesteComponentes2 from "./components/TesteComponentes2.vue";
import TesteComponentes3 from "./components/TesteComponentes3.vue";

export default {
  name: "App",
  components: {
    TesteComponentes1,
    TesteComponentes2,
    TesteComponentes3,
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
