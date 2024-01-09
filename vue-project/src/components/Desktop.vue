<script >
import Cards from './Cards.vue';
import About from './About.vue';
import Contact from './Contact.vue';

export default {
    components: { Cards, About, Contact }
}
</script>


<template>
  <nav>
    <!-- desktop menu -->
     <div>
     
      <div class="flex justify-between items-start p-2">
  <div>
    <img src="https://www.singulart.com/blog/wp-content/uploads/2023/10/Leonardo-Da-Vinci.webp" 
      style="width: 700px; height:auto; margin-right: 10px;">
  </div>
  
  <div class="max-w-7xl mx-auto">
    <div class="hidden md:flex justify-end">
      <a href="" class="py-5 px-2">მთავარი</a>
      <a href="" class="py-5 px-2">გალერეა</a>
      <a href="" class="py-5 px-2">მხატვრის შესახებ</a>
      <a href="" class="py-5 px-2">კონტაქტი</a>
      <a href="" class="py-5 px-2">შესვლა</a>
    </div>
    <div class="p-20 text-5xl text-center">
  <a class="font-extrabold mb-20 block">ლეონარდოს</a>
  <a class="font-extrabold mb-20 block">ფუნჯი</a>
  <a class="mb-10 block">ხელოვნება არასოდეს მთავრდება</a>
</div>

  </div>
</div>

     </div>
      <!-- mobile menu -->
      
  <div class="md:hidden flex justify-center py-5 ">
  <button>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 5.25h16.5m-16.5 4.5h16.5m-16.5 4.5h16.5m-16.5 4.5h16.5" />
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
</template>