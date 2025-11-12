<template>
   <!-- right/main container -->
        <div id="rignt-container" class="w-full  flex flex-col">
            <!-- header/search bar section -->
            <div id="header" class="w-full px-4 py-1.5 bg-gray-200">
                <div id="search-bar">
                    <span class="relative ">
                        <svg class="absolute left-30 top-1/2 -translate-y-1/2 text-gray-400 h-4 w-4" fill="currentColor"
                            viewBox="0 0 20 20">
                                <path fill-rule="evenodd"
                                d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                                clip-rule="evenodd"></path>
                        </svg>
                        <input type="text" placeholder="Search tasks..."
                            class="w-[20%] h-fit  rounded-md border border-gray-200 focus:outline-none focus:ring-2 focus:ring-gray-200 placeholder-gray-400">
                    </span>
                </div>
            </div>
        </div>
</template>
<script setup>

</script>