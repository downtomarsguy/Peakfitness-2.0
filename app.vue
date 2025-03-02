<template>
  <div class="h-screen flex flex-col">
    <Navbar />
    
    <div class="flex-1 flex justify-center items-center">
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar,
  },
};
</script>

<style>
@import "tailwindcss";
</style>
