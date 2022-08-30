<template>
  <p>{{ count }}</p>
  <button @click="count++">Add</button>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)

</script>