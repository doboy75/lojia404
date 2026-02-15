<template>
  <section
    class="container-fluided d-flex justify-content-center py-5"
    style="background-color: #0f2533"
  >
    <div class="row d-flex align-items-center" style="width: 1154px">
      <div class="col text-start">
        <h2 style="color: #ffff; font-size: 50px; font-weight: 700">
          {{ textWhatsapp }}
        </h2>
        <p
          style="color: #ffff; font-size: 20px; font-weight: 300; padding: 10px"
        >
          Tenha um <Span>Catalogo Digital</Span> dos seus produtos para voçé
          <span>Vender pela internet.</span>Com isso seus clientes poderão
          <span>fazer pedidos de forma simples e fácil</span> e vocé
          <span>receber através do whatsapp</span>
        </p>
        <button
          class="mb-5"
          style="
            border: none;
            color: #ffffff;
            background-color: #22b573;

            font-size: 31.14px;
            font-weight: 700;
            border-radius: 6.7px;
            padding: 10px 20px;
          "
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
    };
  },
};
</script>
