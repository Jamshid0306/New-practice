<script setup>

import arrow from "@/components/icons/RightArrow.vue"

const props = defineProps({
  text: String,
})

</script>

<template>
  <button class="nav__btn2">{{text}}</button>

</template>

