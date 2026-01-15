<template>
  <section class="hero">
    <div class="container grid">
      <div class="text">
        <h1>
          Venda Online e<br />
          receba os pedidos<br />
          pelo Whatsapp
        </h1>

        <p>
          Tenha um Catálogo Digital dos seus produtos para você vender pela
          internet.
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
  padding: 80px 0;
}
.container {
  max-width: 1200px;
  margin: auto;
  padding: 0 24px;
}
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  align-items: center;
}
.text h1 {
  color: #fff;
  font-size: 42px;
}
.text p {
  color: #cfd8dc;
  margin: 20px 0;
}
.btn-primary {
  background: #1fd18a;
  border: none;
  padding: 14px 28px;
  border-radius: 10px;
  font-weight: 600;
}
.imagem-video img {
  width: 100%;
  height: auto;
  
}
</style>
