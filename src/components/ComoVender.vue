<template>
  <section
    :id="comoFunciona"
    class="container-fluid d-flex justify-content-center"
  >
    <div class="container row py-5 my-5 gap-5">
      <div class="col shadow rounded-4 px-4">
        <span class="text-start fw-bold" :class="posicaoIndex">1</span>
        <h2 class="h4 py-4 fw-bold">
          {{ textWhatsapp }}
        </h2>
        <img src="../assets/vetor passo 1.png" :alt="descricaoimg" />
        <p class="p py-3">
          {{ textCard_1 }}
        </p>
      </div>
      <div class="col shadow rounded-4 px-4 mx-5">
        <span class="text-start fw-bold" :class="posicaoIndex">2</span>
        <h2 class="h4 py-4 fw-bold">
          {{ text_2 }}
        </h2>
        <img src="../assets/vetor passo 2.png" :alt="descricaoimg" />
        <p class="p py-3">
          {{ textCard_2 }}
        </p>
      </div>
      <div class="col shadow rounded-4 px-4">
        <span class="text-start fw-bold" :class="posicaoIndex">3</span>
        <h2 class="h4 py-4 fw-bold">
          {{ text_3 }}
        </h2>
        <img src="../assets/vetor passo 3.png" :alt="descricaoimg" />
        <p class="p py-3">
          {{ textCard_3 }}
        </p>
      </div>
    </div>
  </section>
  <button
    :class="btnBg_dark"
    class="h2 fw-bold mb-5 px-5 py-3 rounded-4 text-white border-0"
  >
    {{ btntext }}
  </button>
</template>

<script>
export default {
  name: "ComoVender",
  data() {
    return {
      textCard:
        "tenha um Catálogo Digital dos seus produtos para vocé vender pela internet.com isso os seus clientes poderão fazer pedidos de forma simples e facil e vocé recebe através do whatsapp",
      textWhatsapp: "Você recebe o Pedido no whatsapp",
      textCard_1:
        "Tenha um Catálogo Digital dos seus produtos para você vender pela internet. Com isso seus clientes poderão fazer pedidos de forma simples e fácil e você receber através do WhatsApp.",
      text_2: "O cliente acessa o escolhe o produto",
      textCard_2:
        "O seu cliente acessa o link da sua loja, escolhe o produto desejado e faz o pedido. Tudo muito simples e prático para o seu cliente.",
      textCard_3:
        "Imediatamente após o pedido do seu cliente, você recebe no seu WhatsApp o pedido completo, com todos os dados e informações para já negociar e fechar a venda com seu cliente.",
      text_3: "Você recebe o pedido no whatsApp",
      imgmoca: "../assets/vetor passo 1.png",
      descricaoimg: "uma moça escolhendo itens",
      btntext: "Começar Agora",
      btnBg_dark: "btnbackground_dark",
      posicaoIndex: "posicaoIndex",
      posicaoIndex_card: "posicaoIndex _card",
      comoFunciona: "comoFunciona",
    };
  },
};
</script>

<style scoped>
.btnbackground_dark {
  background-color: #1b2733;
}

.posicaoIndex {
  position: relative;
  z-index: 0;
  bottom: 37px;
  right: 55px;
  display: block;
  font-size: 86px;
}
.posicaoIndex_card {
  z-index: 2;
}
</style>
