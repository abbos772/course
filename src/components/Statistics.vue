<script setup>
</script>

<template>
  <main class="stats_section">
    <div class="container">
      <h1>Статистика</h1>
      <div class="top_cards">
        <div class="stat_card border_blue">
          <div class="card_top">
            <img src="../assets/images/telegram.png" alt="">
            <p>Получили направление на обучение</p>
          </div>
          <h2>13 948</h2>
        </div>

        <div class="stat_card border_green">
          <div class="card_top">
            <img src="../assets/images/icon2.png" alt="">
            <p>Обучаются на данный момент</p>
          </div>
          <h2>37 978</h2>
        </div>

        <div class="stat_card border_purple">
           <div class="card_top">
            <img src="../assets/images/icon3.png" alt="">
             <p>Закончили обучение</p>
          </div>
          <h2>29 074</h2>
        </div>

        <div class="stat_card border_yellow">
           <div class="card_top">
            <img src="../assets/images/icon4.png" alt="">
             <p>Количество устроившихся на работу</p>
          </div>
          <h2>91 132</h2>
        </div>
      </div>

      <div class="bottom_section">
        <div class="map_box">
          <img src="../assets/images/map.png" alt="">
        </div>

        <div class="right_stats">
          <div class="small_card">
            <p>Общее количество студентов по городам, областям и всему Узбекистану</p>
            <h3>243 099</h3>
          </div>

          <div class="small_card">
             <p>Количество курсов по городам, областям и всему Узбекистану</p>
             <h3>189</h3>
          </div>

          <div class="small_card">
             <p>Количество учебных центров по Узбекистану</p>
             <h3>1 526</h3>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
  .stats_section {
    background: #F5F6FA;
    padding: 50px 0;
    font-family: sans-serif;
    margin-top: 55px;
  }

  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }

  h1 {
    text-align: center;
    color: #07274B;
    font-size: 32px;
    font-weight: 800;
    margin-bottom: 40px;
  }

  .top_cards {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    margin-bottom: 30px;
    flex-wrap: wrap;
  }

  .stat_card {
    background: #fff;
    width: 23%;
    padding: 20px;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 180px;
    box-sizing: border-box;
  }

  .card_top {
    display: flex;
    gap: 15px;
  }

  .card_top img {
    width: 40px;
    height: 40px;
    object-fit: contain;
  }

  .stat_card p {
    font-size: 13px;
    color: #555;
    margin: 0;
    line-height: 1.4;
  }

  .stat_card h2 {
    font-size: 28px;
    color: #07274B;
    font-weight: 800;
    margin: 0;
  }

  .border_blue {
     border-bottom: 4px solid #0046B8; 
    }
  .border_green {
     border-bottom: 4px solid #00B887; 
    }
  .border_purple {
     border-bottom: 4px solid #8C52FF; 
    }
  .border_yellow {
     border-bottom: 4px solid #FFBE0B; 
    }

  .bottom_section {
    display: flex;
    justify-content: space-between;
    gap: 20px;
  }

  .map_box {
    width: 68%;
    background: #fff;
    padding: 10px;
    border-radius: 20px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
  }

  .map_box img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 15px;
  }

  .right_stats {
    width: 30%;
    display: flex;
    flex-direction: column;
    gap: 20px;
  }

  .small_card {
    background: #F4F5FA;
    padding: 25px;
    border-radius: 20px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .small_card p {
    font-size: 14px;
    color: #666;
    margin-bottom: 10px;
  }

  .small_card h3 {
    font-size: 26px;
    color: #0046B8;
    font-weight: 800;
    margin: 0;
  }

  @media (max-width: 900px) {
    .top_cards {
      justify-content: center;
    }
    
    .stat_card {
      width: 45%;
      margin-bottom: 20px;
      padding: 10px;
      gap: 5px;
      height: auto;
    }
    .stat_card p{
        font-size: 10px;
    }
    .stat_card h2{
        font-size: 20px;
    }
    .card_top{
        display: flex;
        flex-direction: column;
    }
    .bottom_section {
      flex-direction: column;
    }
    .map_box {
      width: 100%;
      height: auto;
    }
    .right_stats {
      width: 100%;
      align-items: center;
      justify-content: center;
      flex-wrap: wrap;
    }
    .small_card {
      width: 100%;
    }
  }
</style>