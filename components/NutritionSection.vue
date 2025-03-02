<template>
    <section class="py-12 bg-black">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-extrabold text-center text-white mb-10">
                Search Nutrition Plans
            </h2>

            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">
                <div v-for="(program, index) in programs" :key="index"
                    class="bg-white rounded-lg overflow-hidden shadow-lg flex flex-col">
                    <img :src="program.image" class="w-full h-72 object-cover" />
                    <div class="p-6 flex flex-col flex-1">
                        <h3 class="text-2xl font-semibold text-gray-800">{{ program.title }}</h3>
                        <p class="text-gray-600 mt-2 mb-5">{{ program.description }}</p>
                        <button
                            class="mt-auto px-6 py-2 bg-red-500 text-white font-semibold rounded-lg hover:bg-red-600">
                            Learn More
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import bodybuildingDietImg from "@/assets/bodybuildingdiet.jpg";
import fatLossImg from "@/assets/bodyfat.jpg";
import massImg from "@/assets/mass.jpg";
import staminaImg from "@/assets/staminatraining2.jpg";

export default {
    name: "ProgramSection",
    data() {
        return {
            programs: [
                {
                    title: "Bodybuilding Diet",
                    description: "Fuel your muscle-building journey with high-protein, calorie-dense meals designed to support muscle growth and recovery.",
                    image: bodybuildingDietImg,
                },
                {
                    title: "Fat Loss",
                    description: "Optimize your metabolism with a balanced, calorie-controlled diet designed to shed fat while preserving lean muscle.",
                    image: fatLossImg,
                },
                {
                    title: "Mass",
                    description: "Increase your calorie intake with a high-energy diet designed to help you put on mass and build strength.",
                    image: massImg,
                },
                {
                    title: "Stamina",
                    description: "Improve endurance and energy levels with a nutrition plan focused on sustaining long-term physical performance.",
                    image: staminaImg,
                },
            ],
        };
    },
};
</script>

<style scoped>
.container {
    max-width: 1200px;
}
</style>