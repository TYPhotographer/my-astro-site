<template>
  <p>{{ $counter }}</p>
  <button @click="counter.set($counter + 1)">Add</button>
</template>

<script setup lang="ts">
// import { ref } from 'vue'
import { counter } from '../store/index'
import { useStore } from '@nanostores/vue'

// const count = ref(0)
const $counter = useStore(counter)

</script>