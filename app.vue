<template>
  <div class="flex flex-col">
    <Navbar />
    
    <HeroSection />

    <ProgramSection />

    <NutritionSection />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
import ProgramSection from "./components/ProgramSection.vue";
import NutritionSection from "./components/NutritionSection.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    HeroSection,
    ProgramSection,
    NutritionSection,
  },
};
</script>

<style>
@import "tailwindcss";
</style>
