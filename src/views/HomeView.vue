<script setup>
import LeftSide from '@/components/LeftSide.vue';
import searchbar from '@/components/searchbar.vue';
import Content from '@/components/content.vue';
</script>

<template>
  <main>
    <!-- main container -->
    <div id="parent-container" class="md:flex h-screen w-screen">
        <!-- left/side-bar container-->
        <LeftSide />

        <!-- right/main container -->
        <div id="rignt-container" class="w-full  flex flex-col">
            <!-- header/search bar section -->
            <!-- <searchbar /> -->

            <!-- main/task cards container -->
           <Content/>
        </div>
    </div>
  </main>
</template>
