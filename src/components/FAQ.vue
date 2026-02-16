<script setup></script>

<template>
  <main id="faq">
  <div class="FAQ"> 
    <h1>FAQ</h1>
    <h3>Часто Задаваемые Вопросы</h3>
  </div>
  <div class="container">
  <div class="FAQ_inputs">
  <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
    <div class="FAQ_input">
  <p>Как я могу записаться на желаемый курс?</p>
  <img src="../assets/images/down.png" alt="">
  </div>
  </div>
  </div>
  </main>
</template>

<style scoped>
 .FAQ{
    background-image: url(../assets/images/FAQ.png);
    background-size: cover;
    background-position: center;
    width: 100%;
    height: 32vh;
    margin-bottom: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 10px;
}

 .FAQ h1{
    font-family: Montserrat;
    font-weight: 800;
    font-style: ExtraBold;
    font-size: 55px;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: -2%;
    text-align: center;
    text-transform: uppercase;
    color: #FFFFFF;

 }
 .FAQ h3{
    font-family: Montserrat;
    font-weight: 600;
    font-style: SemiBold;
    font-size: 20px;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: -2%;
    text-align: center;
    color: #FFFFFF;
 }
 .FAQ_inputs{
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    align-items: center;
    justify-content: center;
 }
 .FAQ_input img{
    width: 30px;
    height: 30px;
 }
 .FAQ_input{
    width: 44%;
    height: 90px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    background: #F5F6FA;
    padding: 2px;
    border-radius: 20px;
 }
 @media (max-width: 768px) {
  .FAQ_input {
    width: 70%;
    padding: 10px;
    font-size: 14px;
  }
}
 @media (max-width: 480px) {
  .FAQ_input {
    width: 90%;
    padding: 10px;
    font-size: 11px;
    height: 70px;
  }
}
</style>