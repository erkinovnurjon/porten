<template >
  <div>
   
    <Header />
    <div class="container">
      <Navbar />
    </div>
      <Hero />

  </div>
</template>

<script>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Navbar from './components/Navbar.vue';
import AOS from "aos"
export default {
  components:{
    Header,
    Navbar,
    Hero
},
mounted() {
  AOS.init()
},
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