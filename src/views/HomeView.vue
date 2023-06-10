<template>
  <div>
    <main>
      <section
        class="banners banner-1 d-flex flex-column justify-content-center text-center"
      >
        <div class="banners-titulo bg-body-secondary py-5">
          <h2 class="fw-bold">Sua pausa para desfrutar a vida.</h2>
          <p>
            Boas -vindas ao & Bistrô Serenatto! Um ambiente aconchegante e
            acolhedor para apreciar um bom café.
          </p>
        </div>
      </section>
      <the-cards-vue />
      <section
        class="banners banner-2 d-flex flex-column justify-content-center text-center"
      >
        <div class="banners-titulo bg-body-secondary py-5">
          <h2 class="fw-bold">Portas abertas para todos os públicos.</h2>
          <p>
            Nosso espaço é aconchegante, pet friendly, preparado para receber
            crianças e pessoas com deficiência. Também oferecemos ambientes de
            coworking!
          </p>
        </div>
      </section>
      <novos-produtos-vue />
    </main>
  </div>
</template>

<script>
import TheCardsVue from "@/components/TheCards.vue";
import NovosProdutosVue from "@/components/NovosProdutos.vue";
export default {
  components: {
    TheCardsVue,
    NovosProdutosVue,
  },
};
</script>

<style scoped>
.banner-1 {
  background-image: url(../assets/imgs/banner-1.png);
}
.banner-2 {
  background-image: url(../assets/imgs/banner-2.png);
}
.banners {
  width: 100%;
  height: 80vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
.banners-titulo {
  --bs-bg-opacity: 0.2;
}
</style>
