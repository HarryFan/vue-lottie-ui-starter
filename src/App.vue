<template>
  <div class="app text-center py-10">
    <h1 class="text-3xl font-bold mb-6 text-blue-600">Lottie Animation in Vue 3 + Tailwind</h1>
    <lottie-player
      src="https://assets10.lottiefiles.com/packages/lf20_tll0j4bb.json"
      background="transparent"
      speed="1"
      style="width: 300px; height: 300px"
      loop
      autoplay
    />
  </div>
</template>

<script setup>
// 無需額外 JS 控制
</script>

<style scoped>
/* 可選補充樣式 */
</style>