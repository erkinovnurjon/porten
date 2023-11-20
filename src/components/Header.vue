<template >
      <div class="header">
           <div class="container">
             <div>
                  <img src="./../assets/phone.svg" alt="phone">
            <span>8 (812) 123-45-67    |    Работаем 7 дней в неделю    |    9:00 — 18:00  </span>
            </div>
           <div >
             <img src="./../assets/exit.svg" alt="">
            <span>Войти / Регистрация</span>
           </div>
           </div>
      </div>
</template>
<script>
export default {
      
}
</script>
<style scoped>
.container{
      width: 100%;
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 16px;
      box-sizing: border-box;
      display: flex;
      justify-content: space-between;
      align-items: center;
}
     .header{
      padding:  8px 0;
      height: 100%;
      background: #000;
      
     } 
     .header div{
      display: flex;
      align-items: center;
      gap: 20px;

     }
     div span{
       color:  #969696;
text-align: right;
font-family: PT Sans;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: normal;
     }
</style>