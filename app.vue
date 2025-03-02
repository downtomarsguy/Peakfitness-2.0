<template>
  <div class="h-screen flex flex-col">
    <Navbar />

      <HeroSection />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    HeroSection
  },
};
</script>

<style>
@import "tailwindcss";
</style>
