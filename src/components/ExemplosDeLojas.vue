<template>
  <section class="container-fluided d-flex justify-content-center pt-5">
    <div class="container py-5">
      <div class="container">
        <h1 class="display-5 fw-bold pb-4">
          {{ tituloExemplosLojas }}
        </h1>
      </div>
      <div class="container row gap-5 d-flex justify-content-center pt-2">
        <div class="col shadow rounded-4" :class="heigh_card">
          <h2 class="h5 fw-bold pt-3">
            Loja de <br />
            Eletrônicos
          </h2>
        </div>
        <div class="col shadow rounded-4" :class="heigh_card">
          <h2 class="h5 fw-bold pt-3">
            Loja de <br />
            Roupas
          </h2>
        </div>
        <div class="col shadow rounded-4">
          <h2 class="h5 fw-bold pt-3">Hamburgueria</h2>
        </div>
        <div class="col shadow rounded-4">
          <h2 class="h5 fw-bold pt-3">
            Loja de <br />
            Acessórios
          </h2>
        </div>
      </div>
    </div>
  </section>
  <div class="container-fluid pt-2 d-flex justify-content-center">
    <button
      :class="btnBg_dark"
      class="d-flex justify-content-center h2 py-3 px-4 border-0 bg- text-white rounded-3 fw-bold"
    >
      {{ btTextoExemplosLojas }}
    </button>
  </div>
</template>
<script>
export default {
  name: "ExemplosDeLojas",
  data() {
    return {
      tituloExemplosLojas: "Veja alguns exemplos de lojas na Lojia",
      btTextoExemplosLojas: "Começar Agora",
      btnBg_dark: "btnBg_dark",
      heigh_card: "heigh_card",
    };
  },
};
</script>
<style scoped>
.heigh_card {
  height: 383.88px;
}
.btnBg_dark {
  background-color: #0f2533;
}
</style>
