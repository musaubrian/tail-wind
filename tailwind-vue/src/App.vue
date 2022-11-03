<script setup>
import MainContent from './components/mainContent.vue';
import SideBar from './components/sideBar.vue';

</script>

<template>
  <div class="bg-gray-200">
    <main class="grid grid-cols-5 gap-5 pt-4 h-full px-5">
      <SideBar class="col-span-2"/>
      <MainContent class="col-span-3"/>
  </main>
  </div>
  
</template>