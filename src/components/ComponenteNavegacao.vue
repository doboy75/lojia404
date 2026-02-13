<template>
  <header class="pz-2" style="background: #0f2533">
    <div
      class="container d-flex align-items-center justify-content-between px-4"
    >
      <div
        class="d-flex align-items-center gap-2 text-white fw-bold me-2"
        style="width: 80px; height: 100px"
      >
        <img
          src="../assets/logo404.png"
          alt="logo"
          style="width: 70.61px; height: 38.5px"
        />
        <img
          src="../assets/404.png"
          alt="logo"
          style="width: 35px; height: 19px"
        />
      </div>

      <nav class="d-flex gap-5" style="font-size: 14px">
        <a class="text-decoration-none h6 link-custom" style="color: #22b573"
          >Home</a
        >

        <a class="text-white text-decoration-none link-custom">Como Funciona</a>
        <a class="text-white text-decoration-none link-custom"
          >Planos e Preços</a
        >
        <a class="text-white text-decoration-none link-custom"
          >Perguntas Frequentes</a
        >
        <a class="text-white text-decoration-none link-custom">Contato</a>
      </nav>

      <button
        class="py-2 px-3 btn d-flex justify-content-center"
        style="
          color: #22b573;
          background-color: #ffffff;
          font-size: 14.1px;
          border-radius: 9px;
          font-weight: 700;
          cursor: pointer;
        "
      >
        Começar agora
      </button>
    </div>
  </header>
</template>

<script>
export default {
  name: "ComponenteNavegacao",
  data() {
    return {};
  },
};
</script>
