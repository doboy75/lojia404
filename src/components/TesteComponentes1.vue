<template>
  <header class="header">
    <div class="container">
      <div class="logo">
        <img src="../assets/logo404.png" alt="logo" />
      </div>

      <nav class="menu">
        <a>Home</a>
        <a>Como Funciona</a>
        <a>Planos e Preços</a>
        <a>Perguntas Frequentes</a>
        <a>Contato</a>
      </nav>

      <button class="btn-outline">Começar Agora</button>
    </div>
  </header>
</template>

<script>
export default {
  name: "TesteComponentes1",
};
</script>

<style scoped>
a:visited {
  color: #fff;
  border-bottom: 2px solid #1fd18a;
}
a:hover {
  color: #fff;
  border-bottom: 2px solid #1fd18a;
}
.header {
  background: #0f2533;
  padding: 18px 0;
}
.container {
  max-width: 1200px;
  margin: auto;
  padding: 0 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.logo {
  display: flex;
  align-items: center;
  gap: 8px;
  color: #fff;
  font-weight: 700;
  margin-right: 10px;
}
.logo-circle {
  width: 34px;
  height: 34px;
  background: #1fd18a;
  color: #0f2533;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.menu {
  display: flex;
  gap: 22px;
}
.menu a {
  color: #cfd8dc;
  font-size: 14px;
  cursor: pointer;
}

.btn-outline {
  background: #fff;
  color: #0f2533;
  border: none;
  padding: 10px 16px;
  border-radius: 8px;
  font-weight: 600;
}
</style>
