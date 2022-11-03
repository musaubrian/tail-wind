<script setup>
import Form from './components/Form.vue';

</script>

<template>
  <div class="grid grid-cols-2 h-full w-full">
    <Form class="col-span-2 md:col-span-1"/>
    <img src="../src/assets/photoshoot.jpeg" class="hidden md:col-span-1 md:block h-full object-cover" alt="photoshoot session">
  </div>
</template>