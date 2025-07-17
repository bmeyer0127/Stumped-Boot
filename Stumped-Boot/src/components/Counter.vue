<script setup lang="ts">

import { ref } from 'vue'
const count = ref(0)

</script>

<template>
  <button @click="count++">Count++</button>
  <div class="count-container">
    <h2 class="count-header">Count:</h2>
    <h3>{{ count }}</h3>
  </div>
</template>