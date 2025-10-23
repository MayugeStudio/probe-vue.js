<script setup>
  import { ref } from 'vue'

  const text = ref(0)

</script>

<template>
  <input v-model="text" placeholder="Type here"></input>
  <p>{{ text }}</p>
</template>

