<style scoped>
div {
  font-family: 'Poetsen One', sans-serif;
  font-weight: 400;
  font-style: normal;
  color: white;
}

header {
  background-color: #758731;
  color: #727171;
}
</style>

<template>
  <header class="flex items-center justify-between bg-white py-4 px-6">
    <div class="flex items-center">
      <RouterLink to="/" class="text-3xl font-bold hover:cursor-pointer"
        >Cheap!</RouterLink
      >
    </div>
    <div class="flex items-center">
      <i class="fa-solid fa-magnifying-glass mr-2"></i>
      <input
        type="text"
        placeholder="Search..."
        class="px-4 py-2 border border-gray-300 rounded-l-md focus:outline-none focus:ring-2 focus:ring-blue-500"
      />
      <button
        class="bg-blue-500 text-white px-4 py-2 rounded-r-md hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500"
      >
        Search
      </button>
    </div>
    <div class="flex items-center space-x-4">
      <button
        class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500"
      >
        <i class="fas fa-shopping-cart"></i>
      </button>
      <button
        class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500"
      >
        <i class="fas fa-comments"></i>
      </button>
    </div>
  </header>
</template>

<script setup></script>
