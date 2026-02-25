<template>
  <section
    :class="bg_img"
    class="container-fluided d-flex justify-content-center py-5 bg-dark"
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
    };
  },
};
</script>
<style scoped>
.bg_img {
  background-image: url("../assets/Group.png");
  background-size: auto;
  background-position: center;
}
.background_green {
  background-color: #22b573;
}
</style>
