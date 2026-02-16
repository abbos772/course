<script setup>
</script>

<template>
  <main class="hero">
    <div class="container">
      <div class="hero_flex">
      <div class="left">
        <h1>Станьте <span>Экспертом</span> <br> в своей области!</h1>
        <p>Подберите нужный курс и станьте  востребованным специалистом в желаемой индустрии</p>
        <img src="../assets/images/svg.png" alt="">
      </div>
      <div class="right">
        <img src="../assets/images/std.jpg" alt="">
      </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
    .hero {
      background: url('../assets/images/back.png');
      display: flex;
      align-items: center;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
    }
    .container {
      max-width: 1150px;
      margin: 0 auto;
      width: 100%;
    }
    .hero_flex{
      margin-top: 100px;
     display: flex;
      align-items: center;
      justify-content: space-between;
      width: 100%;
      flex-wrap: wrap;
    } 
    .left {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 20px;
    }
    .left img{
      position: relative;
      top: 60px;
    }
    span{
      font-weight:bolder;
      color: #07274B;

    }
    .left h1 {
      font-size: 36px;
      font-weight:600;
      margin: 0 0 12px;
      color: #07274B;
    }
    .left p {
      font-size: 16px;
      margin: 0;
      color: #334155;
      width: 350px; 
      font-weight: 400;
      color: #272727CC;
      line-height: 158%;
    }
    .right {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .right img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    @media (max-width: 768px) {
      .left img{
        top: 10px;
        width: 50%;
      }
      .container{
        text-align: center;
      }
      .hero_flex{
        margin-top: 5px;
        display: flex;
        flex-direction: column;
        align-items: center;
        flex-wrap: wrap;
        padding: 20px;
      }
      .left{
        align-items: center;
        justify-content: center;
      }
      .left p{
        width: auto;
      }
      .left h1 {
         font-size: 22px; 
        }
        .left p{
          font-size: 14px;
        }
      .right img {
         width: 100%; 
        }
    }
</style>
