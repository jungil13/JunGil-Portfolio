<!-- Projects.vue -->
<template>
 <section class="container mx-auto py-8">
  <h1 class="text-3xl font-bold mb-6 text-center font-sans text-gray-800">My Projects</h1>
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
        <p class="text-gray-700">Description of Project 1. Chatify is a library offered by laravel .</p>
      </div>
    </div>
    
    <!-- Card 2 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/ecom.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Ecommerce Website</h2>
        <p class="text-gray-700">Description of Project 2. Ecommerce website for clothing.</p>
      </div>
    </div>
    
    <!-- Card 3 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/spotify.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Spotify API</h2>
        <p class="text-gray-700">Description of Project 3. Spotify Api made with Node Js</p>
      </div>
    </div>
    
    <!-- Card 4 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/timewise.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">TimeWise - Laravel</h2>
        <p class="text-gray-700">App Dev Project - it is a blogging website for time management</p>
      </div>
    </div>
    
    <!-- Card 5 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/account.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Account Manager</h2>
        <p class="text-gray-700">Description of Project 5. A system for managing accounts like add user roles and changing password</p>
      </div>
    </div>
    
    <!-- Card 6 -->
    <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
      <img class="w-full h-40 object-cover" src="/images/port.png" alt="Project Image">
      <div class="p-4">
        <h2 class="text-lg font-semibold mb-2">Portfolio Website</h2>
        <p class="text-gray-700">Description of Project 6. My personal Portfolio made with vue js frontend only</p>
      </div>
    </div>
  </div>
</section>
</template>

<script>

</script>

<style scoped>

</style>
