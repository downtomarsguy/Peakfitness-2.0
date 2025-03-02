<template>
  <div class="flex flex-col">
    <Navbar />
    
    <HeroSection />

    <ProgramSection />

    <NutritionSection />

    <ToolsSection />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
import ProgramSection from "./components/ProgramSection.vue";
import NutritionSection from "./components/NutritionSection.vue";
import ToolsSection from "./components/ToolsSection.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    HeroSection,
    ProgramSection,
    NutritionSection,
    ToolsSection
  },
};
</script>

<style>
@import "tailwindcss";
</style>
