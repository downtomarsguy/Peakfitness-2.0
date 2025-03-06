<template>
    <nav class="sticky top-0 bg-black p-4 z-10">
        <div class="flex items-center justify-between">
            <div class="text-white text-2xl font-semibold">
                FlexNation
            </div>
            <div class="flex space-x-6">
                <button class="text-white hover:text-gray-400 flex items-center space-x-2">
                    <Icon name="material-symbols:energy-program-saving" />
                    <span>Home</span>
                </button>
                <button class="text-white hover:text-gray-400 flex items-center space-x-2">
                    <Icon name="ic:round-calculate" />
                    <span>Program</span>
                </button>
                <button class="text-white hover:text-gray-400 flex items-center space-x-2">
                    <Icon name="ic:sharp-fastfood" />
                    <span>Nutrition</span>
                </button>
                <button class="text-white hover:text-gray-400 flex items-center space-x-2">
                    <Icon name="ic:round-calculate" />
                    <span>Tools</span>
                </button>
                <button class="text-white hover:text-gray-400 flex items-center space-x-2">
                    <Icon name="material-symbols:info-rounded" />
                    <span>About</span>
                </button>
                <button class="text-white hover:text-gray-400 flex items-center space-x-2">
                    <Icon name="material-symbols:logout-rounded" />
                    <span>Login/Register</span>
                </button>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'Navbar',
};
</script>