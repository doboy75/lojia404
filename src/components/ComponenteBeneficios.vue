<template>
  <section class="container-fluid bg-light d-flex justify-content-center">
    <div class="container">
      <h1 class="h1 fw-bold text-center my-5">
        Aumente sua Receita
        <span class="h1 fw-bold">com um</span>
        Catálogo Digital e <br />
        receba os pedidos no WhatsApp.<br />
        Simples, Fácil, Sem Taxas, Sem Burocracia!
      </h1>

      <button
        :class="bg_green"
        class="container-fluid d-flex justify-content-center shadow text-center py-4 text-white h3 fw-bold border-0 rounded-4"
      >
        Veja como funciona o Catálogo Digital da Loja 404
      </button>
    </div>
  </section>
</template>

<script>
export default {
  name: "ComponenteBeneficios",
  data() {
    return {
      bg_green: "background_green",
    };
  },
};
</script>
<style scoped>
.background_green {
  background-color: #22b573;
}
</style>
