<script setup>
</script>

<template>
  <main>
    <h1 id="course_video">Популярные видеоуроки</h1>
   <div class="container">
     <div class="videos">
      <div class="video_card">
       <div class="video">
       <img src="../assets/images/man.png" alt="">
       </div>
        <div class="video_text">
        <h4>Урок 1</h4>
        <span class="line">|</span>
        <img src="../assets/images/star.png" alt="">
        <h4>4.7</h4>
        <img src="../assets/images/eyee.png" alt="">
        <p>(2078)</p>
        </div>
        <p>Ёш болаларда соч мошинкаси насадка <br> ёрдамида сочни қисқартириш</p>
       </div>
        <div class="video_card">
       <div class="video">
       <img src="../assets/images/girl.png" alt="">
       </div>
        <div class="video_text">
        <h4>Урок 1</h4>
        <span class="line">|</span>
        <img src="../assets/images/star.png" alt="">
        <h4>4.7</h4>
        <img src="../assets/images/eyee.png" alt="">
        <p>(2078)</p>
        </div>
        <p>Ёш болаларда соч мошинкаси насадка <br> ёрдамида сочни қисқартириш</p>
       </div>
        <div class="video_card">
       <div class="video">
       <img src="../assets/images/girl2.png" alt="">
       </div>
        <div class="video_text">
        <h4>Урок 1</h4>
        <span class="line">|</span>
        <img src="../assets/images/star.png" alt="">
        <h4>4.7</h4>
        <img src="../assets/images/eyee.png" alt="">
        <p>(2078)</p>
        </div>
        <p>Ёш болаларда соч мошинкаси насадка <br> ёрдамида сочни қисқартириш</p>
       </div>
     </div>
   </div>
   <div class="popular_courses">
   <h1>Популярные видеокурсы</h1>
   <div class="images container">
   <div class="card one">
   <img src="../assets/images/play.png" class="play" alt="">
   <div class="img_text">
   <p>Erkaklar sartaroshligi</p>
   <img src="../assets/images/star.png" alt="">
    <h4>4.7</h4>
   </div>
   </div>
   <div class="card two">
   <img src="../assets/images/play.png" class="play" alt="">
   <div class="img_text">
   <p>Ayollar sartaroshligi</p>
   <img src="../assets/images/star.png" alt="">
    <h4>4.7</h4>
   </div></div>
   <div class="card three">
   <img src="../assets/images/play.png" class="play" alt="">
   <div class="img_text">
   <p>Oshpazlik</p>
   <img src="../assets/images/star.png" alt="">
    <h4>4.7</h4>
   </div></div>
   <div class="card four">
   <img src="../assets/images/play.png" class="play" alt="">
   <div class="img_text">
   <p>Qandolat</p>
   <img src="../assets/images/star.png" alt="">
    <h4>4.7</h4>
   </div></div>
   </div>
   </div>
  </main>
</template>
  
<style scoped>
  .popular_courses{
    background: #CED3E633;
    margin-top: 10px;
  }
  .popular_courses h1{
    padding: 15px;
  }
  .images{
    display: flex;
    align-items: center;
    gap: 20px;
    padding: 10px;
    margin-bottom: 25px;
  }
  .img_text{
    display: flex;
    align-items: center;
    gap: 10px;
    width: 100%;
    position: relative;
    top: 120px;
    color: white;
    font-size: 15px;
  }
  .card{
    position: relative;
    width: 300px;
    height: 160px;
     background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    border-radius: 20px;
    padding: 10px;
  }
  .play{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 50px;
    height: 50px;
  }
  .one{
    background-image: url(../assets/images/one.png);
  }
  .two{
    background-image: url(../assets/images/two.png);
  }
  .three{
    background-image: url(../assets/images/three.png);
   }
   .four{
    background-image: url(../assets/images/four.png);
   }
   @media (max-width: 768px) {
    .img_text {
        font-size: 13px;
    }
     .images {
       flex-wrap: wrap;
       justify-content: center;
     }
     .card {
       width: 100%;
       max-width: 300px;
     }
   }
  main h1{
    text-align: center;
    font-family: Montserrat;
    font-weight: 800;
    font-style: ExtraBold;
    font-size: 26px;
    color: #07274B;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: -2%;
    text-align: center;
    margin-top: 40px;
  }
  .line{
   color: rgb(235, 226, 226);
   width: 1px;
  }
  .video_text{
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 15px;
    margin-top: 15px;
  }
  .video_text p{
    color: #07274B80;
    font-size: 12px;
  }
  .video_card p{
    color: #07274BCC;

  }
  .video img{
    max-width: 370px;
    width: 100%;
  }
  .videos{
    margin-top: 50px;
    display: flex;
    gap: 20px;
    justify-content: center;
    
  }
  @media (max-width: 768px) {
    .videos {
      flex-wrap: wrap;
      align-items: center;
    }
    .video_card {
      width: 100%;
      max-width: 200px;
    }
      .video_text p{
    color: #07274B80;
    font-size: 12px;
  }
  .video_card p{
    color: #07274BCC;
   font-size: 12px;
  }
  .video_text h4{
    font-size: 14px;
  }
  }
</style>