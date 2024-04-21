<script setup>

import arrow from "@/components/icons/RightArrow.vue"

const props = defineProps({
  text: String,
})

</script>

<template>
  <button class="nav__btn2 nav__btn5">{{text}} <arrow :size="32"/></button>
  
</template>
