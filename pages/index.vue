<script setup>
// You can add any reactive properties or methods here if needed
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <section class="text-center mt-20">
      <h1 class="text-5xl font-bold">Hello, I am Amal. A. S</h1>
      <p class="text-base text-gray-900 p-2 italic">Full Stack Developer</p>
    </section>

    <section class="flex flex-col md:flex-row items-center md:justify-between my-10">
      <div class="md:w-3/4">
        <h2 class="text-3xl font-bold">About Me</h2>
        <p class="text-lg py-2">
            I am a full-stack developer based in Trivandrum, skilled in both front-end and back-end development.
            I have recently completed my B.Tech in Electronics and communication from Marian Engineering College.
             With a background in electronics engineering, I have a solid understanding of technical concepts that enhance my programming skills. 
             I enjoy building web applications and have experience with modern frameworks and tools, including Tailwind CSS for styling and improving user interfaces. 
             My passion lies in creating efficient, user-friendly solutions that meet client needs and improve overall user experience.
              I am continuously learning and staying updated with the latest technologies to enhance my expertise in the field.
        </p>
    
      </div>
      <img src="/assets/images/pf1.png" class="w-60 md:max-w-sm p-8 mx-auto top-5" alt="Profile Image" />
    </section>

  

    <!-- Footer Section with Links -->
    <footer class="w-full bg-gray-800 text-white text-center py-4 mt-auto">
      <div class="container mx-auto">
      
        <div class="mt-2 flex justify-center space-x-4">
          <a href="https://github.com/amal1923" target="_blank" class="text-gray-400 hover:text-white">GitHub</a>
          <a href="https://www.linkedin.com/in/amal-a-s-51aa72209/" target="_blank" class="text-gray-400 hover:text-white">LinkedIn</a>
          
        </div>
      </div>
    </footer>
  </div>
</template>


<style scoped>
/* Additional styles can be added here */
</style>
