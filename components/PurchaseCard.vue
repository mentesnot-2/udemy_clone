<template>
    <div class="bg-white shadow-md rounded-lg max-w-sm mx-auto mt-10 mb-10">
      <!-- Image container with relative positioning -->
      <div class="relative w-full h-auto mb-4 z-0">
        <img
          src="https://img-c.udemycdn.com/course/240x135/6080417_89c8_2.jpg"
          alt="Course Preview"
          class="w-full h-auto"
        />
  
        <!-- Play Icon and Preview Text centered on the image -->
        <div class="absolute inset-0 flex flex-col items-center justify-center bg-black bg-opacity-50">
            <!-- Play Icon in the center -->
            <div class="h-16 w-16 bg-white rounded-full flex items-center justify-center cursor-pointer">
                <svg class="w-12 h-12 text-black" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M4 3v14l12-7-12-7z"/>
                </svg>
            </div>

            <!-- Preview Text at the bottom -->
            <span class="text-white font-semibold text-xl mt-4">Preview this course</span>
        </div>



      </div>
  
      <div class="mb-2 px-6">
        <div class="flex items-center justify-start space-x-2">
          <span class="text-4xl font-bold text-black">$11.99</span>
          <span class="line-through text-black text-lg pt-1">$49.99</span>
          <span class="text-black text-lg pt-1">76% off</span>
        </div>
      </div>
  
      <div class="flex items-center text-gray-600 px-6">
        <svg class="h-5 w-5 mr-1" fill="currentColor" viewBox="0 0 20 20">
          <path d="M5 2a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V4a2 2 0 00-2-2H5zm0 2h10v12H5V4zm5 3a1 1 0 01.993.883L11 8v4a1 1 0 01-1.993.117L9 12V8a1 1 0 011-1zm0 6a1.5 1.5 0 110 3 1.5 1.5 0 010-3z"/>
        </svg>
        <span class="text-sm text-red-600"><strong>3 hours</strong> left at this price!</span>
      </div>
  
      <div class="flex flex-col space-y-4 px-6 py-4">
        <button class="w-full py-3 bg-purple-700 text-white rounded-md hover:bg-purple-900 transition">
          Add to cart
        </button>
        <button class="w-full py-3 text-black border border-black hover:bg-white-800 transition">
          Buy now
        </button>
        <button class="w-full mt-2 text-gray-600 text-sm transition">
          30-Day Money-Back Guarantee
        </button>
      </div>
  
      <div class="mt-2 px-6">
        <h2 class="text-lg font-semibold mb-2">This course includes:</h2>
        <ul class="space-y-2 text-gray-600 text-sm">
          <li class="flex items-center">
            <svg class="h-5 w-5 mr-2" fill="currentColor" viewBox="0 0 20 20">
              <path d="M2 10a8 8 0 118 8 8 8 0 01-8-8zM10 4a6 6 0 106 6 6 6 0 00-6-6zm0 9a3 3 0 100-6 3 3 0 000 6z"/>
            </svg>
            <span>2 hours on-demand video</span>
          </li>
          <li class="flex items-center">
            <svg class="h-5 w-5 mr-2" fill="currentColor" viewBox="0 0 20 20">
              <path d="M2.003 5.884L10 2l7.997 3.884v6.769L10 18l-7.997-5.347V5.884zM10 4l6 2.882v4.786l-6 4-6-4V6.882L10 4z"/>
            </svg>
            <span>Access on mobile and TV</span>
          </li>
          <li class="flex items-center">
            <svg class="h-5 w-5 mr-2" fill="currentColor" viewBox="0 0 20 20">
              <path d="M4 5h16v11a2 2 0 01-2 2H4a2 2 0 01-2-2V5h2zm2 0v11h12V5H6zM1 4v2h2V4h16v2h2V4a2 2 0 00-2-2H3a2 2 0 00-2 2z"/>
            </svg>
            <span>Full lifetime access</span>
          </li>
          <li class="flex items-center">
            <svg class="h-5 w-5 mr-2" fill="currentColor" viewBox="0 0 20 20">
              <path d="M9 2a1 1 0 011 1v4H5V3a1 1 0 011-1h2zm-5 9V7h14v4H4zm2 1h10v5a1 1 0 01-1 1H7a1 1 0 01-1-1v-5zM5 7V4a3 3 0 016-0v3h2V4a5 5 0 00-10 0v3h2z"/>
            </svg>
            <span>Certificate of completion</span>
          </li>
        </ul>
      </div>
  
      <div class="flex flex-row space-x-8 font-bold text-sm mt-4 px-6">
        <a href="#" class="underline"><span>Share</span></a>
        <a href="#" class="underline"><span>Gift this course</span></a>
        <a href="#" class="underline"><span>Apply Coupon</span></a>
      </div>
  
      <div class="mt-4 p-6">
        <div class="border-dashed border border-gray-600">
          <ul class="list-none pl-4">
            <li data-purpose="code-text" class="text-gray-600 text-sm">
              <b>ST2MT110724BNEW</b> is applied
            </li>
            <li class="text-sm text-gray-600">Udemy coupon</li>
          </ul>
        </div>
        <button type="button" class="absolute top-0 right-0 p-2 text-black hover:text-gray-900">
          <span class="text-lg font-bold">X</span>
        </button>
      </div>
  
      <div class="sidebar-container-buy-for-team bg-white p-6 border-t border-gray-300">
        <h2 class="text-lg font-semibold mb-2">Training 5 or more people?</h2>
        <p class="text-sm text-gray-600 mb-4">
          Get your team access to 27,000+ top Udemy courses anytime, anywhere.
        </p>
        <button class="w-full py-2 text-black border border-black hover:bg-white-800 transition text-bold">
          Try Udemy for Business
        </button>
      </div>
    </div>
  </template>
  