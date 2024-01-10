<script setup>
import Cards from './Cards.vue';
import About from './About.vue';
import Contact from './Contact.vue';

import { ref } from 'vue';

const isSidebarOpen = ref(false);

const toggleSidebar = () => {
  isSidebarOpen.value = !isSidebarOpen.value;
};
</script>

<template>
  <div>
    <nav>
      
      <div>
  <div class="relative flex justify-between items-start p-2">
    <div>
      <img src="https://www.singulart.com/blog/wp-content/uploads/2023/10/Leonardo-Da-Vinci.webp"
        style="width: 700px; height:auto; margin-right: 10px;">

      <div class="absolute top-1/2 transform -translate-y-1/2 right-0 p-20 text-xl text-center">
        <a class="font-extrabold mb-20 block text-white md:text-black">ლეონარდოს</a>
        <a class="font-extrabold mb-20 block text-white md:text-black">ფუნჯი</a>
        <a class="mb-10 block  text-white md:text-black">ხელოვნება არასოდეს მთავრდება</a>
      </div>
    </div>

    <div class="max-w-7xl mx-auto">
      <div class="hidden md:flex justify-end">
        <a href="" class="py-5 px-2 text-white md:text-black">მთავარი</a>
        <a href="" class="py-5 px-2 text-white md:text-black">გალერეა</a>
        <a href="" class="py-5 px-2 text-white md:text-black">მხატვრის შესახებ</a>
        <a href="" class="py-5 px-2 text-white md:text-black">კონტაქტი</a>
        <a href="" class="py-5 px-2 text-white md:text-black">შესვლა</a>
      </div>
    </div>
  </div>
</div>

      
      <div class="md:hidden absolute top-0 right-0 p-2 text-white">
        <button>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
            stroke="currentColor" class="w-15 h-10">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M3.75 5.25h16.5m-16.5 4.5h16.5m-16.5 4.5h16.5m-16.5 4.5h16.5" />
          </svg>
        </button>
      </div>
    </nav>

    <div>
      <Cards></Cards>
    </div>

    <div>
      <About></About>
    </div>

    <div>
      <Contact></Contact>
    </div>
  </div>
</template>




