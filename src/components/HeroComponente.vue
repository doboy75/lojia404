<template>
  <section :class="hero_seccao">
    <div :class="container">
      <div>
        <img src="../assets/bro copy.png" alt="" />
      </div>
      <div :class="caixa">
        <h2 :class="texto">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatum
        </h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo
          deserunt blanditiis maxime repellendus enim quia veritatis, maiores
          ipsa quibusdam nostrum impedit cum ab tempore totam sequi, asperiores
          libero vel! Cum?
        </p>
        <button :class="bt">Comprar Agora</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HeroComponente",
  data() {
    return {
      hero_seccao: "seccao-2",
      container: "container-2",
      caixa: "caixatexto",
      bt: "botao",
    };
  },
};
</script>
<style>
.seccao-2 {
  display: flex;
  justify-content: center;
}

.container-2 {
  width: 68rem;
  display: flex;
  gap: 2rem;
  text-align: start;
}
.caixatexto {
  text-align: end;
}
.botao {
  font-size: 1.8rem;
  padding: 1rem 2rem;
  background-color: #42b983;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}
</style>
