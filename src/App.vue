<template>
  <!-- SITEMIAMO TUTTO E POI AGGIUNGIAMO I FONTS !!!-->
  <div class="position">
    <!-- <GotopComponent /> -->
    <HeaderComponent />
    <JumboComponent />
    <GotopComponent />

    <MainComponent />
    <FooterComponent />

  </div>

</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import JumboComponent from './components/JumboComponent.vue';
import GotopComponent from './components/GotopComponent.vue';
export default {
  components: { HeaderComponent, MainComponent, FooterComponent, JumboComponent, GotopComponent }
}
</script>

<style lang="scss" scoped>
nav {
  position: absolute;
  top: 0;
}

.position {
  position: relative
}



.gotop {
  position: fixed;
  background-color: rgb(65, 64, 64);
  width: 50px;
  height: 50px;
  padding: 10px;
  text-align: center;
  bottom: 10px;
  right: 15px;
  color: white;
  z-index: 5000;
  border-radius: 15px;

  i {
    color: white;
  }

  .changecolor {
    color: white;
  }
}
</style>