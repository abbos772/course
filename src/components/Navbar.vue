<script setup>
import { ref } from 'vue'
const open = ref(false)
const toggle = () => (open.value = !open.value)
const close = () => (open.value = false)
</script>

<template>
  <header class="navbar">
    <div class="container">
      <div class="logo">
        <img src="../assets/images/Group 139.jpg" alt="">
      </div>
      <div class="nav_tool">
      <nav class="links">
        <a href="#">Главная</a>
        <a href="#course">Популярные курсы</a>
        <a href="#course">учебные центры</a>
        <a href="#">видеокурсы</a>
        <a href="#faq">FAQ</a>
      </nav>
      
      
        <div class="login">
          <button class="eye">
            <img src="../assets/images/Subtract.png" width="40" alt="">
          </button>
          <button class="button_lang"><span>Uz/Ru</span></button>
          <button class="logout">Войти</button>
        </div>

        <button class="burger" @click="toggle" :aria-expanded="open ? 'true' : 'false'" aria-label="menu">
          <span class="bar"></span>
          <span class="bar"></span>
          <span class="bar"></span>
        </button>
      </div>
    </div>

    <div v-if="open" class="mobile-menu">
      <a href="#" @click.prevent="close">Главная</a>
      <a href="#" @click.prevent="close">Популярные курсы</a>
      <a href="#" @click.prevent="close">учебные центры</a>
      <a href="#" @click.prevent="close">видеокурсы</a>
      <a href="#" @click.prevent="close">FAQ</a>
      <div class="mobile-actions">
        <button class="button_lang">Uz/Ru</button>
        <button class="logout">Войти</button>
      </div>
    </div>
  </header>
</template>

<style scoped>
  .navbar {
    width: 100%;
    padding: 16px 0;
    background: #fff;
  }

  .container {  
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .logo img {
    width: 50px;
    height: 70px;
  }

  .links {
    display: flex;
    gap: 30px;
  }

  .links a {
    position: relative;
    text-decoration: none;
    color: #07274B;
    font-weight: 500;
    font-size: 20px;
    padding-bottom: 6px;
    transition: 0.3s ease;
  }

  .links a:hover {
    color: #0046B8;
    font-weight: 700;
    font-size: 22px;
  }

  .links a::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: -5px;
    width: 0;
    height: 3px;
    background: linear-gradient(
      90.07deg,
      #FFA600 -1.12%,
      rgba(255,166,0,0) 128%
    );
    transition: width 0.3s ease;
  }

  .links a:hover::after {
    width: 100%;
  }

  .nav_tool {
    display: flex;
    align-items: self-start;
    gap: 35px;
  }

  .login {
    display: flex;
    gap: 12px;
    align-items: center;
    position: relative;
    bottom: 12px;
  }

  .button_lang {
    width: 82px;
    height: 50px;
    border-radius: 12px;
    border: 1px solid #0046B8;
    cursor: pointer;
    background: transparent;
  }

  .button_lang span {
    color: #0046B8;
    font-weight: 500;
    font-size: 20px;
  }

  .logout {
    width: 92px;
    height: 50px;
    border-radius: 12px;
    background: #0046B8;
    border: 0;
    color: #F4F4F4;
    font-size: 20px;
    font-weight: 500;
    cursor: pointer;
  }

  .eye {
    cursor: pointer;
    border: 0;
    background: transparent;
  }

  .burger {
    display: none;
    border: 0;
    background: transparent;
    padding: 8px;
    cursor: pointer;
  }

  .bar {
    display: block;
    width: 22px;
    height: 2px;
    margin: 4px 0;
    background: #07274B;
    border-radius: 2px;
  }

  .mobile-menu {
    padding: 12px 16px 20px;
    background: #fff;
    border-top: 1px solid rgba(0,0,0,0.04);
  }

  .mobile-menu a {
    display: block;
    padding: 12px 0;
    color: #07274B;
    text-decoration: none;
    font-size: 18px;
    border-bottom: 1px solid rgba(0,0,0,0.03);
  }

  .mobile-actions {
    display: flex;
    gap: 12px;
    margin-top: 12px;
  }

  @media (max-width: 900px) {
    .links {
      display: none;
    }

    .login {
      display: none;
    }

    .burger {
      display: block;
    }

    .mobile-menu {
      display: block;
    }
  }

  @media (max-width: 420px) {
    .button_lang,
    .logout {
      height: 44px;
      padding: 0 12px;
    }

    .logo img {
      width: 44px;
      height: 60px;
    }
  }
</style>

