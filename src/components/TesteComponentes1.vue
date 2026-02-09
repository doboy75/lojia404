<template>
  <header class="pz-2" style="background: #0f2533">
    <div
      class="container d-flex align-items-center justify-content-between px-4"
    >
      <div
        class="d-flex align-items-center gap-2 text-white fw-bold me-2"
        style="width: 80px; height: 100px"
      >
        <img src="../assets/logo404.png" alt="logo" />
      </div>

      <nav class="d-flex gap-4 h5">
        <a class="text-white text-decoration-none link-custom">Home</a>
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
        class="btn bg-white text-dark border-0 px-5 py-3 fw-semibold fs-5 rounded-3"
      >
        Começar Agora
      </button>
    </div>
  </header>
</template>

<script>
export default {
  name: "TesteComponentes1",
};
</script>

<style scoped>
/*
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
/*
.container {
  max-width: 1200px;
  margin: auto;
  padding: 0 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
 

.logo {
  width: 80px;
  height: 100;
  display: flex;
  align-items: center;
  gap: 8px;
  color: #fff;
  font-weight: 700;
  margin-right: 10px;
}
  

.menu {
  display: flex;
  gap: 22px;
}
.menu a {
  color: #cfd8dc;
  font-size: 20px;
  cursor: pointer;
}
/*

.btn-outline {
  background: #fff;
  color: #0f2533;
  border: none;
  padding: 20px 40px;
  border-radius: 8px;
  font-weight: 600;
  font-size: 20px;
}
  */
</style>
