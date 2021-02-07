<template>
  <button @click="increment">Increment Count</button>
  <h2>{{ count }}</h2>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)

function increment() {
  count.value += 1
}
</script>
