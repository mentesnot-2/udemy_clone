<template>
    <div class="bg-white rounded-lg max-w-4xl" :style="{ marginLeft: '10.5%',maxWidth:'700px' }">
      <div class="space-y-4">
        <!-- Description Header -->
        <h2 class="text-2xl font-semibold text-gray-800">Description</h2>
        <!-- Description Content -->
        <div v-if="showMore" class="space-y-4">
          <p><strong class="text-black">CRITICAL NOTICE Prior to Enrollment:</strong></p>
          <p>This course does not serve as a substitute for official vendor materials necessary for certification exams. It lacks endorsement from the certification vendor, and participants will not receive official certification study materials or a voucher as part of this course.</p>
          <p>Are you ready to take your design skills to the next level? Whether you’re a beginner looking to break into the world of UI/UX design or an experienced designer wanting to enhance your toolkit, this comprehensive Figma course is perfect for you. <strong>Figma</strong> is a powerful, browser-based design tool that enables designers to collaborate in real-time, create stunning user interfaces, and streamline their workflow.</p>
          <p>In this course, you will learn everything you need to know to become proficient in <strong>Figma</strong>. We’ll start with the basics, including an introduction to the Figma interface, understanding design principles, and mastering the essential tools and features. You’ll get hands-on experience with creating wireframes, designing user interfaces, and prototyping interactive experiences.</p>
          <p>As we progress, we’ll dive deeper into advanced techniques that will elevate your designs. You’ll explore component creation, responsive design, and efficient use of design systems to maintain consistency across projects. We’ll also cover collaboration tools that make working with teams seamless, and version control features that keep your designs organized.</p>
          <p>Throughout the course, you’ll work on real-world projects and design challenges that will build your portfolio and give you practical experience. You’ll learn how to create high-fidelity mockups, interactive prototypes, and user flows that effectively communicate your design ideas.</p>
          <p>By the end of the course, you’ll have a strong foundation in <strong>Figma</strong> and a set of polished projects to showcase your skills.</p>
          <p>My engaging lessons are designed to be clear and easy to follow, with step-by-step instructions and plenty of visual aids.</p>
          <p>Whether you’re designing a mobile app, a website, or any other digital product, this course will equip you with the knowledge and confidence to create professional-quality designs.</p>
          <p>Join me on this journey to mastering Figma and unlocking your potential as a UI/UX designer.</p>
          <p>Enroll now and start creating amazing designs that stand out!</p>
          <p>Thank you</p>
        </div>
  
        <!-- Who this course is for -->
        <div class="space-y-4">
          <h3 class="text-xl font-semibold text-gray-800">Who this course is for:</h3>
          <ul class="list-disc pl-5 space-y-2">
            <li>Beginners who are new to UI/UX design and want to learn Figma from scratch.</li>
            <li>Experienced designers looking to enhance their skills and add Figma to their toolkit.</li>
            <li>Freelancers and professionals seeking to streamline their design process and improve collaboration.</li>
            <li>Product managers and developers interested in understanding the design process and working more effectively with design teams.</li>
            <li>Anyone passionate about creating beautiful, user-friendly digital products.</li>
          </ul>
        </div>
  
        <!-- Show More/Show Less Button -->
        <div class="text-center mt-4">
          <button @click="toggleShowMore" class="text-sm text-blue-500 hover:text-blue-700">
            <span v-if="showMore">Show Less</span>
            <span v-else>Show More</span>
          </button>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        showMore: true,
      };
    },
    methods: {
      toggleShowMore() {
        this.showMore = !this.showMore;
      },
    },
  };
  </script>
  
  <style scoped>
  /* Optional additional styles */
  </style>
  