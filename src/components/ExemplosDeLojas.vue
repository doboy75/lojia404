<template>
  <section class="container-fluided d-flex justify-content-center pt-5">
    <div class="py-5" style="width: 1102.19px">
      <div style="width: 1102.19px">
        <h1
          style="
            color: #1b2733;
            font-size: 52px;
            font-weight: 700;
            margin-bottom: 99px;
          "
        >
          {{ tituloExemplosLojas }}
        </h1>
      </div>
      <div
        class="row gap-5 d-flex justify-content-center"
        style="width: 1102.19px"
      >
        <div
          class="col"
          style="
            width: 232.19px;
            border-radius: 30px;
            height: 383.88px;
            box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
          "
        >
          <h2
            style="
              font-size: 20px;
              font-weight: 700;
              color: #1b2733;
              text-align: center;
              padding-top: 28px;
            "
          >
            Loja de <br />
            Eletrônicos
          </h2>
        </div>
        <div
          class="col"
          style="
            width: 232.19px;
            border-radius: 30px;
            height: 383.88px;
            box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
          "
        >
          <h2
            style="
              font-size: 20px;
              font-weight: 700;
              color: #1b2733;
              padding-top: 28px;
            "
          >
            Loja de <br />
            Roupas
          </h2>
        </div>
        <div
          class="col"
          style="
            width: 232.19px;
            border-radius: 30px;
            height: 383.88px;
            box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
          "
        >
          <h2
            style="
              font-size: 20px;
              font-weight: 700;
              color: #1b2733;
              text-align: center;
              padding-top: 28px;
            "
          >
            Hamburgueria
          </h2>
        </div>
        <div
          class="col"
          style="
            width: 232.19px;
            border-radius: 30px;
            height: 383.88px;
            box-shadow: 1px 2px 14px 1px rgba(0, 0, 0, 0.2);
          "
        >
          <h2
            style="
              font-size: 20px;
              font-weight: 700;
              color: #1b2733;
              text-align: center;
              padding-top: 28px;
            "
          >
            Loja de <br />
            Acessórios
          </h2>
        </div>
      </div>
    </div>
  </section>
  <div class="container-fluided pt-2 d-flex justify-content-center">
    <button
      :class="btnBg_dark"
      class="d-flex justify-content-center"
      style="
        border: none;
        color: #ffffff;

        font-size: 31.14px;
        font-weight: 700;
        border-radius: 6.7px;
        padding: 10px 20px;
      "
    >
      {{ btTextoExemplosLojas }}
    </button>
  </div>
</template>
<script>
export default {
  name: "ExemplosDeLojas",
  data() {
    return {
      tituloExemplosLojas: "Veja alguns exemplos de lojas na Lojia",
      btTextoExemplosLojas: "Começar Agora",
      btnBg_dark: "btnbackground_dark",
    };
  },
};
</script>
<style>
.btnbackground_dark {
  background-color: #1b2733;
}
</style>
