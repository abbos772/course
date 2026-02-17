<script setup>
</script>

<template>
  <main class="container">
    <h1>Реестр выпускников</h1>
    
    <div class="list">
      <div class="item">
        <h3>Исмоилов Ахмаджон</h3>
        <p class="job">Саноат қурилмалари ва машиналари операторлари ва йиғувчилари</p>
        <p class="center">Sarabiy Profession Study Center</p>
      </div>

      <div class="item">
        <h3>Иброхимов Акбархон</h3>
        <p class="job">Қишлоқ хўжалигининг малакали ходимлари балиқчилар, балиқшунослар</p>
        <p class="center">Beruniy Professions Jobs</p>
      </div>

      <div class="item">
        <h3>Шарапова Олеся</h3>
        <p class="job">Савдо корхоналари ва хизмат кўрсатиш соҳаси ходимлари</p>
        <p class="center">Azizxon As Tekstil</p>
      </div>

      <div class="item no_line">
        <h3>Акопов Тимур</h3>
        <p class="job">Ўқитилаётган касблар</p>
        <p class="center">Mohiyora Kumush</p>
      </div>
    </div>

    <button class="btn">Посмотреть всех</button>
   
   

  </main>
</template>

<style scoped>

  .footer_mid{
    margin-top: 80px;
  }
  main {
    text-align: center;
    margin-top: 60px;
    margin-bottom: 60px;
    font-family: Arial, sans-serif;
  }

  h1 {
    color: #07274B;
    font-size: 29px;
    font-weight: 800;
    margin-bottom: 40px;
  }

  .list {
    display: flex;
    justify-content: space-between;
    margin-bottom: 40px;
  }

  .item {
    width: 25%;
    text-align: left;
    padding: 0 15px;
    border-right: 1px solid #ddd;
  }

  .no_line {
    border-right: none;
  }

  .item h3 {
    font-size: 18px;
    color: #07274B;
    margin-bottom: 15px;
    font-weight: bold;
  }

  .job {
    font-size: 15px;
    color: #07274B;
    margin-bottom: 15px;
    line-height: 1.2;
  }

  .center {
    font-size: 14px;
    color: #555;
  }

  .btn {
    background: #0046B8;
    color: white;
    border: none;
    padding: 15px 40px;
    font-size: 16px;
    border-radius: 20px;
    cursor: pointer;
  }

  @media (max-width: 900px) {
    .list {
      flex-direction: column;
      gap: 30px;
    }
    .item {
      width: 100%;
      border-right: none;
      border-bottom: 1px solid #ddd;
      padding-bottom: 20px;
    }
    .no_line {
      border-bottom: none;
    }
  }
</style>