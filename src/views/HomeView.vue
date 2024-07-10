<script setup lang="ts">
import CV from '../assets/2024_MATSUNKIT_CV.pdf'
</script>

<template>
  <div class="grid grid-cols-5 gap-4">
    <div class="col-span-3">
      <h3 class="text-4xl font-semibold pb-4 text-gray-600">HELLO</h3>
      <h1 class="text-6xl font-bold pb-4 text-gray-600">I AM MARCO MA</h1>
      <h4 class="text-2xl font-bold pb-14 text-gray-400">SENIOR WEB DEVELOPER</h4>

      <a type="button" :href="CV" target="_target"
        class="cursor-pointer text-gray-900 hover:text-white border border-gray-800 hover:bg-gray-900 focus:ring-4 focus:outline-none focus:ring-gray-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-gray-600 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-800">
        GET CV
      </a>
    </div>
    <div class="col-span-2 hidden md:block">
      <img src="/src/assets/home/code-geek.png" class="w-100">
    </div>
  </div>

</template>

<style scoped></style>