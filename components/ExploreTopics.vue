<template>
    <div class="topic-navigation w-full":style="{ marginLeft: '10.5%',maxWidth:'700px' }" data-client-side-render-only="CSR: component">
      <h2 class="text-2xl font-bold mb-4">Explore related topics</h2>
      <ul class="flex space-x-4">
        <li>
          <NuxtLink to="/topic/figma/" class="btn btn-large btn-secondary btn-round text-md">
            <span class="btn-label">Figma</span>
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/courses/design/user-experience/" class="btn btn-large btn-secondary btn-round text-md">
            <span class="btn-label">User Experience Design</span>
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/courses/design/" class="btn btn-large btn-secondary btn-round text-md">
            <span class="btn-label">Design</span>
          </NuxtLink>
        </li>
      </ul>
    </div>
  </template>
  
  <style scoped>
  /* Custom button styles using Tailwind CSS utility classes */
  .btn {
    @apply inline-flex items-center justify-center px-4 py-2 rounded-full;
  }
  
  .btn-large {
    @apply text-lg;
  }
  
  .btn-secondary {
    @apply bg-white text-gray-800 hover:bg-gray-300 border border-black;
  }
  
  .btn-round {
    @apply rounded-full;
  }
  
  .text-md {
    @apply text-base;
  }
  
  .btn-label {
    @apply font-semibold;
  }
  
  </style>
  