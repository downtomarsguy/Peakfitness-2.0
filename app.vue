<template>
  <div class="flex flex-col">
    <Navbar />
    
    <HeroSection />

    <ProgramSection />

    <NutritionSection />

    <ToolsSection />

    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
import ProgramSection from "./components/ProgramSection.vue";
import NutritionSection from "./components/NutritionSection.vue";
import ToolsSection from "./components/ToolsSection.vue";
import Footer from "./components/Footer.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    HeroSection,
    ProgramSection,
    NutritionSection,
    ToolsSection,
    Footer,
  },
};
</script>

<style>
@import "tailwindcss";
</style>
