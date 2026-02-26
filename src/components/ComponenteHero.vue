<template>
  <section
    class="container-fluid"
    :class="{ /* bg_img, */ bg_dark, bg_imgEstilo }"
  >
    <header class="container-fluid py-4 px-5">
      <div class="container d-flex align-items-center justify-content-between">
        <div class="d-flex align-items-center gap-2 text-white fw-bold me-2">
          <img src="../assets/logo404.png" alt="logo" />
          <img src="../assets/404.png" alt="logo" />
        </div>

        <nav
          class="container-fluid justify-content-center d-flex align-items-center gap-5 h5"
        >
          <a
            href="#comer"
            class="text-decoration-none link-custom fw-bold"
            :class="btnColor_green"
            >Home</a
          >

          <a
            href="#comoFunciona"
            class="text-white text-decoration-none link-custom"
            >Como Funciona</a
          >
          <a href="#precos" class="text-white text-decoration-none link-custom"
            >Planos e Preços</a
          >
          <a
            href="#perguntas"
            class="text-white text-decoration-none link-custom"
            >Perguntas Frequentes</a
          >
          <a
            href="#contacto"
            class="text-white text-decoration-none link-custom"
            >Contato</a
          >

          <div
            class="bg-light rounded-4 fw-bold py-2 px-4 btn d-flex justify-content-center ms-5"
            :class="{ btnColor_green }"
          >
            Começar agora
          </div>
        </nav>
      </div>
    </header>
    <div class="container d-flex justify-content-center">
      <div class="container row row align-items-center min-vh-100">
        <div class="col-lg-5 text-start">
          <h1 class="display-3 text-white fw-bold">
            Venda Online e<br />
            receba os <br />pedidos pelo <br />Whatsapp
          </h1>

          <p class="text-white lh-base h4 fw-semi-bold mt-4 mb-5">
            Tenha um
            <span class="fw-bold h3">Catálogo Digital</span>
            dos
            <br />
            seus produtos para você vender<br />
            pela internet.
          </p>

          <button
            class="h3 py-3 px-5 rounded-4 fw-bold-flex justify-content-center text-light"
            :class="{ btnColor_fundo_green }"
          >
            Começar Agora
          </button>
        </div>

        <div class="col-lg-7 d-flex justify-content-center">
          <div class="w-100">
            <h2 class="text-light display-6 fw-bold">Veja como funciona:</h2>
            <img src="../assets/video.png" alt="Imagem Hero " class="w-100" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ComponenteHero",
  data() {
    return {
      /*       bg_img: "bg_img", */
      bg_imgEstilo: "bg_imgEstilo",
      bg_dark: "bg_dark",
      btnColor_green: "btnColor_green",
      btnColor_fundo_green: "btnColor_fundo_green",
    };
  },
};
</script>
<style scoped>
/* .bg_img {
  background-image: url("../assets/BG (1).png");
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
} */
.bg_dark {
  background-color: #1b2733;
}
.bg_imgEstilo {
  background-image: url("../assets/Pattern (1).png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.btnColor_green {
  color: #22b573;
}
.btnColor_fundo_green {
  background-color: #22b573;
}
</style>
