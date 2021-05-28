<template>
<div class="grid grid-container justify-center p-8 gap-8">
  <div class="flex justify-between items-center">
    <div class="flex justify-center items-center h-6 w-6 rounded-full ring-4 bg-green-500 ring-green-500 mx-2">
      <span class="text-gray-100 font-semibold">1</span>
    </div>
    <hr class="w-52 border-2 border-green-500">
    <div class="flex justify-center items-center h-6 w-6 rounded-full ring-4 bg-green-500 ring-green-500 mx-2">
      <span class="text-gray-100 font-semibold">2</span>
    </div>
    <hr class="w-52 border-2">
    <div class="flex justify-center items-center h-6 w-6 rounded-full ring-4 ring-gray-300 mx-2">
      3
    </div>
    <hr class="w-52 border-2">
    <div class="flex justify-center items-center h-6 w-6 rounded-full ring-4 ring-gray-300 mx-2">
      4
    </div>
    <hr class="w-52 border-2">
    <div class="flex justify-center items-center h-6 w-6 rounded-full ring-4 ring-gray-300 mx-2">
      5
    </div>
  </div>
  <div class="h-96 border-gray-400 border-4">
  </div>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Home'
})
</script>
