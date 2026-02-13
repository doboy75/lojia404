<template>
  <section class="d-flex justify-content-center container-fluided">
    <div class="row p-5 text-start" style="width: 1154px">
      <div class="col">
        <h2 style="font-size: 50px; font-weight: 700; color: #1b2733">
          {{ textoCatalogo }}
        </h2>
        <p
          style="
            color: #1b2733;
            font-size: 20 px;
            font-weight: 300;
            margin-top: 38px;
          "
        >
          {{ conteudoCatalogo }}
        </p>
        <button
          class="d-flex justify-content-center"
          style="
            padding: 15px 30px;
            border-radius: 9px;
            background-color: #22b573;
            color: #ffffff;

            font-weight: 700;
            margin-top: 32px;
            cursor: pointer;
            border: none;
            font-size: 31.14px;
            margin-bottom: 40.61px;
          "
        >
          {{ textbtn }}
        </button>
      </div>
      <div class="col">
        <img
          src="../assets/bro.png"
          :alt="descrição"
          style="width: 493.85px; height: 434.22px"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "OqueVender",

  data() {
    return {
      descrição: "mulher segurando um celular",
      textoCatalogo: "  O que da pra vender no catálogo da lojia?",
      conteudoCatalogo:
        "O Catálogo Digital da lojia é ideal para vocé vender o que quiser,seja loja de roupas,semijoias,sapatos,peças automativas ou até no ramo alimentício como restaurante,lanchonetes,mercados e padarias.È a sua loja de forma simples,prática e  rápida!",
      textbtn: "Começar Agora",
    };
  },
};
</script>
