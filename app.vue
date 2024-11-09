<template>
  <div>
    <Advertisement />
    <Header />
    <div class="relative">
      <div class="relative">
        <CourseInfo class="w-full" /> 
        <PurchaseCard class="absolute top-0 right-[100px]" />
      </div>
    </div>
    <Course/>
    <ExploreTopics/>
    <CourseContent/>
    <Requirement/>
    <CourseDescription/>
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
