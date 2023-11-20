<template>
  <div class="hero" data-aos="fade-up">
    <div class="hero-left">
      <div class="image-container"></div>
    </div>
    <div class="container">
      <div class="content" data-aos="fade-left">
       <div class="small">
         <img src="./../assets/PORTEN.svg" alt=""> 
        <div class="line"></div> 
        <img src="./../assets/logo-2.svg" alt="">
       </div>
      </div>
      <div class="para" data-aos="fade-left" data-aos-duration="3000">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Purus interdum purus, est tortor pulvinar ut in. Fringilla a diam enim sed justo, sed iaculis sagittis. Tortor id eu interdum nec ut iaculis. Penatibus ullamcorper ultricies morbi ipsum sem metus pharetra, mi. Tortor nibh magna feugiat id nunc, dui nisl viverra.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import AOS from "aos"
export default  {
     mounted() {
        AOS.init()
     },
}
</script>

<style scoped>
.container{
    width: 100%;
    max-width: 1280px;
    margin: 0 auto;
    padding: 0 16px;
    box-sizing: border-box;
    position: relative;
    
}
  .hero-left .image-container {
    width: 100vw;
    height: 100vh;
    background-image: url('./../assets/bg.png');
    background-size: cover; 
    background-position: center; 
    background-repeat: no-repeat;
    
    z-index: -999;

}
.small {
    text-align: center;
}
.content{
    border: 4px solid #fff;
   width: 320px;
   height: 300px;
   
   display: flex;
   justify-content: center;
   align-items: center;
   position: absolute;
   top: -530px;
   left: 490px;
}
.content .line{
    width: 180px;
    height: 5px;
    background-color: #fff;
    margin: 30px 0;
}
.para{
    position: absolute;
    top: -150px;
    max-width: 900px;
    margin: auto;
    left: 200px;
}
.para p{
    color: #FFF;
text-align: center;
font-family: PT Sans;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 150%; 
text-transform: uppercase;
}
 
</style>
