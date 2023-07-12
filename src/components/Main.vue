<template>
  <div class="main">
    <div class="main__container">
      <div class="main__phone-section">
        <div class="main__phone-section__help">
          <h2>Помощь</h2>
        </div>
        <div class="main__phone-section__hot-line">
          <p>Телефон горячей линии</p>
          <h2>8 (800) 500-30-20</h2>
        </div>
      </div>
      <Cards />
      <Description />
      
    </div>
    <Footer />
  </div>
</template>
  
  <script>
import Cards from "./Cards.vue";
import Description from "./Description.vue";
import Footer from "./Footer.vue";

export default {
  components: {
    Cards,
    Description,
    Footer,
  },
};
</script>
  
  <style lang="scss">
</style>