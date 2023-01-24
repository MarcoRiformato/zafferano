<template>
<Header/>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-4 p-4">
  <div class="bg-white rounded-lg shadow-md">
    <img src='/images/secco.png' alt="Pack 1" class="w-full h-48 object-cover">
    <h2 class="text-lg font-medium my-2">Pack 1</h2>
    <p class="text-sm text-gray-600">A brief description of the first pack.</p>
  </div>
  <div class="bg-white rounded-lg shadow-md">
    <img src='/images/secco.png' alt="Pack 2" class="w-full h-48 object-cover">
    <h2 class="text-lg font-medium my-2">Pack 2</h2>
    <p class="text-sm text-gray-600">A brief description of the second pack.</p>
  </div>
  <div class="bg-white rounded-lg shadow-md">
    <img src='/images/secco.png' alt="Pack 3" class="w-full h-48 object-cover">
    <h2 class="text-lg font-medium my-2">Pack 3</h2>
    <p class="text-sm text-gray-600">A brief description of the third pack.</p>
  </div>
  <div class="bg-white rounded-lg shadow-md">
    <img src='/images/secco.png' alt="Pack 4" class="w-full h-48 object-cover">
    <h2 class="text-lg font-medium my-2">Pack 4</h2>
    <p class="text-sm text-gray-600">A brief description of the fourth pack.</p>
  </div>
  <div class="bg-white rounded-lg shadow-md">
    <img src='/images/secco.png' alt="Pack 5" class="w-full h-48 object-cover">
    <h2 class="text-lg font-medium my-2">Pack 5</h2>
    <p class="text-sm text-gray-600">A brief description of the fifth pack.</p>
  </div>
  <div class="bg-white rounded-lg shadow-md">
    <img src='/images/secco.png' alt="Pack 6" class="w-full h-48 object-cover">
    <h2 class="text-lg font-medium my-2">Pack 6</h2>
    <p class="text-sm text-gray-600">A brief description of the sixth pack.</p>
  </div>
</div>

<MyFooter/>
</template>
<script setup>
import MyFooter from '../Components/Custom/MyFooter.vue';
import Header from '../Components/Custom/Header.vue';

</script>