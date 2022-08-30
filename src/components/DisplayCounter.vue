<template>
  <p>from counter: {{ $counter }}</p>
</template>

<script setup lang="ts">
import { counter } from '../store/index'
import { useStore } from '@nanostores/vue'

const $counter = useStore(counter)

</script>