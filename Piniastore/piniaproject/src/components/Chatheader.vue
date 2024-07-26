<template>
  <div class="ml-64 pl-32">
    <div class="flex justify-between items-center bg-[#44403c] p-4 sticky top-0 ">
      <div class="px-3">
        <h4>Selam</h4>
        <p>last seen recently</p>
      </div>
      <div class="space-x-3">
        <i class="bi bi-telephone-fill text-xl"></i>
        <i class="bi bi-search-heart text-xl"></i>
      </div>
    </div>
    <div class="overflow-y-scroll">
   <Chatpage />
    </div>
  </div>
</template>


<script setup>
import Chatpage from './Chatpage.vue'
</script>