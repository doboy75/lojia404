<template>
  <section class="container-fluid d-flex justify-content-center">
    <div class="container row py-5 my-5 gap-5">
      <div class="col">
        <img
          src="../assets/bro copy.png"
          alt="imagem de uma mulher segurando um celular"
        />
      </div>
      <div class="col">
        <h2 class="display-5 fw-bold mb-3">
          {{ textMidia }}
        </h2>
        <p class="lead mb-4">
          {{ conteudoMidia }}
        </p>
        <button
          class="h2 fw-bold mb-5 px-5 py-3 rounded-4 text-white border-0"
          :class="background_dark"
        >
          {{ btTextMidia }}
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "CatalagoDigital",

  data() {
    return {
      textMidia:
        "Leve seus clientes das mídias sociais para seu Catálogo Digital",
      conteudoMidia:
        " Com a Lojia você terá um link onde poderá divulgar ele na Bio do seu Instagram e assim divulgar seus produtos na sua conta. Você vai vender muito mais!",
      btTextMidia: "Começar Agora",
      background_dark: "background_dark",
    };
  },
};
</script>
<style scoped>
.background_dark {
  background-color: #22b573;
}
</style>
