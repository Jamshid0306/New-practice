<script setup>
import HeaderBtn from "@/components/UI/HeaderBtn.vue";
</script>

<template>
  <section class="tarifes">
    <div class="container">
      <h2 class="tarifes__title">Тарифы</h2>
      <div class="tarif__cards">
        <div class="t__card">
          <h3 class="t__card-title">Сайт “Визитка”</h3>
          <p class="t__card-p">
            Сайт-визитка - компактный веб-ресурс – отличный старт бизнеса в
            интернете. Сайт-визитка содержит несколько страниц, в том числе –
            информацию о компании, её товарах и услугах, прейскурант цен,
            контакты и координаты для связи.
          </p>
          <div class="t__card-bot">
            <div class="t__card-bot-txt">
              <h5 class="t__card-price">От N</h5>
              <p class="t__card-txt">От 5 дней</p>
            </div>
            <HeaderBtn :text="'Подробнее'" :size="32" />
          </div>
        </div>
        <div class="t__card">
          <h3 class="t__card-title">Сайт “Каталог”</h3>
          <p class="t__card-p">
            Сайт-каталог – это полноценный веб-ресурс, в котором потребители
            могут ознакомиться с товарами или услугами компании. Являясь удобным
            инструментом продаж, сайт-каталог может повысить доходность бизнеса
            и упростить задачу по предоставлению ассортимента целевой аудитории.
          </p>
          <div class="t__card-bot">
            <div class="t__card-bot-txt">
              <h5 class="t__card-price">От N sum</h5>
              <p class="t__card-txt">От 15 дней</p>
            </div>
            <HeaderBtn :text="'Подробнее'" :size="32" />
          </div>
        </div>
        <div class="t__card">
          <h3 class="t__card-title">Сайт “Визитка”</h3>
          <p class="t__card-p">
            Сайт-визитка - компактный веб-ресурс – отличный старт бизнеса в
            интернете. Сайт-визитка содержит несколько страниц, в том числе –
            информацию о компании, её товарах и услугах, прейскурант цен,
            контакты и координаты для связи.
          </p>
          <div class="t__card-bot">
            <div class="t__card-bot-txt">
              <h5 class="t__card-price">От N sum От 5 дней</h5>
              <p class="t__card-txt"></p>
            </div>
            <HeaderBtn :text="'Подробнее'" :size="32" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>