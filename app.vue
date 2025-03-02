<template>
  <div class="h-screen flex flex-col">
    <nav class="bg-black p-4">
      <div class="flex items-center justify-between">
        <div class="text-white text-2xl font-semibold">
          FlexNation
        </div>
        <div class="flex space-x-6">
          <button class="text-white hover:text-gray-400 flex items-center space-x-2">
            <Icon name="material-symbols:energy-program-saving" style="" />
            <span>Home</span>
          </button>
          <button class="text-white hover:text-gray-400 flex items-center space-x-2">
            <Icon name="ic:round-calculate" style="" />
            <span>Program</span>
          </button>
          <button class="text-white hover:text-gray-400 flex items-center space-x-2">
            <Icon name="ic:sharp-fastfood" style="" />
            <span>Nutrition</span>
          </button>
          <button class="text-white hover:text-gray-400 flex items-center space-x-2">
            <Icon name="ic:round-calculate" style="" />
            <span>Tools</span>
          </button>
          <button class="text-white hover:text-gray-400 flex items-center space-x-2">
            <Icon name="material-symbols:info-rounded" style="" />
            <span>About</span>
          </button>
          <button class="text-white hover:text-gray-400 flex items-center space-x-2">
            <Icon name="material-symbols:logout-rounded" style="" />
            <span>Login/Register</span>
          </button>
        </div>
      </div>
    </nav>

    <div class="flex-1 flex justify-center items-center">
    </div>
  </div>
</template>

<style>
@import "tailwindcss";
</style>
