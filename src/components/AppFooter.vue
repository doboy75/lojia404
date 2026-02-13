<template>
  <section :class="footer_seccao">
    <footer :class="footer_cartao">
      <div :class="footeres">
        <img src="../assets/Group (4).png" :alt="logo" />
      </div>
      <div :class="footeres">
        <p :class="numero">
          Somos uma plantaforma de Catalogo Digital<br />
          que busca ajudar o Micro e pequeno <br />empreendedor angolano a
          vender mais<br />
          pela internet
        </p>
      </div>
      <div :class="footeres">
        <p :class="verde">Lojia 404</p>
        <p :class="numero">
          Tutorias<br />
          Atendimentos <br />Termos de Uso <br />Politica de Privacidade
        </p>
      </div>
      <div :class="footeres">
        <p :class="verde">Soporte</p>
        <p :class="numero">
          (+244) 9300000<br />
          lojoa404.gmail.com<br />
        </p>
        <img src="../assets/icones (1).png" alt="" />
      </div>
    </footer>
  </section>
</template>
<script>
export default {
  name: "AppFooter",
  data() {
    return {
      footer_seccao: "seccao_footer",
      footer_cartao: "footer_cartao",
      footeres: "footeres ",
      numero: "numero",
      verde: "verde",
      logo: "logo do footer",
    };
  },
};
</script>
<style>
.seccao_footer {
  padding: 8rem 16rem;
}
.footer_cartao {
  display: flex;

  justify-content: center;
  gap: 4.5rem;
}
.footeres {
  text-align: start;
}
.verde {
  color: #42b983;
  font-size: 20px;
  font-weight: 600;
  line-height: 0px;
}
</style>
