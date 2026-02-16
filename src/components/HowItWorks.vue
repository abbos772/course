<template>
  <main class="how_it_works">
    <div class="container">
      <div class="how_title">
        <h1>Как это Работает</h1>
      </div>

      <div class="steps_wrapper">
        <img src="../assets/images/Kite.png" alt="kite" class="kite_image">

        <div class="step_item step_1">
          <div class="icon_circle"><img src="../assets/images/close.png" alt=""></div>
          <p>Авторизуйтесь <br> на сайте</p>
        </div>

        <div class="step_item step_2">
          <div class="icon_circle"><img src="../assets/images/hex.png" alt=""></div>
          <p>Выберите <br> курс</p>
        </div>

        <div class="step_item step_3">
          <div class="icon_circle"><img src="../assets/images/click.png" alt=""></div>
          <p>Подайте <br> заявку</p>
        </div>

        <div class="step_item step_4">
          <div class="icon_circle"><img src="../assets/images/teacher.png" alt=""></div>
          <p>Пройдите <br> обучение</p>
        </div>

        <div class="step_item step_5">
          <div class="icon_circle"><img src="../assets/images/sms.png" alt=""></div>
          <p>Получите <br> сертификат</p>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
  .how_it_works {
    background-image: url('../assets/images/how.png');
    background-size: cover;
    background-position: center;
    padding: 80px 0;
    min-height: 600px;
    position: relative; 
    overflow: hidden;
  }

  .container {
    position: relative; 
  }

  
  .kite_image {
    position: absolute;
    right: -20px;   
    top: 50px;      
    width: 150px;   
    z-index: 1;     
    pointer-events: none;
  }

  .steps_wrapper {
    display: flex;
    justify-content: space-between;
    position: relative;
    z-index: 2;
  }

  .how_title h1 {
    text-align: center;
    font-family: 'Montserrat', sans-serif;
    font-weight: 800;
    font-size: 32px;
    color: #07274B;
    margin-bottom: 60px;
  }

  .step_item {
    width: 180px;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .icon_circle {
    width: 100px;
    height: 100px;
    background-color: #0046B8;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 15px;
    
    box-shadow: 0 5px 15px rgba(0, 70, 184, 0.3);
  }

  .icon_circle img {
    width: 50px;
  }


  .step_1 {
     margin-top: 50px;
    }
  .step_2 {
     margin-top: 280px; 
    }
  .step_3 {
     margin-top: 20px; 
    }
  .step_4 {
     margin-top: 220px; 
    }
  .step_5 {
     margin-top: 350px; 
    }


  @media (max-width: 768px) {
    .how_it_works{
      padding: 40px 0;
    }
    .step_item p{
      font-size: 13px;
    }
    .icon_circle{
      width: 80px;
      height: 80px;
    }
     .how_title h1 {
      font-size: 24px;
     }
    .kite_image {
      display: none; 
    }
    .steps_wrapper {
      flex-direction: column;
      align-items: center;
      gap: 40px;
    }
    .step_1, .step_2, .step_3, .step_4, .step_5 {
      margin-top: 0;
    }
  }
</style>