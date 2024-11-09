<template>
  <div class="bg-dark p-20 py-7">
    <!-- Breadcrumb Section -->
    <div class="text-white text-lg ml-16">
      <div class="flex space-x-2">
        <a href="/courses/design/" class="text-sm font-semibold">Design</a>
        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6l6 6-6 6"/>
        </svg>
        <a href="/courses/design/user-experience/" class="text-sm font-semibold">User Experience Design</a>
        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6l6 6-6 6"/>
        </svg>
        <a href="/topic/figma/" class="text-sm font-semibold">Figma</a>
      </div>
    </div>

    <!-- Main Content Section -->
    <div class="mt-6 ml-10 w-10/12">
      <div class="bg-dark pl-6 rounded-lg mb-6">
        <div class="flex justify-between items-center">
          <div class="w-full md:w-2/3 flex flex-start flex-col">
            <h1 class="text-3xl text-white font-bold mb-4">Master Figma From Beginner to Pro in UI/UX Design</h1>
            <p class="font-bold text-gray-300">Figma Essentials: Design Beautiful Interfaces with Ease, Craft Amazing Designs with Figma for Success.</p>
          </div>
          <!-- <div class="hidden md:block w-1/3">
            <img src="https://img-c.udemycdn.com/course/240x135/6080417_89c8_2.jpg" alt="Course Preview" class="w-full h-auto rounded-lg"/>
          </div> -->
        </div>
      </div>

      <!-- Course Price and Rating -->
      <div class="mt-2 pl-6 flex justify-start space-x-2 items-center text-white">
        <button class="bg-orange-200 text-black py-1 px-3 text-sm font-semibold">
            Highest Rated
        </button>
        <span class="text-yellow-600">5.0</span>
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/ae/5_stars.svg" alt="Course Preview" class="w-24 h-auto rounded-lg"/>
        <a href="#" >(80 ratings)</a>
        <span>661 students</span>
      </div>

      <!-- Instructor Info -->
      <div class="mt-2 pl-6 space-x-2">
        <span class="text-sm text-gray-400 font-bold">Created by</span>
        <a href="#instructor-1" class="text-lg text-blue-400">Faris Azam</a>
      </div>

      <!-- Last Update and Language -->
      <div class="mt-4 text-gray-300 text-sm flex flex-row space-x-4 pl-6 mb-6 font-bold">
        <span>Last updated 7/2024</span>
        <span>English</span>
        <span>
            English [Auto]
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // This page doesn't require any script logic
}
</script>

<style scoped>
.bg-dark {
  background-color: #1C1D1F;
}
.bg-gradient-to-b {
  background: linear-gradient(to bottom, #1f2937, #4b5563);
}
</style>
