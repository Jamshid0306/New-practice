<script setup>

import arrow from "@/components/icons/RightArrow.vue"

const props = defineProps({
  text: String,
})

</script>

<template>
  <button class="nav__btn nav__btn2 nav__btn3">{{text}}</button>

</template>

