<script>

  import AppHeader from './components/AppHeader.vue';
  import AppHero from './components/AppHero.vue';
  import AppMain from './components/AppMain.vue';
  import AppShortMenu from './components/AppShortMenu.vue'
  import AppFooter from './components/AppFooter.vue';

  export default {

  name: 'Vite Comics',

  components: { AppHeader, AppHero, AppMain, AppShortMenu, AppFooter },

  data() {
      return {}
    }
  } 

</script>


<template>

  <AppHeader />
  <AppHero />
  <AppMain />
  <AppFooter />

</template>

<style lang="scss">

    @use 'assets/scss/style.scss';

</style>