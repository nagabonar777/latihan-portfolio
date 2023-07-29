
<template>
 <Navbar></Navbar>
 <br><br><br>
 <center>
<h1 class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-gray-900 md:text-5xl lg:text-6xl dark:text-white">Hi, this is my portfolio</h1>
<h1 class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-gray-900 md:text-5xl lg:text-6xl dark:text-white">Chandra A.H</h1>
<p class="mb-6 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400">I'm here to introduce myself.</p>
<a href="#" class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900">
    See more
    <svg class="w-3.5 h-3.5 ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
  </svg>
</a>
</center><br>
   <div class="left side" stroke-width="">
  <Body></Body><br>
  </div>
  <br>
  <Body3></Body3>
  <br><br>
  <Body2></Body2>
  
  <Footer></Footer>
</template>

<script setup>

import Navbar from './components/Navbar.vue'
import Body from './components/Body.vue'
import Body2 from './components/Body2.vue'
import Footer from './components/Footer.vue';
import Body3 from './components/Body3.vue'


</script>


<style scoped>

</style>
