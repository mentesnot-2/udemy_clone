<template>
    <div class="max-w-4xl p-6 ":style="{ marginLeft: '10.5%',maxWidth:'700px' }">
      <h2 class="text-3xl font-bold mb-4">Course content</h2>
      <div class="flex justify-between items-center mb-4">
        <span class="text-sm text-gray-600">5 sections • 19 lectures • 1h 51m total length</span>
        <button @click="toggleExpandAll" class="text-sm text-blue-600 hover:underline">
          {{ isExpanded ? 'Collapse all sections' : 'Expand all sections' }}
        </button>
      </div>
  
      <div v-for="section in sections" :key="section.title" class="mb-6">
        <div class="flex justify-between items-center border-b pb-2">
          <div class="flex items-center">
            <button @click="section.isOpen = !section.isOpen" class="focus:outline-none mr-2">
              <svg
                :class="section.isOpen ? 'transform rotate-180' : ''"
                class="h-5 w-5 text-gray-500 transition-transform"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </button>
            <h3 class="text-lg font-semibold">{{ section.title }}</h3>
          </div>
          <span class="text-sm text-gray-500">{{ section.totalDuration }}</span>
        </div>
  
        <div v-if="section.isOpen" class="mt-4 space-y-2">
          <ul>
            <li v-for="lecture in section.lectures" :key="lecture.title" class="flex justify-between items-center py-2">
              <div class="flex items-center">
                <svg class="h-4 w-4 text-gray-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.752 11.168l-3.197-2.132a1 1 0 00-1.555.832v4.264a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z" />
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                <span class="text-sm">{{ lecture.title }}</span>
              </div>
              <span class="text-sm text-gray-500">{{ lecture.duration }}</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        isExpanded: false,
        sections: [
          {
            title: 'GETTING STARTED FIGMA',
            isOpen: false,
            totalDuration: '09:02',
            lectures: [
              { title: 'FIGMA INTERFACE', duration: '06:33' },
              { title: 'INSTALLING FONT IN BROWSER', duration: '02:29' },
            ],
          },
          {
            title: 'SETTING UP FILE',
            isOpen: false,
            totalDuration: '16:43',
            lectures: [
              { title: 'CREATING FILE', duration: '04:35' },
              { title: 'CREAT AND EDIT FRAMES', duration: '08:19' },
              { title: 'CREATING PAGES', duration: '03:49' },
            ],
          },
          {
            title: 'ADDING CONTENT',
            isOpen: false,
            totalDuration: '13:06',
            lectures: [
              { title: 'SHAPES', duration: '07:13' },
              { title: 'CUSTOM SHAPES', duration: '05:53' },
            ],
          },
          {
            title: 'WORKING WITH TEXT',
            isOpen: false,
            totalDuration: '07:12',
            lectures: [
              { title: 'TEXT TOOL', duration: '04:12' },
              { title: 'TEXT PROPERTIES', duration: '03:00' },
            ],
          },
          {
            title: 'WORKING WITH IMAGES',
            isOpen: false,
            totalDuration: '05:48',
            lectures: [
              { title: 'IMPORTING IMAGES', duration: '03:48' },
              { title: 'IMAGE PROPERTIES', duration: '02:00' },
            ],
          }
        ],
      };
    },
    methods: {
      toggleExpandAll() {
        this.isExpanded = !this.isExpanded;
        this.sections.forEach((section) => {
          section.isOpen = this.isExpanded;
        });
      },
    },
  };
  </script>
  
  <style scoped>
  /* Add any additional styling if necessary */
  </style>
  