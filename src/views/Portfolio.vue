<script setup>
import OrderBtn from '@/components/UI/OrderBtn.vue';
</script>


<template>
  <section class="portfolio" id="scroll_why">
    <div class="container">
      <div class="portfolio__text-blog">
        <h2 class="portfolio__title">Наше портфолио</h2>
        <p class="portfolio__text">
          В данном портфолио вы сможете увидеть кейсы наших работ на 2022 - 2023
          год
        </p>
        <OrderBtn class="nav__btn3" :text="'Компьютерные версии'"/>
      </div>
    </div>
  </section>
</template>