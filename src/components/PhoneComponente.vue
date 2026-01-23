<template>
  <section class="seccao4">
    <div :class="container">
      <div :class="caixatexto">
        <h2 :class="textogrande">
          Venda Onlibe e receba os pedidos pelo Whaatsapp
        </h2>
        <p :class="textphone">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus
          accusantium quidem voluptates dicta facere, tempore possimus assumenda
          quas saepe. At sint nostrum dignissimos provident modi eveniet natus
          cupiditate ad iure.
        </p>
        <button :class="bt">Comçar Agora</button>
      </div>
      <div>
        <img src="../assets/Phone.png" :alt="descricao" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "PhoneComponente",
  data() {
    return {
      seccao: "seccao",
      container: "container",
      caixatexto: "caixatexto",
      bt: "botao",
      descricao: "Imagem de um celular",
      textphone: "textophone",
      textogrande: "textogrande",
    };
  },
};
</script>

<style>
.container {
  max-width: 74rem;
  display: flex;
  gap: 4rem;
  justify-content: center;
  align-items: center;
}
.caixatexto {
  margin-bottom: 2rem;
  text-align: start;
  padding: 0 2rem;
}
.seccao4 {
  display: flex;
  justify-content: center;
  background-color: #1b2733;
  padding-top: 3.4rem;
  padding: 2.4rem 3.4rem;
}

.textogrande {
  font-size: 2.4rem;
  color: white;
  font-weight: 800;
  margin: 0;
}
.textophone {
  color: #e9e2e2;

  line-height: 26px;
}
.botao {
  padding: 1rem 2rem;
  background-color: #1fd18a;
  color: white;
  border: none;
  border-radius: 0.5rem;
  cursor: pointer;
}
</style>
