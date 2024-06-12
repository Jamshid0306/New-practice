<script setup>
import OrderBtn from "@/components/UI/OrderBtn.vue";

import { ref } from 'vue';


const burgermodal = ref(false)
</script>
<template>
  <nav class="nav">
    <div class="container">
      <RouterLink to="/" class="logo">
        <img src="@/assets/images/logo_1.svg" alt="" class="logo_1-img" />
        <img src="@/assets/images/logo_2.svg" alt="" class="logo_1-img" />
      </RouterLink>
      <ul class="nav__items">
        <li class="nav__item"><a class="nav__link" href="#scroll_main">Главная</a></li>
        <li class="nav__item nav__item2"><a class="nav__link" href="#scroll_why">Почему именно мы?</a></li>
        <li class="nav__item"><a class="nav__link" href="#scroll_contact">Контакты</a></li>
        <OrderBtn :text="'Заказать'" />
      </ul>
      <ul class="nav__items2" :class="{ 'active': burgermodal }">
        <li class="nav__item"><a class="nav__link" href="#scroll_main">Главная</a></li>
        <li class="nav__item nav__item2"><a class="nav__link" href="#scroll_why">Почему именно мы?</a></li>
        <li class="nav__item"><a class="nav__link" href="#scroll_contact">Контакты</a></li>
        <OrderBtn :text="'Заказать'" />
      </ul>
      <div class="nav__burger" :class="{ 'activeburger': burgermodal }">
            <div class="nav__burger-btn" :class="{ 'activeburger': burgermodal }" @click="burgermodal = !burgermodal">
                <span></span>
            </div>
        </div>
    </div>
  </nav>
</template>


