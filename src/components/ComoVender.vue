<template>
  <section class="d-flex justify-content-center">
    <div class="row py-5 my-5 gap-5" style="width: 1106">
      <div
        class="col"
        style="
          width: 282px;
          /* height: 680px; */
          background-color: #ffffff;
          border-radius: 28px;
          padding: 13px 28px;
          text-align: center;
          box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
        "
      >
        <h2
          style="
            color: #000000;
            font-size: 23.57px;
            font-weight: 700;
            margin-bottom: 10px;
            padding-top: 25px;
          "
        >
          {{ textWhatsapp }}
        </h2>
        <img
          src="../assets/vetor passo 1.png"
          :alt="descricaoimg"
          style="width: 200px; height: 277px; margin: 35px 0"
        />
        <p style="font-size: 15px; font-weight: 300; color: #1b2733">
          {{ textCard_1 }}
        </p>
      </div>
      <div
        class="col mx-5"
        style="
          width: 282px;
          /* height: 680px; */
          background-color: #ffffff;
          border-radius: 28px;
          padding: 13px 28px;
          text-align: center;
          box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
        "
      >
        <h2
          style="
            color: #000000;
            font-size: 23.57px;
            font-weight: 700;
            margin-bottom: 10px;
            padding-top: 25px;
          "
        >
          {{ text_2 }}
        </h2>
        <img
          src="../assets/vetor passo 2.png"
          :alt="descricaoimg"
          style="width: 100.23px; height: 300px; margin: 35px 0"
        />
        <p style="font-size: 15px; font-weight: 300; color: #1b2733">
          {{ textCard_2 }}
        </p>
      </div>
      <div
        class="col"
        style="
          width: 282px;
          /* height: 680px; */
          background-color: #ffffff;
          border-radius: 28px;
          padding: 13px 28px;
          text-align: center;
          box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
        "
      >
        <h2
          style="
            color: #000000;
            font-size: 23.57px;
            font-weight: 700;
            margin-bottom: 10px;
            padding-top: 25px;
          "
        >
          {{ text_3 }}
        </h2>
        <img
          src="../assets/vetor passo 3.png"
          :alt="descricaoimg"
          style="width: 163.57px; height: 237.87px; margin: 35px 0"
        />
        <p style="font-size: 15px; font-weight: 300; color: #1b2733">
          {{ textCard_3 }}
        </p>
      </div>
    </div>
  </section>
  <button
    class="mb-5"
    style="
      border: none;
      color: #ffffff;
      background-color: #1b2733;
      font-size: 31.14px;
      font-weight: 700;
      border-radius: 6.7px;
      padding: 10px 20px;
    "
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
    };
  },
};
</script>

<style></style>
