<script>
export default {}
</script>
<template>
<div class="flex p-4 bg-gray-800 text-white ">
  <!-- Left side: Contact details -->
  <div class="w-1/2 p-4">
    <h2 class="text-2xl font-bold mb-4">კონტაქტი</h2>
    
    <!-- Contact form inputs -->
    <div class="mb-4">
      <label for="name" class="block text-white">თბილისი, ლეონარდო და ვინჩის ქუჩა N15</label>
      
    </div>
    
    <div class="mb-4">
      <label for="email" class="block text-white">მობილური: (+995) 551 10 11 12</label>
    </div>
    <div class="mb-4">
      <label for="email" class="block text-white">მეილი: ლეონარდოს_ფუნჯი@gmail.com</label>
    </div>
  </div>

  <!-- Right side: Message area -->
  <div class="w-1/2 p-4">
    <h2 class="text-2xl font-bold mb-4"></h2>
    
    <!-- Message form inputs -->
    <div class="mb-4">
    
      <input placeholder="მეილი" type="text" id="subject" name="subject" class="w-full border rounded p-2">
    </div>
    
    <div class="mb-4">
    
    <input placeholder="სათაური" type="text" id="subject" name="subject" class="w-full border rounded p-2">
  </div>
    <div class="mb-4">
      
      <textarea placeholder="შეტყობინება" id="message" name="message" rows="4" class="w-full border rounded p-2"></textarea>
    </div>
    
    <button class="bg-blue-500 text-white py-2 px-4 rounded">გაგზავნა</button>
  </div>
</div>

</template>