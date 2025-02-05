<script setup>
const colorMode = useColorMode()

const toggleTheme = () => {
  colorMode.preference = colorMode.value === 'dark' ? 'light' : 'dark'
}
</script>

<template>
  <button @click="toggleTheme">
    {{ colorMode.value === 'dark' ? '🌙 Dark Mode' : '☀️ Light Mode' }}
  </button>
</template>
