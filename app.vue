<template>
  <div class="flex flex-col">
    <Navbar />
    
    <HeroSection />

    <ProgramSection />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
import ProgramSection from "./components/ProgramSection.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    HeroSection,
    ProgramSection,
  },
};
</script>

<style>
@import "tailwindcss";
</style>
