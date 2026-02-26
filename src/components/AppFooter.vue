<template>
  <section class="container-fluid d-flex justify-content-center pt-5">
    <footer class="container d-flex justify-content-center row gap-3 p-5">
      <div class="col d-flex justify-content-center align-items-center gap-3">
        <img src="../assets/Group (4).png" alt="logo" />
        <img src="../assets/404 (1).png" alt="logo" />
      </div>
      <div class="col text-start fw-bold">
        <p>
          Somos uma plataforma de Catálogo Digital que busca ajudar o Micro e
          Pequeno Empreendedor angolano a vender mais pela internet.
        </p>
      </div>

      <div class="col text-start">
        <span class="fw-bold d-block text-success">Lojia 404</span>
        <span class="d-block">Tutoriais</span>
        <span class="d-block">Atebdimento</span>
        <span class="d-block">Termos de Uso</span>
        <span class="d-block">Políticas de Privacidade</span>
      </div>
      <div class="col text-start">
        <span class="d-block fw-bold text-success">Suporte </span>
        <span class="d-block">( +244 939000000)</span>
        <span class="d-block">lojia404.gmail.com</span>
        <span><img src="../assets/icones copy.png" alt="logo" /></span>
      </div>
    </footer>
  </section>
</template>
<script>
export default {
  name: "AppFooter",
  data() {
    return {
      color_dark: "color_dark",
    };
  },
};
</script>
<style scoped>
.color_dark {
  color: #1b2733;
}
</style>
