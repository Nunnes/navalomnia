<template>
  <div id="app">
     <NavMenu />
    <HeroSection />
    
  </div>
</template>

<script>
import NavMenu from './components/NavMenu.vue';
import HeroSection from './components/HeroSection.vue';


export default {
  name: 'App',
  components: {
    NavMenu,
    HeroSection
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
