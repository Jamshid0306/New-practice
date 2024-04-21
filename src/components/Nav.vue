<script setup>
import OrderBtn from "@/components/UI/OrderBtn.vue";
</script>
<template>
  <nav class="nav">
    <div class="container">
      <RouterLink to="/" class="logo">
        <img src="@/assets/images/logo_1.svg" alt="" class="logo_1-img" />
        <img src="@/assets/images/logo_2.svg" alt="" class="logo_1-img" />
      </RouterLink>
      <ul class="nav__items">
        <li class="nav__item"><a href="#scroll_main">Главная</a></li>
        <li class="nav__item nav__item2"><a href="#scroll_why">Почему именно мы?</a></li>
        <li class="nav__item"><a href="#scroll_contact">Контакты</a></li>
        <OrderBtn :text="'Заказать'" />
      </ul>
    </div>
  </nav>
</template>


