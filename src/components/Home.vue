<template>
  <div class="home flex flex-col md:flex-row items-center justify-center bg-white">
    <!-- Content Section -->
    <div class="content text-center md:text-left md:mr-8">
      <div class="intro">
    <h1 id="typed" class="text-4xl font-extrabold leading-tight tracking-tight mb-8 text-black-500">
      <span class="rgb-animation text-4xl">Hi, I'm Jun Gil Casquejo</span>
    </h1>
    <p class="mb-2 text-xl text-black font-semibold leading-tight tracking-tight">
     Web Developer and BSIT student at
    </p>
    <p class="mb-6 text-xl text-black font-semibold leading-tight tracking-tight">
     Cordova Public College
    </p>
  </div>
      
    </div> 
    <!-- Image Section -->
    <div class="character max-w-xs md:max-w-md">
      <img src="/images/akomani.jpg" alt="Ako" class="w-full h-auto rounded-full">
    </div>
    <router-view></router-view>
  </div>

  <section class="container mx-auto py-8 mb-6">
  <h1 class="text-3xl font-bold mb-6 text-center leading-tight tracking-tight text-red-800">My Projects</h1>
  <h1 class="text-2xl font-semibold mb-6 text-center font-sans text-gray-800">Some of my Recent Projects</h1>
   <!-- Search Bar -->
   <div class="flex justify-center mb-6">
        <input type="text" v-model="searchQuery" class="px-4 py-2 border border-gray-600 rounded-md focus:outline-none focus:border-blue-400" placeholder="Search...">
      </div>
  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <!-- Card 1 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/realchat.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Chatify by Laravel</h2>
        <p class="text-gray-700 mb-4">Description of Project 1. Chatify is a library offered by laravel .</p>
        <button class="text-red-800 text-lg font-semibold">View More</button>
      </div>
    </div>
    
    <!-- Card 2 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/ecom.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Ecommerce Website</h2>
        <p class="text-gray-700 mb-4">Description of Project 2. Ecommerce website for clothing.</p>
        <button class="text-red-800 text-lg font-semibold">View More</button>
      </div>
    </div>
    
    <!-- Card 3 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/spotify.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Spotify API</h2>
        <p class="text-gray-700 mb-4">Description of Project 3. Spotify Api made with Node Js</p>
        <button class="text-red-800 text-lg font-semibold">View More</button>
      </div>
    </div>
    
    <!-- Card 4 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/timewise.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">TimeWise - Laravel</h2>
        <p class="text-gray-700 mb-4">App Dev Project - it is a blogging website for time management</p>
        <button class="text-red-800 text-lg font-semibold">View More</button>
      </div>
    </div>
    
    <!-- Card 5 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/account.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Account Manager</h2>
        <p class="text-gray-700 mb-4">Description of Project 5. A system for managing accounts like add user roles and changing password</p>
        <button class="text-red-800 text-lg font-semibold">View More</button>
      </div>
    </div>
    
    <!-- Card 6 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/port.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Portfolio Website</h2>
        <p class="text-gray-700 mb-4">Description of Project 6. My personal Portfolio made with vue js frontend only</p>
        <button class="text-red-800 text-lg font-semibold">View More</button>
      </div>
    </div>
  </div>
</section>

<section class="container mx-auto py-8">
  <h1 class="text-3xl font-bold mb-6 text-center font-sans text-red-800">Contact Me!</h1>
  
  <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-black p-6">
    <div class="mb-4">
      <label for="email" class="block text-lg font-semibold text-gray-800">Email:</label>
      <input type="email" id="email" name="email" class="mt-1 p-2 w-full border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="example@example.com">
    </div>
    
    <div class="mb-4">
      <label for="phone" class="block text-lg font-semibold text-gray-800">Phone:</label>
      <input type="text" id="phone" name="phone" class="mt-1 p-2 w-full border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="+1 234 567 890">
    </div>
    
    <div class="mb-4">
      <label for="message" class="block text-lg font-semibold text-gray-800">Message:</label>
      <textarea id="message" name="message" rows="4" class="mt-1 p-2 w-full border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Type your message here..."></textarea>
    </div>
    
    <button class="w-full bg-black hover:bg-gray-800 text-white font-semibold py-2 px-4 rounded-md focus:outline-none focus:bg-blue-600">Send Message</button>
  </div>
</section>



</template>

<script>
</script>

<style scoped>
.rgb-animation {
  animation: rgbAnimation 3s infinite alternate;
}

@keyframes rgbAnimation {
  0% {
    color: red;
  }
  33% {
    color: green;
  }
  66% {
    color: blue;
  }
  100% {
    color: red;
  }
}
</style>
