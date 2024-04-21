<script setup>
import OrderBtn from '@/components/UI/OrderBtn.vue';
</script>
<template>
  <section class="application">
    <div class="container">
      <h3 class="app__title">Оставь заявку</h3>
      <div class="app__blog">
        <form class="app__inp">
          <p class="app__txt">Ваше ФИО</p>
          <input type="name" class="app__input" />
        </form>
        <form class="app__inp">
          <p class="app__txt">Ваш номер телефона</p>
          <input type="text" class="app__input" />
        </form>
        <form class="app__inp">
          <p class="app__txt">Бюджет на сайт</p>
          <input type="text" class="app__input" />
        </form>
        <form class="app__inp">
          <p class="app__txt">Ваш E-MAIL адрес</p>
          <input type="email" class="app__input" />
        </form>
        <form class="app__inp">
          <p class="app__txt">Ваш комментарий ( по желанию )</p>
          <input type="text" class="app__input" />
        </form>
          <OrderBtn class="nav__btn4" :text="'Отправить'"/>
      </div>
    </div>
  </section>
</template>


