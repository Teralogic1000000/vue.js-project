<script setup>
import cardImage from '../components/cardImage.vue';
import cardName from '../components/cardName.vue';
import cardButtons from '../components/cardButtons.vue';
import cardLinks from '../components/cardLinks.vue';
import cardStatus from '../components/cardStatus.vue';
</script>

<template>
  <div class="flex justify-center items-center min-h-screen bg-gray-100">
    <div class="bg-white shadow-lg p-6 w-80 text-center">
      <cardImage />
      <cardName  />
      <cardLinks />
      <cardButtons />
      <cardStatus likes="23.4k" shares="17.8k" comments="11.4k" />
    </div>
  </div>
</template>

