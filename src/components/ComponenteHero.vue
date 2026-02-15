<template>
  <section
    class="container-fluided d-flex justify-content-center"
    :class="bg_dark"
    style="padding: 8.5rem 0"
  >
    <div class="row row align-items-center min-vh-100" style="width: 1440px">
      <div class="col-lg-5 text-start">
        <h1 style="font-size: 50px; color: #ffffff; font-weight: 700">
          Venda Online e<br />
          receba os <br />pedidos pelo <br />Whatsapp
        </h1>

        <p
          class="text-white lh-base"
          style="
            font-size: 20px;
            color: #ffffff;
            font-weight: 300;
            margin-bottom: 30px;
            margin-top: 30px;
          "
        >
          Tenha um
          <span style="display: block; font-weight: 500; font-size: 25px"
            >Catálogo Digital</span
          >
          dos
          <br />
          seus produtos para você vender<br />
          pela internet.
        </p>

        <button
          class="d-flex justify-content-center"
          style="
            padding: 15px 30px;
            border-radius: 9px;
            background-color: #22b573;
            color: #ffffff;
            font-size: 27.22px;
            font-weight: 700;
            margin-top: 32px;
            cursor: pointer;
          "
        >
          Começar Agora
        </button>
      </div>

      <div class="col-lg-6 imagem-video">
        <img
          src="../assets/video.png"
          alt="Imagem Hero "
          style="width: 756px; height: 469px"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ComponenteHero",
  data() {
    return {
      corverde: "#22b573",
      bg_dark: "background_dark",
    };
  },
};
</script>
