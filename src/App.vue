<template >
  <div class="container">
    <Header />
    <Navbar />
    <Hero />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Navbar from './components/Navbar.vue';
export default {
  components:{
    Header,
    Navbar,
    Hero
}
}
</script>

<style >
  .container{
    width: 100%;
    max-width: 1280px;
    margin: 0 auto;
    padding: 0 16px;
    box-sizing: border-box;
  }
</style>