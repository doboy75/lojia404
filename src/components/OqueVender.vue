<template>
  <section :class="centralizar">
    <div :class="tamanhoContainer">
      <div :class="caixatexto">
        <h2>O que da pra vender no catálogo da lojia?</h2>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quo, soluta
          magnam suscipit magni similique excepturi pariatur debitis nisi
          architecto, perspiciatis voluptatem numquam eaque ipsum? Quasi
          excepturi voluptate odit minima tenetur.
        </p>
        <button :class="bt">Começar Agora</button>
      </div>
      <div>
        <img :class="imagem" src="../assets/bro.png" :alt="descrição" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "OqueVender",

  data() {
    return {
      centralizar: "centro",
      tamanhoContainer: "container-4",
      descrição: "mulher segurando um celular",
      imagem: "imagem",
      bt: "botao",
    };
  },
};
</script>

<style>
.imagem {
  text-align: start;
}
.centro {
  padding: 0 3rem;
  justify-content: center;
  display: flex;
}
.container-4 {
  width: 68rem;
  display: flex;
  gap: 2rem;
  text-align: start;
}
.caixatexto {
}
h2 {
  font-size: 2.2rem;
  margin-bottom: 1.2rem;
  color: #000;
}
p {
  color: #333;
  line-height: 24px;
  font-size: 1.1rem;
}
.botao {
  font-size: 1.8rem;
  margin-top: 1.5rem;
  padding: 0.8rem 1.5rem;
  background-color: #42b983;
  color: #fff;
  border: none;
  border-radius: 9px;
  font-weight: 700;
  cursor: pointer;
}
</style>
