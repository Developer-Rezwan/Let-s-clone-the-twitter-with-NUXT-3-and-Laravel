<template>
  <div :class="{ dark : isDark}">
    <div class="dark:bg-black">
      <h1 class="dark:text-dim-600">Hello</h1>
    </div>
  </div>
</template>

<script setup>
const isDark = ref(true);
</script>

<style scoped>
</style>