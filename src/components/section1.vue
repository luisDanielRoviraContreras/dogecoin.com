<template>
  <section class="section-1">
    <img src="/doge.png" alt="">
  </section>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>
