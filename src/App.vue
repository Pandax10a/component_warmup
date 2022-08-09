<template>
  <div id="app">
    
    <product-hero-vue/>
    <productinfo/>
    <page-footer/>
    
  </div>
</template>

<script>
import PageFooter from './components/pageFooter.vue'


import productHeroVue from './components/productHero.vue'
import Productinfo from './components/productinfo.vue'

export default {
  
  components: {
    productHeroVue,
    Productinfo,
    PageFooter,
    
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
