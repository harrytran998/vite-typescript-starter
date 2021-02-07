<template>
  <div style="text-align: center">
    <h1>Hello {{ name }} to Vue Vite</h1>
    <h6>Look good???</h6>
    <Counter />
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const name = ref('Your name')
</script>
