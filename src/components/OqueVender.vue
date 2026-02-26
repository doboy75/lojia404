<template>
  <section
    :id="perguntas"
    class="d-flex justify-content-center container-fluid"
  >
    <div class="container row p-5 text-start">
      <div class="col">
        <h2 class="display-5 fw-bold">
          {{ textoCatalogo }}
        </h2>
        <p class="lead mb-4">
          {{ conteudoCatalogo }}
        </p>
        <button
          class="h2 d-flex justify-content-center border-0 py-3 px-4 text-white rounded-3 fw-bold mb-2"
          :class="background_green"
        >
          {{ textbtn }}
        </button>
      </div>
      <div class="col">
        <img src="../assets/bro.png" :alt="descrição" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "OqueVender",

  data() {
    return {
      descrição: "mulher segurando um celular",
      textoCatalogo: "  O que da pra vender no catálogo da lojia?",
      conteudoCatalogo:
        "O Catálogo Digital da lojia é ideal para vocé vender o que quiser,seja loja de roupas,semijoias,sapatos,peças automativas ou até no ramo alimentício como restaurante,lanchonetes,mercados e padarias.È a sua loja de forma simples,prática e  rápida!",
      textbtn: "Começar Agora",
      background_green: "background_green",
      perguntas: "perguntas",
    };
  },
};
</script>
<style scoped>
.background_green {
  background-color: #22b573;
}
</style>
