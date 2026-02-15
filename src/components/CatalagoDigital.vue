<template>
  <section class="d-flex justify-content-center">
    <div class="row py-5 my-5 gap-5" style="width: 1101px">
      <div class="col">
        <img
          src="../assets/bro copy.png"
          alt=""
          style="width: 482.88px; height: 468.11px"
        />
      </div>
      <div class="col">
        <h2 style="font-size: 50px; font-weight: 700; color: #1b2733">
          {{ textMidia }}
        </h2>
        <p
          style="
            color: #1b2733;
            font-size: 20px;
            font-weight: 300;
            margin: 34px 0;
          "
        >
          {{ conteudoMidia }}
        </p>
        <button
          :class="bg_green"
          class="mb-5"
          style="
            border: none;
            color: #ffffff;

            font-size: 31.14px;
            font-weight: 700;
            border-radius: 6.7px;
            padding: 10px 20px;
          "
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
      bg_green: "background_green",
    };
  },
};
</script>
<style>
.background_green {
  background-color: #22b573;
}
</style>
