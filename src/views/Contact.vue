<script setup>
import UsersIcon from "@/components/icons/UsersIcon.vue";
import BeIcon from "@/components/icons/BeIcon.vue";
import TelegramIcon from "@/components/icons/TelegramIcon.vue";
import VkIcon from "@/components/icons/VkIcon.vue";
import EmailIcon from "@/components/icons/EmailIcon.vue";
</script>
<template>
  <section class="contact" id="scroll_contact">
    <div class="container">
      <div class="contact__title">
        <img class="footer__logo" src="@/assets/images/contact_title.svg" alt="" />
      </div>
      <div class="contact__blogs">
        <a href="#" class="contact__blog">
          <UsersIcon class="contact__icon" />
        </a>
        <a href="#" class="contact__blog">
          <BeIcon class="contact__icon" />
        </a>
        <a href="#" class="contact__blog">
          <TelegramIcon class="contact__icon" />
        </a>
        <a href="#" class="contact__blog">
          <VkIcon class="contact__icon" />
        </a>
        <a href="#" class="contact__blog">
          <EmailIcon class="contact__icon" />
        </a>
      </div>
      <img class="footer__img" src="@/assets/images/footer-logo.svg" alt="" />
      <p class="footer__txt">Политика сайта и обработка персональных данных</p>
    </div>
  </section>
</template>


