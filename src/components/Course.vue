<script setup>
</script>

<template>
  <main class="container" id="course">
    <div class="course">
      <div class="course_text">
        <h1>Популярные курсы</h1>
        <div class="course_pagination">
          <button class="pagination_btn">
            <img src="../assets/images/btnone.png" alt="">
          </button>
          <button class="pagination_btn btn_two">
            <img src="../assets/images/btntwo.png" alt="">
          </button>
        </div>
      </div>
      
      <div class="course_flex">
        <img src="../assets/images/Vector.png" width="800" alt="" class="bg_vector">
        
        <div class="course_cards">
          <div class="course_card">
            <div class="card_icon">
               <img src="../assets/images/web.png"> 
            </div>
            <div class="line"></div>
            <h3>WEB программист</h3>
            <p>Количество студентов: <span>10</span></p>
          </div>

          <div class="course_card">
            <div class="card_icon">
               <img src="../assets/images/bux.png" alt="">
            </div>
            <div class="line"></div>
            <h3>Бухгалтер</h3>
            <p>Количество студентов: <span>12</span></p>
          </div>

          <div class="course_card">
            <div class="card_icon">
               <img src="../assets/images/admin.png" alt="">
            </div>
            <div class="line"></div>
            <h3>Администратор отеля</h3>
            <p>Количество студентов: <span>8</span></p>
          </div>

          <div class="course_card">
            <div class="card_icon">
               <img src="../assets/images/land.png" alt="">
            </div>
            <div class="line"></div>
            <h3>Ландшафтный Дизайнер</h3>
            <p>Количество студентов: <span>10</span></p>
          </div>

          <div class="course_card">
            <div class="card_icon">
               <img src="../assets/images/florist.png" alt="">
            </div>
            <div class="line"></div>
            <h3>Флорист</h3>
            <p>Количество студентов: <span>10</span></p>
          </div>

          <div class="course_card">
            <div class="card_icon">
               <img src="../assets/images/sew.png" alt="">
            </div>
            <div class="line"></div>
            <h3>Швея</h3>
            <p>Количество студентов: <span>10</span></p>
          </div>

        </div>
      </div>
      <div class="course_text sectiontwo">
        <h1>Лучшие учебные центры</h1>
        <div class="course_pagination">
          <button class="pagination_btn">
            <img src="../assets/images/btnone.png" alt="">
          </button>
          <button class="pagination_btn btn_two">
            <img src="../assets/images/btntwo.png" alt="">
          </button>
        </div>
      </div>
      <div class="course_boxes">
  
    <div class="course_box">
        <div class="box_content">
        <h3 class="center_name">BERUNIY <br> PROFESSIONS JOBS</h3>
        <p class="region">Қорақалпоғистон Республикаси</p>
        
        <div class="student_badge">
            Обучается студентов: <span>1500</span>
        </div>
        
        <button class="more_btn">Подробнее</button>
        </div>
    </div>

    <div class="course_box">
        <div class="box_content">
        <h3 class="center_name">SARABIY PROFESSION <br> STUDY CENTER</h3>
        <p class="region">Қорақалпоғистон Республикаси</p>
        
        <div class="student_badge">
            Обучается студентов: <span>1200</span>
        </div>
        
        <button class="more_btn">Подробнее</button>
        </div>
    </div>

    <div class="course_box">
        <div class="box_content">
        <h3 class="center_name">ELEGANT <br> GULCHIROY</h3>
        <p class="region">Фарғона вилояти</p>
        
        <div class="student_badge">
            Обучается студентов: <span>800</span>
        </div>
        
        <button class="more_btn">Подробнее</button>
        </div>
    </div>

    <div class="course_box">
        <div class="box_content">
        <h3 class="center_name">AZIZXON AS <br> TEKSTIL</h3>
        <p class="region">Фарғона вилояти</p>
        
        <div class="student_badge">
            Обучается студентов: <span>1000</span>
        </div>
        
        <button class="more_btn">Подробнее</button>
        </div>
    </div>

    </div>
    <div class="btn_container">
    <button class="btn_all">Посмотреть все</button>
    </div>
 </div>
  </main>
</template>

