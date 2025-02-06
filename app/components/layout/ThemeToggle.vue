<script setup>
const colorMode = useColorMode()

const toggleTheme = () => {
  colorMode.preference = colorMode.value === 'dark' ? 'light' : 'dark'
}
</script>

<template>
  <button
    class="px-4"
    @click="toggleTheme"
  >
    {{ colorMode.value === 'dark' ? '🌙' : '☀️' }}
  </button>
</template>
