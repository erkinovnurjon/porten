<template >
      <div class="navbar" data-aos="fade-down">
          <div class="nav-left">
            <img src="./../assets/PORTEN.svg" alt="">
          </div> 
          <div class="nav-right">
           
             <ul>
                <li>Понравилось</li>
                <li>личный кабинет</li>
                <li>настройки</li>
            </ul>
           
             <span>

                   <img src="./../assets/korzinka.svg" alt="">
                   <img src="./../assets/search.svg" alt="">
             </span>
            
          </div>
      </div>
</template>
<script>
      import AOS from 'aos'; // AOS kutubxonasini import qilish
export default {
  
 
    mounted() {
      AOS.init(); // AOS-ni boshlash
    }
  
}
</script>
<style scoped >
    .navbar{
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 15px 0 ;
    }  
    .nav-right{
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 150px;
    }
    
    .navbar ul{
      display: flex;
      list-style: none;
      gap: 40px;
    }
    .nav-right ul li {
      color:  #969696;
font-family: 'PT Sans', sans-serif;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-transform: uppercase;
    }
    .nav-right ul li:hover{
      color: #fff;
      transition: all ease .8s;
    }
    .nav-right span {
      display: flex;
      gap: 30px;
    }
</style>