<style scoped>
  .container {
    margin-top: 50px;
    margin-bottom: 50px;
    font-family: Arial, sans-serif;
  }
   .course_boxes{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 23px;
  }
  .btn_container{
    text-align: center;
  }
  .btn_all{
    margin-top: 50px;
    font-family: Montserrat;
    font-weight: 500;
    font-style: Medium;
    font-size: 18px;
    line-height: 100%;
    letter-spacing: -2%;
    color: #F4F4F4;
    background: #0046B8;
    height: 50px;
    width: 250px;
    border-radius: 20px;
    border: none;
    cursor: pointer;
  }
    .course_box {
    width: 260px;
    height: 250px;
    border-radius: 20px;
    border: 1px solid #E7F0FF;

    background: linear-gradient(314.93deg, #E5F0FF -16.82%, rgba(255, 255, 255, 0) 99.97%);
    padding: 10px;
    display: flex;
    flex-direction: column;
    box-sizing: border-box; 
    box-shadow: 0px 8px 16px 0px rgba(15, 86, 179, 0.14);
    }
    .box_content {
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    height: 100%;
    padding: 10px;
    }

    .center_name {
    font-size: 16px;
    font-weight: 800;
    color: #07274B;
    margin-top: 10px;
    text-transform: uppercase;
    }

    .region {
    font-size: 12px;
    color: #07274B;
    margin-top: 5px;
    }

    .student_badge {
    background: white;
    padding: 8px 15px;
    border-radius: 10px;
    border: 1px solid #E7F0FF;
    font-size: 12px;
    color: #07274B;
    margin: 15px 0;
    }

    .student_badge span {
    font-weight: 800;
    color: #0046B8;
    }

    .more_btn {
    background: #0046B8;
    color: white;
    border: none;
    padding: 10px 25px;
    border-radius: 8px;
    cursor: pointer;
    font-weight: 600;
    width: fit-content;
    }

    .more_btn:hover {
    background: #00358a;
    }
  .bg_vector {
    z-index: -10;
    position: absolute;
    margin-top: -40px;
  }
  
  .course_cards {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    gap: 30px;
    z-index: 10;
    margin-top: 20px;
  }
  
  .course_card {
    max-width: 350px;
    width: 100%;
    height: 250px;
    border-radius: 20px;
    background: #FFFFFF;
    box-shadow: 0px 8px 16px 0px #0F56B324; 
    padding: 30px; 
    box-sizing: border-box; 
  }

  .card_icon {
    height: 80px;
    display: flex;
    align-items: center;
  }
  
  .card_icon img {
    max-height: 100%;
    width: 60px;
  }

  .line {
    width: 40px;
    height: 3px;
    background-color: #0046B8; 
    margin-top: 20px;
    margin-bottom: 20px;
  }

  .course_card h3 {
    font-size: 20px;
    font-weight: bold;
    color: #000;
    margin-bottom: 15px;
  }

  .course_card p {
    color: #333;
    font-size: 14px;
  }

  .course_card p span {
    font-size: 18px;
    color: #0046B8; 
    font-weight: bold;
    margin-left: 5px;
  }

  
  .course_pagination {
    justify-content: flex-end;
    display: flex;
    gap: 10px;
    position: relative;
    bottom: 40px;
    padding-right: 50px;
  }
  
  .course_text {
    text-align: center;
    color: #07274B;
    font-family: 'Montserrat', sans-serif;
  }
  .sectiontwo{
    margin-top: 80px;
  }
  .pagination_btn {
    width: 45px;
    height: 45px;
    border-radius: 8px;
    background: #E7F0FF;
    cursor: pointer;
    border: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .btn_two {
    background: #0046B8;
  }
  @media (max-width:768px){
    .course_boxes{
        flex-wrap: wrap;
        padding: 15px;
    }
    .course_card{
        max-width: 250px;
        height: 250px;
    }
    .course_pagination{
       position: relative;
       bottom: 0;
       right: 0;
       padding-right: 0;
    }
    .course_text{
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 50px;
        padding: 20px;
    }
    .course_text h1{
     font-size:  17px;
    }
    .bg_vector{
        padding: 10px;
        width: 100%;
    
    }
  }
</style>