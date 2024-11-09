<template>
    <div class="mb-6" :style="{ marginLeft: '10.5%',maxWidth:'700px' }">
      <h2 class="text-2xl font-bold mb-4" data-purpose="requirements-title">Requirements</h2>
      <ul class="list-none pl-4">
        <li class="flex items-start mb-3">
          <!-- Icon -->
          <svg fill="#000000" width="800px" height="800px" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" focusable="false" class="w-5 h-5 text-neutral-500 mr-2"><path d="M7.8 10a2.2 2.2 0 0 0 4.4 0 2.2 2.2 0 0 0-4.4 0z"/></svg>
          <!-- List Item Content -->
          <div class="text-sm">
            Willingness or Interest to learn about Figma for UI and UX Design.
          </div>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'RequirementsList'
  }
  </script>
  
  <style scoped>
  /* You can add any custom styles you need, but this design can be accomplished with Tailwind */
  </style>
  