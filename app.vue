<template>
  <div>
    <Advertisement />
    <Header />
    <!-- <CourseInfo class="relative" /> -->
    <div class="relative">
      <!-- Wrapper for positioning -->
      <div class="relative">
        <CourseInfo class="w-full" /> <!-- Full width CourseInfo -->
        <PurchaseCard class="absolute top-0 right-[100px] z-10" />
        <!-- Adjust top and left values as needed -->
      </div>
    </div>
    <Course/>
  </div>
</template>

<style scoped>
.relative {
  position: relative;
}

.absolute {
  position: absolute;
}

.z-10 {
  z-index: 10;
}
</style>
