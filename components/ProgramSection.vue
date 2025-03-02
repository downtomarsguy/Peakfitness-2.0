<template>
    <section class="py-12 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-extrabold text-center text-gray-800 mb-10">
                Choose Your Program
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
import bodybuildingImg from "@/assets/bodybuilding.jpg";
import bodyRecompositionImg from "@/assets/bodyrecomposition.jpg";
import workoutBeginnersImg from "@/assets/workoutbeginners.jpg";
import staminaTrainingImg from "@/assets/staminatraining.jpg";
import strengthBuildingImg from "@/assets/strengthbuilding.jpg";

export default {
    name: "ProgramSection",
    data() {
        return {
            programs: [
                {
                    title: "Bodybuilding",
                    description:
                        "Build muscle and strength with structured weight training programs.",
                    image: bodybuildingImg,
                },
                {
                    title: "Body Recomposition",
                    description: "Lose fat while gaining muscle for a more defined physique.",
                    image: bodyRecompositionImg,
                },
                {
                    title: "Workout for Beginners",
                    description: "Perfect for those just starting their fitness journey.",
                    image: workoutBeginnersImg,
                },
                {
                    title: "Stamina Training",
                    description: "Improve your cardiovascular endurance and stamina.",
                    image: staminaTrainingImg,
                },
                {
                    title: "Strength Building",
                    description:
                        "Increase your raw strength with targeted training routines.",
                    image: strengthBuildingImg,
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