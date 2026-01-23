<template>
  <section :class="seccao_card">
    <div class="grid">
      <div :class="container">
        <div :class="card_1">
          <h1 style="font-weight: 700">Vocé cria seu catálogo digital</h1>
          <div>
            <img
              :class="imagem_1"
              src="../assets/vetor passo 1.png"
              :alt="descricao_1"
            />
            <p>{{ textCard }}</p>
          </div>
        </div>
      </div>
      <div :class="container">
        <div :class="card_1">
          <h1 style="font-weight: 700">Vocé cria seu catálogo digital</h1>
          <div>
            <img
              :class="imagem_1"
              src="../assets/vetor passo 1.png"
              :alt="descricao_1"
            />
            <p>{{ textCard }}</p>
          </div>
        </div>
      </div>
      <div :class="container">
        <div :class="card_1">
          <h1 style="font-weight: 700">Vocé cria seu catálogo digital</h1>
          <div>
            <img
              :class="imagem_1"
              src="../assets/vetor passo 1.png"
              :alt="descricao_1"
            />
            <p>{{ textCard }}</p>
          </div>
        </div>
      </div>
    </div>

    <button class="btn">Começar agora</button>
  </section>
</template>

<script>
export default {
  name: "CardeComponente",
  data() {
    return {
      container: "espaco",
      card_1: "primeiro",
      imagem_1: "imagem",
      textCard:
        "tenha um Catálogo Digital dos seus produtos para vocé vender pela internet.com isso os seus clientes poderão fazer pedidos de forma simples e facil e vocé recebe através do whatsapp",
      seccao_card: "seccao",
    };
  },
};
</script>

<style>
.seccao {
  padding: 90px 0;
}
.grid {
  display: grid;
  grid-template-columns: 350px 350px 350px;
  justify-content: center;
}
.espaco {
  max-width: 1200px;
  margin: auto;
  padding: 0 24px;
  height: 75vh;
}
.primeiro {
  width: 260px;
  border-radius: 23px;
  padding: 18px 26px;
  text-align: center;
  box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.1);
}
.imagem {
  padding: 24px 0;
}
.btn {
  background-color: black;
  color: #fff;
  border: 0;
  font-size: 24px;
  padding: 12px 30px;
  font-weight: 700;
  border-radius: 9px;
  margin-top: 74px;
}
</style>
