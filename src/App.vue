<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="bg-gray-200 text-center">
    <nav class="pt-28 mx-auto max-w-7xl items-center justify-between p-6 lg:px-8" aria-label="Global">
      <div class="logo pb-10">
        <RouterLink to="/" class="text-5xl font-semibold leading-6 text-black">MARCO MA</RouterLink>
      </div>

      <div class="pages">
        <RouterLink to="/about" class="text-xl font-semibold leading-6 text-gray-900">About</RouterLink>
        <RouterLink to="/contact" class="text-xl font-semibold leading-6 text-gray-900">Contact</RouterLink>
      </div>
    </nav>
  </header>

  <div class="content" >
    <RouterView/>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.pages a {
  display: inline-block;
  padding: 0 1rem;
}

.pages a+a {
  border-left: 1px solid var(--color-border);
}

.content {
  max-width: 1280px;
  margin: 48px auto;
  padding: 0 24px;
}
</style>
