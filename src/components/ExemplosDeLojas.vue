<template>
  <section :class="seccao">
    <div :class="container_6">
      <h2>Veja alguns exemplos de lojas na lojia</h2>
      <div :class="cartao">
        <div>Loja de Electrónicos</div>
        <div>Loja de roupas</div>
        <div>Hamburgsria</div>
        <div>Loja de Acessorios</div>
      </div>
      <button :class="botao_6">Começar agora</button>
    </div>
  </section>
</template>
<script>
export default {
  name: "ExemplosDeLojas",
  data() {
    return {
      cartao: "cartao",
      seccao: "seccao-6",
      container_6: "centralizar",
      botao_6: "botao_6",
    };
  },
};
</script>
<style>
.cartao {
  display: flex;
  justify-content: center;
  gap: 2rem;
}

.cartao div {
  width: 14rem;
  height: 24rem;
  box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
  font-size: 1.4rem;
  border: none;
  border-radius: 19px;
  padding-top: 1.4rem;
  padding: 1.4rem 1rem;
  margin: 2rem 0;
  text-align: center;
  font-weight: 600;
}
.centralizar {
  width: 79rem;
}
.seccao-6 {
  display: flex;
  justify-content: center;
}
.botao_6 {
  background-color: black;
  padding: 1.4rem 4.6rem;
  border: none;
  border-radius: 14px;
  color: #fff;
  font-size: 1.6rem;
  cursor: pointer;
  margin-top: 2.6rem;
}
</style>
