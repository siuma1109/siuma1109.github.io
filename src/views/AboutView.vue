<script setup lang="ts">
import CV from '../assets/2024_MATSUNKIT_CV.pdf'
</script>

<template>
  <div class="grid grid-cols-5 gap-8">
    <div class="col-span-2 hidden md:block">
      <img src="/src/assets/about/left.png" class="w-100 rounded-full">
    </div>
    <div class="col-span-3">
      <h3 class="text-5xl font-semibold pb-4 text-gray-600">
        LET’S<br />
        INTRODUCE ABOUT<br />
        MYSELF
      </h3>
      <h4 class="text-lg font-semibold pb-8 text-gray-400">
        I have four years of experience as a full stack web developer. I specialize in creating web applications using
        PHP, HTML, CSS and JavaScript such as e-commerce systems. This e-commerce system has CRM and CMS features. I
        focused on developing high performance api and responsive pages for optimal user experience on different
        devices. <br /><br />
        As a full stack developer, I enjoy building high-quality code and providing good user interfaces and
        experiences. I'm always learning new technologies and tools to stay up to date with industry trends.
      </h4>
      <a type="button" :href="CV" target="_target"
        class="cursor-pointer text-gray-900 hover:text-white border border-gray-800 hover:bg-gray-900 focus:ring-4 focus:outline-none focus:ring-gray-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-gray-600 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-800">
        DOWNLOAD CV
      </a>
    </div>
  </div>

</template>

<style></style>
