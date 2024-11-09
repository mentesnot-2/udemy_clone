<template>
    <div class="container p-8 bg-white shadow-lg border border-gray-300  py-4 h-80">
      <h2 class="text-2xl font-bold mb-6">What you'll learn</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Column with 5 Objectives -->
        <ul class="space-y-2">
          <li
            v-for="(item, index) in objectives.slice(0, 5)"
            :key="index"
            class="flex items-start space-x-3"
          >
            <!-- Tick Icon -->
            <svg
              aria-hidden="true"
              focusable="false"
              class="w-5 h-5 text-black flex-shrink-0"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 13l4 4L19 7"
              />
            </svg>
            <!-- Objective Text -->
            <span class="text-sm text-gray-700">{{ item }}</span>
          </li>
        </ul>
  
        <!-- Right Column with 5 Objectives -->
        <ul class="space-y-2">
          <li
            v-for="(item, index) in objectives.slice(5)"
            :key="index + 5"
            class="flex items-start"
          >
            <!-- Tick Icon -->
            <svg
              aria-hidden="true"
              focusable="false"
              class="w-5 h-5 text-black flex-shrink-0"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 13l4 4L19 7"
              />
            </svg>
            <!-- Objective Text -->
            <span class="text-sm text-gray-700">{{ item }}</span>
          </li>
        </ul>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        objectives: [
          "Techniques for prototyping interactive experiences.",
          "Basics of the Figma interface and essential tools.",
          "How to create wireframes and user interfaces.",
          "Advanced design techniques, including component creation & responsive design.",
          "Efficient use of design systems for consistency across projects.",
          "Collaboration tools for seamless teamwork & version control.",
          "Practical application of skills through real-world projects & design challenges.",
          "How to create high-fidelity mockups and user flows.",
          "Best practices for effective UI/UX design using tools like Figma.",
          "Building a portfolio of polished design projects.",
        ],
      };
    },
  };
  </script>
  
  <style scoped>
  .container {
    max-width: 700px;
    margin-top: 40px;
    margin-bottom: 40px;
    margin-left: 10.5%;
  }
  </style>
  