<template>
  <!-- SITEMIAMO TUTTO E POI AGGIUNGIAMO I FONTS !!!-->
  <HeaderComponent />
  <JumboComponent />


  <MainComponent />
  <FooterComponent />

</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import JumboComponent from './components/JumboComponent.vue';
export default {
  components: { HeaderComponent, MainComponent, FooterComponent, JumboComponent }
}
</script>

<style lang="scss" scoped>
nav {
  position: absolute;
  top: 0;
}
</style>