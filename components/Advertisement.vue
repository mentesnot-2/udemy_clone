<template>
    <div class="bg-[#ECEB98] py-3 pr-10">
      <div class="flex justify-center items-center">
        <div class="text-center">
          <span role="presentation" class=" text-black" data-testid="smart-bar-copy">
            <span class="text-black font-bold text-[17px]" data-purpose="smart-bar-title" data-testid="smart-bar-title">
              Sale ends today
            </span>
            <span class="text-black" role="presentation" data-purpose="smart-bar-subtitle" data-testid="smart-bar-subtitle">
              | Invest in the latest skills. Starting at $11.99.
            </span>
          </span>
          <span class="block text-black font-bold text-[17px]" data-testid="smart-bar-timer" data-client-side-render-only="CSR: component">
            <span>Ends in <span data-testid="timer-countdown">2h&nbsp;29m&nbsp;37s</span>.</span>
          </span>
        </div>
        
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'SmartBar',
  }
  </script>
  
  <style scoped>
  /* You can define any custom styles or Tailwind extensions here if needed */
  </style>
  