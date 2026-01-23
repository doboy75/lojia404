<template>
  <section class="hero">
    <div class="container grid">
      <div class="text">
        <h1>
          Venda Online e<br />
          receba os pedidos<br />
          pelo Whatsapp
        </h1>

        <p class="entrada">
          Tenha um Catálogo Digital dos<br />
          seus produtos para você vender pela internet.
        </p>

        <button class="btn-primary">Começar Agora</button>
      </div>

      <div class="imagem-video">
        <img src="../assets/video.png" alt="Imagem Hero" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TesteComponentes2",
};
</script>

<style scoped>
.hero {
  background: #0f2533;
  padding: 8rem 0;
}
.container {
  max-width: 120rem;
  margin: auto;
  padding: 0 2rem;
}
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 6rem;
  align-items: center;
}
.text h1 {
  color: #fff;
  font-size: 4.1rem;
}
.entrada {
  font-size: 24px;
  line-height: 40px;
}
.text p {
  color: #cfd8dc;
  margin: 2rem 0;
}
.btn-primary {
  background: #1fd18a;
  border: none;
  padding: 1rem 3rem;
  border-radius: 1rem;
  font-weight: 600;
  font-size: 1.7rem;
}
.imagem-video img {
  width: 100%;
  height: auto;
}
</style>
