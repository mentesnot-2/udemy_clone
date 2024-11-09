<template>
  <div class="bg-white shadow-md rounded-lg max-w-sm mx-auto mt-10 mb-10 sticky top-10">
    <div class="relative w-full h-auto mb-4 z-0">
      <img
        src="https://img-c.udemycdn.com/course/240x135/6080417_89c8_2.jpg"
        alt="Course Preview"
        class="w-full h-auto sticky top-0"
      />
      <div class="absolute inset-0 flex flex-col items-center justify-center bg-black bg-opacity-50">
        <div class="h-16 w-16 bg-white rounded-full flex items-center justify-center cursor-pointer">
          <svg class="w-12 h-12 text-black" fill="currentColor" viewBox="0 0 20 20">
            <path d="M4 3v14l12-7-12-7z"/>
          </svg>
        </div>
        <span class="text-white font-semibold text-xl mt-4">Preview this course</span>
      </div>
    </div>

    <!-- Scrollable Content -->
    <Purchase/>
  </div>
</template>

<style scoped>
.sticky {
  position: sticky;
  top: 0;
}
</style>
