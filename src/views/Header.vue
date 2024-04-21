<script setup>
import Nav from "@/components/Nav.vue";
import HeaderBtn from "@/components/UI/HeaderBtn.vue";

</script>


<template>
  <header class="header" id="scroll_main">
    <Nav />
    <div class="container">
        <div class="header__main">

      <h1 class="title">РАЗРАБОТКА САЙТОВ ДЛЯ ТВОЕГО БИЗНЕСА</h1>
      <p class="text">
        Мы - студия web-разработки, работаем уже более 3-х лет, готовы
        разработать для вас сайт в кротчайшие сроки.
      </p>
      <div class="header__btns">
        <HeaderBtn :text="'Подробнее'"/>
        <RouterLink class="header__btn1" to="/">Остались вопросы?</RouterLink>
      </div>
        </div>
    </div>
  </header>
</template>