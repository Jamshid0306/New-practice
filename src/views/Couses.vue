<script setup>
import CouseBtn from "@/components/icons/CouseBtn.vue";
</script>
<template>
  <section class="couse">
    <div class="container">
      <div class="couse__blocks">
        <div class="couse-btn">
          <CouseBtn />
          <div class="couse__btn-bg"></div>
        </div>
        <div class="couse__block">
          <h2 class="cs__title">Приемлимые цены</h2>
          <p class="cs__txt">
            Мы максимально оптимизируем наш труд, для того, чтобы цены были
            доступными
          </p>
        </div>
      </div>
      <div class="couse__cards">
        <div class="couse__block couse__block1">
          <h2 class="cs__title">В сроки сдаем работу!</h2>
          <p class="cs__txt">
            Расписываем каждый этап по срокам, и придерживаемся дедлайнов
          </p>
        </div>

        <div class="couse__block couse__block2">
          <h2 class="cs__title">Команда специалистов</h2>
          <p class="cs__txt">
            В нашей команде множество специалистов, и каждый из них хорошо знает
            свое дело
          </p>
        </div>

        <div class="couse__block couse__block3">
          <h2 class="cs__title">Консультация перед заказом</h2>
          <p class="cs__txt">
            Наши менеджеры в сети 24/7, и готовы помочь вам, а так же ответить
            на ваши вопросы
          </p>
        </div>
      </div>
    </div>
  </section>
</template>