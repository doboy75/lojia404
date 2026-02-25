<template>
  <section class="container-fluid bg-dark" :class="bg_img">
    <header class="container py-4 px-5">
      <div class="container d-flex align-items-center justify-content-between">
        <div class="d-flex align-items-center gap-2 text-white fw-bold me-2">
          <img src="../assets/logo404.png" alt="logo" />
          <img src="../assets/404.png" alt="logo" />
        </div>

        <nav class="container d-flex align-items-center gap-5 h5">
          <a class="text-success text-decoration-none link-custom">Home</a>

          <a class="text-white text-decoration-none link-custom"
            >Como Funciona</a
          >
          <a class="text-white text-decoration-none link-custom"
            >Planos e Preços</a
          >
          <a class="text-white text-decoration-none link-custom"
            >Perguntas Frequentes</a
          >
          <a class="text-white text-decoration-none link-custom">Contato</a>

          <button
            class="text-success bg-white rounded-4 py-2 px-3 btn d-flex justify-content-center ms-5"
            :class="btn_texto"
          >
            Começar agora
          </button>
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
            class="h3 d-flex justify-content-center btn btn-success text-white fw-bold py-4 px-5 rounded-4"
          >
            Começar Agora
          </button>
        </div>

        <div class="col-lg-7 d-flex justify-content-center">
          <img src="../assets/video.png" alt="Imagem Hero " class="w-100" />
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
      bg_img: "bg_img",
    };
  },
};
</script>
<style scoped>
.bg_img {
  background-image: url("../assets/Group.png");
  background-size: cover;
  background-position: auto;
}
</style>
