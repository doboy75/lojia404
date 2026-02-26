<template>
  <section
    :id="contacto"
    class="container-fluid d-flex justify-content-center py-5"
    :class="{ bg_img, bg_dark }"
  >
    <div class="container row d-flex align-items-center">
      <div class="col text-start">
        <h2 class="display-4 text-white fw-bold">
          {{ textWhatsapp }}
        </h2>
        <p class="lead text-white">
          Tenha um <Span>Catalogo Digital</Span> dos seus produtos para voçé
          <span>Vender pela internet.</span>Com isso seus clientes poderão
          <span>fazer pedidos de forma simples e fácil</span> e vocé
          <span>receber através do whatsapp</span>
        </p>
        <button
          :class="bg_green"
          class="my-5 h1 text-white border-0 rounded-3 py-3 px-4 fw-bold"
        >
          {{ btwhatsapp }}
        </button>
      </div>
      <div class="col">
        <img src="../assets/Phone.png" :alt="descricao" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "VendasViaWhatsapp",
  data() {
    return {
      textWhatsapp: "Venda Onlibe e receba os pedidos pelo Whaatsapp",
      btwhatsapp: "Comçar Agora",
      bg_green: "background_green",
      bg_img: "bg_img",
      contacto: "contacto",
      bg_dark: "bg_dark",
    };
  },
};
</script>
<style scoped>
.bg_img {
  background-image: url("../assets/Pattern (1).png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.background_green {
  background-color: #22b573;
}
.bg_dark {
  background-color: #1b2733;
}
</style>
