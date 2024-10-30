<script setup></script>

<template>
  <div class="bg-slate-500 min-h-screen flex justify-around">
    <div class="container mx-1 px-1 flex items-center max-w-screen-lg">
      <!-- Left Text Section -->
      <div class="text-center lg:text-left lg:justify-around">
        <p class="text-4xl text-gray-900 mb-3">Chat Simple</p>
        <h1 class="text-7xl font-bold text-gray-900 leading-tight">
          Easy, accurate, <br />
          and always free <br />
          tax filing
        </h1>
        <p class="text-gray-900 mt-4 mb-6">
          The hassle-free, worry-free, and actually free tax filing platform.
        </p>
        <router-link
          :to="{ name: 'login' }"
          class="bg-gray-900 text-white py-3 px-6 rounded-full hover:bg-gray-600"
        >
          Get started
        </router-link>
      </div>

      <!-- Right Image Section -->
      <div
        class="mt-10 pl-20 lg:mt-0 flex justify-center lg:justify-start relative"
      >
        <div class="relative">
          <!-- Parachute Image -->
          <img src="../../assets/vue.svg" alt="Logo" class="w-80 lg:w-80" />
        </div>
      </div>
    </div>
  </div>
</template>
