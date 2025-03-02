<template>
    <section class="py-12 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-extrabold text-center text-gray-800 mb-10">
                Use Tools & Calculators
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
import weightLossImg from "@/assets/weightloss.jpg";
import bodyFatImg from "@/assets/bodyfat2.jpg";
import bmiImg from "@/assets/bmi.jpg";
import caloriesCalculatorImg from "@/assets/burncalories.jpg";
import caloriesWorkoutsImg from "@/assets/caloriesworkout.jpg";
import nutritionImg from "@/assets/nutrition.jpg";

export default {
    name: "ToolSection",
    data() {
        return {
            programs: [
                {
                    title: "Weight Loss",
                    description: "Track your weight loss progress and set your goals.",
                    image: weightLossImg,
                },
                {
                    title: "Body Fat",
                    description: "Calculate and monitor your body fat percentage.",
                    image: bodyFatImg,
                },
                {
                    title: "BMI Calculator",
                    description: "Find out your Body Mass Index to assess your health.",
                    image: bmiImg,
                },
                {
                    title: "Calories Calculator",
                    description: "Estimate your daily calorie needs based on activity level.",
                    image: caloriesCalculatorImg,
                },
                {
                    title: "Calories Workouts",
                    description: "Calculate calories burned during different types of workouts.",
                    image: caloriesWorkoutsImg,
                },
                {
                    title: "Nutrition",
                    description: "Get personalized nutrition tips and track your diet.",
                    image: nutritionImg,
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
