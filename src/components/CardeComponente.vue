<template>
  <section>
    <div class="row justify-content-center" style="margin-top: 90px">
      <div
        class="col-12 col-md-auto container px-4 vh-75 mx-auto"
        style="max-width: 1200px"
      >
        <div
          class="text-center px-4 py-3 rounded-4 shadow"
          style="width: 260px; box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.1)"
        >
          <h1 class="fw-bold">Vocé cria seu catálogo digital</h1>
          <div>
            <img
              class="py-4"
              src="../assets/vetor passo 1.png"
              :alt="descricao_1"
            />
            <p class="p">{{ textCard }}</p>
          </div>
        </div>
      </div>
      <div
        class="col-12 col-md-auto container px-4 vh-75 mx-auto"
        style="max-width: 1200px"
      >
        <div
          class="text-center px-4 py-3 rounded-4 shadow"
          style="width: 260px; box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.1)"
        >
          <h1 style="font-weight: 700">Vocé cria seu catálogo digital</h1>
          <div>
            <img
              class="py-4"
              src="../assets/vetor passo 1.png"
              :alt="descricao_1"
            />
            <p class="p">{{ textCard }}</p>
          </div>
        </div>
      </div>
      <div
        class="col-12 col-md-auto container px-4 vh-75 mx-auto"
        style="max-width: 1200px"
      >
        <div
          class="text-center px-4 py-3 rounded-4 shadow"
          style="width: 260px; box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.1)"
        >
          <h1 style="font-weight: 700">Vocé cria seu catálogo digital</h1>
          <div>
            <img
              class="py-4"
              src="../assets/vetor passo 1.png"
              :alt="descricao_1"
            />
            <p class="p">{{ textCard }}</p>
          </div>
        </div>
      </div>
    </div>

    <button
      class="btn text-white border-0 fw-bold fs-4 px-4 py-2 my-5 rounded-3"
      style="background: black; margin-top: 74px"
    >
      Começar agora
    </button>
  </section>
</template>

<script>
export default {
  name: "CardeComponente",
  data() {
    return {
      textCard:
        "tenha um Catálogo Digital dos seus produtos para vocé vender pela internet.com isso os seus clientes poderão fazer pedidos de forma simples e facil e vocé recebe através do whatsapp",
    };
  },
};
</script>
