<template>
    <footer class="bg-black text-white py-12 mt-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-2"> <!-- Decreased gap to gap-2 -->
                <!-- Home Section -->
                <div>
                    <h3 class="text-lg font-semibold mb-4">Home</h3>
                    <ul>
                        <li><a href="/" class="text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="/" class="text-gray-400 hover:text-white">Blog</a></li>
                        <li><a href="/" class="text-gray-400 hover:text-white">FAQ</a></li>
                    </ul>
                </div>

                <!-- Tools Section -->
                <div>
                    <h3 class="text-lg font-semibold mb-4">Tools</h3>
                    <ul>
                        <li><a href="/weight-loss" class="text-gray-400 hover:text-white">Weight Loss</a></li>
                        <li><a href="/body-fat" class="text-gray-400 hover:text-white">Body Fat</a></li>
                        <li><a href="/bmi-calculator" class="text-gray-400 hover:text-white">BMI Calculator</a></li>
                        <li><a href="/calories-calculator" class="text-gray-400 hover:text-white">Calories Calculator</a></li>
                        <li><a href="/calories-workouts" class="text-gray-400 hover:text-white">Calories Workouts</a></li>
                        <li><a href="/nutrition" class="text-gray-400 hover:text-white">Nutrition</a></li>
                    </ul>
                </div>

                <!-- Contact Us Section -->
                <div>
                    <h3 class="text-lg font-semibold mb-4">Contact Us</h3>
                    <ul>
                        <li><a href="/contact" class="text-gray-400 hover:text-white">Contact Form</a></li>
                        <li><a href="/support" class="text-gray-400 hover:text-white">Support</a></li>
                        <li><a href="mailto:support@example.com" class="text-gray-400 hover:text-white">Email Us</a></li>
                    </ul>
                </div>
            </div>

            <div class="mt-12 text-center">
                <p class="text-gray-400">© 2025 Your Company Name. All rights reserved.</p>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "ToolSection",
};
</script>

<style scoped>
footer {
    background-color: #000;
    color: #fff;
}

footer ul {
    list-style-type: none;
    padding: 0;
}

footer ul li {
    margin-bottom: 8px;
}

footer ul li a {
    text-decoration: none;
    color: #9ca3af;
    transition: color 0.3s ease;
}

footer ul li a:hover {
    color: white;
}
</style>
