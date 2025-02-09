<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
  
  </div>

  <p>
    Kind Bites is a food rescue platform that will connect businesses with a surplus of food to nonprofit organizations or individuals in need
  </p>
  <p>
    Comming soon
  </p>
  <p class="read-the-docs">Project is under development</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
