<script setup></script>

<template>
  <div class="flex min-h-screen bg-[#aeb982]">
    <div class="bg-gray-[#B5C18E] p-8 hidden md:block">
      <div class="mb-6">
        <h3 class="text-lg text-white">Profile</h3>
        <ul class="mt-2">
          <li class="mb-2">
            <a
              href="#"
              class="text-2xl font-semibold text-white px-4 py-2 block"
              >History</a
            >
          </li>
        </ul>
      </div>
      <div style="margin-top: 600px" class="mt-auto">
        <a
          href="#"
          class="rounded-2xl bg-green-300 p-2 pl-6 pr-6 text-2xl font-bold text-black hover:text-gray-800"
          >Log out</a
        >
      </div>
    </div>

    <div class="flex-1 p-4 bg-[#FEF3C6] flex flex-col">
      <div class="flex mb-4">
        <div class="w-1/5">
          <!-- Product Image -->
          <img
            src="https://via.placeholder.com/200"
            alt="Product Image"
            class="w-42 rounded-lg"
          />
        </div>
        <div class="w-1/4">
          <!-- Product Name and Price -->
          <h2 class="text-2xl font-bold mb-2">Product Name : ตู้เย็น GL</h2>
          <p class="text-lg mb-4">
            Defect: <span class="font-bold">ไม่มีประตูช่องฟรีซ</span>
          </p>
          <p class="text-lg mb-4">
            Price :<span class="font-bold">xxxxxx Baht</span>
          </p>
          <p class="text-lg mb-4">Amount :<span class="font-bold">1</span></p>
        </div>
        <div class="w-1/4 pt-20">
          <div class="flex items-center">
            <i class="fas fa-truck mr-2"></i>
            <div>
              <div>Chipping...</div>
              <div>Tracking : xxxxx</div>
            </div>
          </div>
        </div>
        <div class="w-1/4 pt-20 rounded-xl">
          <a
            href="#"
            class="rounded-2xl bg-[#758731] p-2 pl-6 pr-6 text-2xl font-bold text-white hover:text-gray-800"
            >Review</a
          >
        </div>
      </div>
      <div class="border-b border-[#4a5324] mb-4"></div>
      <!-- Additional content can be added here -->
    </div>
  </div>
</template>

<style scoped>
div {
  font-family: 'Poetsen One', sans-serif;
  font-weight: 400;
  font-style: normal;
  color: #4a5324;
}

@media (max-width: 767px) {
  .hidden.md\:block {
    display: none;
  }
}
</style>
