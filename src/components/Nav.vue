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
      <div class="nav__items">
        <RouterLink class="nav__item"  to="/">Главная</RouterLink>
        <RouterLink class="nav__item" to="/">Почему именно мы?</RouterLink>
        <RouterLink class="nav__item" to="/">Контакты</RouterLink>
        <OrderBtn :text="'Заказать'" />
      </div>
    </div>
  </nav>
</template>


