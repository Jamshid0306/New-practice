<script setup>
import OrderBtn from '@/components/UI/OrderBtn.vue';
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/pagination';
import 'swiper/css/navigation';
import { Pagination, Navigation } from 'swiper/modules';

const modules = [Pagination, Navigation]

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
      <div class="swiper-blog">
      <swiper ref="{swiperRef}" :slidesPerView="2" :centeredSlides="true" :spaceBetween="30" :pagination="{type: 'fraction',}" :navigation="true" :modules="modules">
      <swiper-slide class="swiper__card32">
          <img class="swiper__card32-bg" src="@/assets/images/swiper__card-bg.svg" alt="">
      </swiper-slide>
      <swiper-slide class="swiper__card32">
        <img class="swiper__card32-bg" src="@/assets/images/swiper__card-bg2.svg" alt="">
      </swiper-slide>
      </swiper>
      </div>
  </section>
</template>