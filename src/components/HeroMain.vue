<script setup>
</script>

<template>
    <main class="Hero_Bottom">
        <div class="container">
            <div class="tell_flex">
              <div class="tell_me">
                <div class="tell_text">
                 <h4>Отдельная <br> возможность   <hr> </h4>
                
                 <div class="flex_btn">
                  <button class="btn_check"><img src="../assets/images/arrow.png" alt=""></button>
                  <p>Подать заявку для <br> Юридических лиц в <br> Реестр учебных центров</p>
                 </div>
                </div>
                <button class="btn_course">Подобрать курс</button>
              </div>
              <div class="flex_title">
                <span><h4>200+</h4>Курсов</span>
                 <span><h4>15000+</h4>Студентов</span>
                  <span><h4>170+</h4>Учебных центров</span>
              </div>
              
            </div>
            <div class="btns">
            <button>Подать заявку <div class="helper"><img src="../assets/images/arrow2.png" alt=""></div> </button>
            <button> <div class="helper2"><img src="../assets/images/memo.png" alt="" width="20"></div> Проверить <br> статус заявки</button>
            <button> <div class="helper2"><img src="../assets/images/dip.png" width="20" alt=""></div> Проверить подлинность <br> сертификата</button>
            </div>
        </div>
    </main>
</template>

<style scoped>
  .Hero_Bottom{
    margin-top: 50px;
  }
  hr{
    width: 100px;
    border: 1px solid #0046B8;
  }
  .btns{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 50px;
    margin-top: 50px;
    flex-wrap: wrap;
  }
  .btns button{
    width: 330px;
    height: 75px;
    
    border-radius: 100px;
    border-width: 2px;
    border: 2px solid #0046B8;
    background: 0;
    cursor: pointer;
    font-family: Montserrat;
    font-weight: 500;
    font-size: 16px;
    line-height: 100%;
    letter-spacing: -2%;
    transition:0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
  }
  .helper{
    background: #F4F4F490;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
    border-radius: 50px;
    position: relative;
    left: 50px;
  }
  .helper2{
     display: flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
    border-radius: 50px;
    background: #E7F0FF;

  }
  .btns button:hover{
    background: #0046B8;
    color: white;
  }
  .flex_btn{
    display: flex;
    align-items: center;
    gap: 15px;
  }
  .flex_title{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 55px;
  }
  span{
    font-family: Montserrat;
    font-weight: 600;
    font-style: SemiBold;
    font-size: 16px;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: 0%;
   color: #07274BB2;
  }
  span h4{
    font-family: Montserrat;
    font-weight: 500;
    font-style: Medium;
    font-size: 30px;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: 0%;
    font-variant-numeric-figure: lining-nums;
    font-variant-numeric-spacing: tabular-nums;
    color: #0046B8;
  }

  .flex_btn p{
    color: #272727B2;
    font-weight: 500;
    font-size: 16px;
    line-height: 100%;
    
  }
  .btn_course{
    width: 240px;
    height: 48px; 
    border-radius: 20px;
    border: 0;
    cursor: pointer;
    background: #0046B8;
    font-weight: 500;
    font-style: Medium;
    font-size: 20px;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: -2%;
    color: #F4F4F4;
    position: relative;
    top: 115px;
  }
  .tell_text{
    display: flex;
    flex-direction: column;
    gap: 15px;
    position: relative;
    top: 75px;
    
  }
  .tell_text h4{
    font-family: Montserrat;
    font-weight: 800;
    font-style: ExtraBold;
    font-size: 18px;
    leading-trim: NONE;
    line-height: 100%;
    letter-spacing: 0%;

  }

  .tell_flex{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
    
  }
  .btn_check{
    width: 60px;
    height: 60px;
    border-radius: 25px;
    background: #0046B8;
    cursor: pointer;
    border: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .tell_me{
    background-image: url(../assets/images/Union.png);
    width: 100%;
    height: 50vh;
    background-repeat: no-repeat;
    background-size:contain;
    background-position: center;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
  }
  @media(max-width:768px){
    .btns{
      align-items: center;
      justify-content: center;
      gap: 20px;
      padding: 15px;
      margin-top: 10px;
    }
    .helper{
      left: 5px;
    }
    .btns button{
      padding: 3px;
      height: auto;
      font-size: 12px;
    }
    .btn_course{
      margin-top: 50px;
    }
    .flex_title{
      display: flex;
      align-items: center;
      flex-direction: row;
      flex-wrap: wrap;
      margin-top: 70px;
      gap: 20px;
      padding: 25px;
    }
    .flex_btn p{
      font-size: 13px;
    }
    .flex_title h4{
      font-size: 20px;
    }
    .tell_text{
      color: white;
      top: 110px;
    }
    .tell_flex{
      flex-wrap: wrap;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .tell_me{
        padding: 20px;
        background-size: cover; 
        background-position: center;
        width: 90%; 
        min-height: 300px;
        border-radius: 30px;
        background-color: #f0f4ff; 
        display: flex;
        align-items: center;
        box-sizing: border-box;
    }
  }
</style>