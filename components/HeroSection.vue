<template>
    <section class="relative h-screen flex items-center justify-between p-8 bg-black overflow-hidden">
        <div class="max-w-lg space-y-6">
            <h1 class="text-4xl font-extrabold text-white">
                Build Perfection For A Good And Healthy Life
            </h1>
            <button class="px-6 py-3 bg-red-500 text-white font-semibold rounded-lg hover:bg-red-600">
                Get Started
            </button>
        </div>

        <div class="absolute bottom-0 right-0 w-1/3 h-full">
            <img src="@/assets/main4.jpg" alt="Hero Image" class="w-full h-full object-cover rounded-lg" />
        </div>
    </section>
</template>

<script>
export default {
    name: 'HeroSection',
};
</script>

<style>
@import "tailwindcss";
</style>