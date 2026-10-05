<script setup lang="ts">
import vertical from './vertical.vue'
import horizontal from './horizontal.vue'
import { ref, onMounted, onUnmounted } from 'vue'

const is_vertical = ref(false)

const check_size = () => {
  is_vertical.value = window.innerWidth < window.innerHeight
}

onMounted(() => {
  check_size()
  window.addEventListener('resize', check_size)
})

onUnmounted(() => {
  window.removeEventListener('resize', check_size)
})
</script>

<template>
  <vertical v-if="is_vertical" />
  <horizontal v-else />
</template>
