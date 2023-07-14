<script>

  import AppHeader from './components/AppHeader.vue';
  import AppHero from './components/AppHero.vue';
  import AppProducts from './components/AppProducts.vue'
  import AppMain from './components/AppMain.vue';
  import AppShortMenu from './components/AppShortMenu.vue'
  import AppFooter from './components/AppFooter.vue';

  export default {

  name: 'Vite Comics',

  components: { AppHeader, AppHero, AppProducts, AppMain, AppShortMenu, AppFooter },

  data() {
      return {}
    }
  } 

</script>


<template>

  <AppHeader />
  <AppHero />
  <AppProducts />
  <AppMain />
  <AppShortMenu />
  <AppFooter />

</template>

<style lang="scss">

    @use 'assets/scss/style.scss';

</style>