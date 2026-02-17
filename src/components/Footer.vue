<script setup>
</script>

<template>
 <footer>
  <div class="container">
   <div class="foot_flex">
   <div class="foot">
   <img src="../assets/images/Logo.png" width="74" alt="">
   <p>Сайт по профессиональному обучению - это кладезь разнообразных курсов, с возможностью найти подходящее направление именно для Вас, обучиться новой профессии и получить сертификат об окончании.
  </p>
   </div>
   <div class="foot">
    <h4>Контакты</h4>
    <p>Амира Темура проспект, <br>  62, Ташкент </p>
    <div class="socials">
    <img src="../assets/images/Email.png" width="20"  alt="">
    <p>Akm@mehnat.uz </p>
   </div>
    <div class="socials">
    <img src="../assets/images/phone.png" width="20"  alt="">
    <p>+9989 71 200-06-00  </p>
   </div>
      </div>
   <div class="foot">
     <img src="../assets/images/met.png" width="200" alt="">
     <img src="../assets/images/kub.png" width="200" alt="">
   </div>
   </div>
   <p class="bottom">2023 ООО «Центр управления проектами в сфере труда» Все права защищены</p>
   </div>
   
 </footer>
</template>

<style scoped>
footer {
  border: 2px solid #FFFFFF;
  padding: 60px 40px 15px;
  border-top-left-radius: 110px;
  background: linear-gradient(116.84deg,#E5F0FF 25.47%,#F2E8FD 103.05%);
  background: linear-gradient(116.84deg,color(display-p3 0.906 0.941 1) 25.47%,color(display-p3 0.941 0.910 0.984) 103.05%);
}
.bottom{
    margin-top: 30px;
    color: #07274BCC;

}
.socials{
    display: flex;
    align-items: center;
    gap: 10px;
}
.foot{
    display: flex;
    flex-direction: column;
    gap: 25px;
}
.foot p{
    max-width: 450px;
    width: 100%;
    font-family: Montserrat;
    font-weight: 400;
    font-style: Regular;

    line-height: 169%;
    letter-spacing: 0%;
    text-align: justify;
    color: #07274B;

}
.foot_flex{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 15px;
    flex-wrap: wrap;
    padding-bottom: 30px;
    border-bottom: 2px solid #FFFFFF;
}
@media (max-width: 480px) {
  p{
    font-size: 12px;
  }
  h4{
    font-size: 15px;
  }
}
</style>