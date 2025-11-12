<template>
  <div class="flex justify-around text-gray-500 text-sm">
    <div class="flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-5 h-5 mr-1">
        <path stroke-linecap="round" stroke-linejoin="round" d="M4.318 6.318a4.5 4.5 0 016.364 0L12 7.636l1.318-1.318a4.5 4.5 0 116.364 6.364L12 21l-7.682-7.682a4.5 4.5 0 010-6.364z" />
      </svg>
      {{ likes }}
    </div>
    <div class="flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-5 h-5 mr-1">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8.59 13.41a2 2 0 11-2.83-2.83l7-7a2 2 0 112.83 2.83l-7 7z" />
        <path stroke-linecap="round" stroke-linejoin="round" d="M16 8v6h6" />
      </svg>
      {{ shares }}
    </div>
    <div class="flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-5 h-5 mr-1">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8 10h.01M12 10h.01M16 10h.01M21 12c0 4.418-4.03 8-9 8-1.61 0-3.113-.423-4.39-1.16L3 20l1.16-4.61C3.423 14.113 3 12.61 3 11c0-4.418 4.03-8 9-8s9 3.582 9 8z"/>
      </svg>
      {{ comments }}
    </div>
  </div>
</template>

<script setup>
defineProps({
  likes: Number,
  shares: Number,
  comments: Number
})
</script>
