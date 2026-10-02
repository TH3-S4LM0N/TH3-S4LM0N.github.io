<script setup lang="ts">
import main_page from './main_page.vue'
import small_page from './small_page.vue'
import { ref, onMounted, onUnmounted } from 'vue'

const too_small = ref(false)

const check_size = () => {
  too_small.value = window.matchMedia('(max-width: 1715px)').matches
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
  <main_page v-if="!too_small" />
  <small_page v-else />
</template>
