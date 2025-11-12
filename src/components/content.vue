<template>
  <RouterView />
   <!-- main/task cards container -->
            <div id="main-content" class="md:grid md:grid-cols-5 gap-2 p-4  bg-gray-200 w-full h-full overflow-y-auto mt-2">
                <div id="new-todo">
                    <div class="task-label bg-orange-500 text-white py-1 px-2 rounded-t-md mb-2">
                        <p class="flex justify-between">
                            <span class="text-[12px]">New Task</span>
                            <span
                                class="bg-white w-5 h-5 text-black rounded-full shadow-2xl text-center text-xs p-1">4</span>
                        </p>
                    </div>

                    <!-- card detail -->
                    <div class="px-1">
                        <div id="task-card"
                            class="bg-white rounded-b shadow-md p-1 mb-4 border-t-2 border-t-orange-500">
                            <!-- card header -->
                            <p class="flex justify-between p-1 mb-2">
                                <span class="text-[10px] font-bold">Task 001</span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                    stroke-width="1.5" stroke="currentColor" class="size-6 w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5" />
                                </svg>
                            </p>
                            <!-- card details -->
                            <p class="task-detail flex justify-between mb-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                    </svg>

                                </span>
                                <span class="flex gap-2 items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M9 12.75 11.25 15 15 9.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="m18.375 12.739-7.693 7.693a4.5 4.5 0 0 1-6.364-6.364l10.94-10.94A3 3 0 1 1 19.5 7.372L8.552 18.32m.009-.01-.01.01m5.699-9.941-7.81 7.81a1.5 1.5 0 0 0 2.112 2.13" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
                                    </svg>
                                </span>
                            </p>
                            <!-- refrence task -->
                            <p class="flex justify-between">
                                <span class="text-gray-500 text-[8px] font-bold">
                                    Task-101
                                </span>
                                <span class="text-[8px] font-light">17-OCT-2025</span>
                            </p>
                            <p class="flex gap-1 mt-2">
                                <span class="w-2 h-[2px] bg-green-500"></span>
                                <span class="w-2 h-[2px] bg-blue-500"></span>
                                <span class="w-2 h-[2px] bg-orange-500"></span>
                                <span class="w-2 h-[2px] bg-red-500"></span>
                            </p>
                        </div>
                    </div>
                </div>
                <div id="not-started">
                    <div class="task-label bg-orange-500 text-white py-1 px-2 rounded-t-md mb-2">
                        <p class="flex justify-between">
                            <span class="text-[12px]">New Task</span>
                            <span
                                class="bg-white w-5 h-5 text-black rounded-full shadow-2xl text-center text-xs p-1">4</span>
                        </p>
                    </div>

                    <!-- card detail -->
                    <div class="px-1">
                        <div id="task-card"
                            class="bg-white rounded-b shadow-md p-1 mb-4 border-t-2 border-t-orange-500">
                            <!-- card header -->
                            <p class="flex justify-between p-1 mb-2">
                                <span class="text-[10px] font-bold">Task 001</span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                    stroke-width="1.5" stroke="currentColor" class="size-6 w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5" />
                                </svg>
                            </p>
                            <!-- card details -->
                            <p class="task-detail flex justify-between mb-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                    </svg>

                                </span>
                                <span class="flex gap-2 items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M9 12.75 11.25 15 15 9.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="m18.375 12.739-7.693 7.693a4.5 4.5 0 0 1-6.364-6.364l10.94-10.94A3 3 0 1 1 19.5 7.372L8.552 18.32m.009-.01-.01.01m5.699-9.941-7.81 7.81a1.5 1.5 0 0 0 2.112 2.13" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
                                    </svg>
                                </span>
                            </p>
                            <!-- refrence task -->
                            <p class="flex justify-between">
                                <span class="text-gray-500 text-[8px] font-bold">
                                    Task-101
                                </span>
                                <span class="text-[8px] font-light">17-OCT-2025</span>
                            </p>
                            <p class="flex gap-1 mt-2">
                                <span class="w-2 h-[2px] bg-green-500"></span>
                                <span class="w-2 h-[2px] bg-blue-500"></span>
                                <span class="w-2 h-[2px] bg-orange-500"></span>
                                <span class="w-2 h-[2px] bg-red-500"></span>
                            </p>
                        </div>
                    </div>
                </div>
                <div id="in-progress">
                    <div class="task-label bg-orange-500 text-white py-1 px-2 rounded-t-md mb-2">
                        <p class="flex justify-between">
                            <span class="text-[12px]">New Task</span>
                            <span
                                class="bg-white w-5 h-5 text-black rounded-full shadow-2xl text-center text-xs p-1">4</span>
                        </p>
                    </div>

                    <!-- card detail -->
                    <div class="px-1">
                        <div id="task-card"
                            class="bg-white rounded-b shadow-md p-1 mb-4 border-t-2 border-t-orange-500">
                            <!-- card header -->
                            <p class="flex justify-between p-1 mb-2">
                                <span class="text-[10px] font-bold">Task 001</span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                    stroke-width="1.5" stroke="currentColor" class="size-6 w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5" />
                                </svg>
                            </p>
                            <!-- card details -->
                            <p class="task-detail flex justify-between mb-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                    </svg>

                                </span>
                                <span class="flex gap-2 items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M9 12.75 11.25 15 15 9.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="m18.375 12.739-7.693 7.693a4.5 4.5 0 0 1-6.364-6.364l10.94-10.94A3 3 0 1 1 19.5 7.372L8.552 18.32m.009-.01-.01.01m5.699-9.941-7.81 7.81a1.5 1.5 0 0 0 2.112 2.13" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
                                    </svg>
                                </span>
                            </p>
                            <!-- refrence task -->
                            <p class="flex justify-between">
                                <span class="text-gray-500 text-[8px] font-bold">
                                    Task-101
                                </span>
                                <span class="text-[8px] font-light">17-OCT-2025</span>
                            </p>
                            <p class="flex gap-1 mt-2">
                                <span class="w-2 h-[2px] bg-green-500"></span>
                                <span class="w-2 h-[2px] bg-blue-500"></span>
                                <span class="w-2 h-[2px] bg-orange-500"></span>
                                <span class="w-2 h-[2px] bg-red-500"></span>
                            </p>
                        </div>
                    </div>
                </div>
                <div id="under-review">
                    <div class="task-label bg-orange-500 text-white py-1 px-2 rounded-t-md mb-2">
                        <p class="flex justify-between">
                            <span class="text-[12px]">New Task</span>
                            <span
                                class="bg-white w-5 h-5 text-black rounded-full shadow-2xl text-center text-xs p-1">4</span>
                        </p>
                    </div>

                    <!-- card detail -->
                    <div class="px-1">
                        <div id="task-card"
                            class="bg-white rounded-b shadow-md p-1 mb-4 border-t-2 border-t-orange-500">
                            <!-- card header -->
                            <p class="flex justify-between p-1 mb-2">
                                <span class="text-[10px] font-bold">Task 001</span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                    stroke-width="1.5" stroke="currentColor" class="size-6 w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5" />
                                </svg>
                            </p>
                            <!-- card details -->
                            <p class="task-detail flex justify-between mb-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                    </svg>

                                </span>
                                <span class="flex gap-2 items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M9 12.75 11.25 15 15 9.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="m18.375 12.739-7.693 7.693a4.5 4.5 0 0 1-6.364-6.364l10.94-10.94A3 3 0 1 1 19.5 7.372L8.552 18.32m.009-.01-.01.01m5.699-9.941-7.81 7.81a1.5 1.5 0 0 0 2.112 2.13" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
                                    </svg>
                                </span>
                            </p>
                            <!-- refrence task -->
                            <p class="flex justify-between">
                                <span class="text-gray-500 text-[8px] font-bold">
                                    Task-101
                                </span>
                                <span class="text-[8px] font-light">17-OCT-2025</span>
                            </p>
                            <p class="flex gap-1 mt-2">
                                <span class="w-2 h-[2px] bg-green-500"></span>
                                <span class="w-2 h-[2px] bg-blue-500"></span>
                                <span class="w-2 h-[2px] bg-orange-500"></span>
                                <span class="w-2 h-[2px] bg-red-500"></span>
                            </p>
                        </div>
                    </div>
                </div>
                <div id="completed">
                    <div class="task-label bg-orange-500 text-white py-1 px-2 rounded-t-md mb-2">
                        <p class="flex justify-between">
                            <span class="text-[12px]">New Task</span>
                            <span
                                class="bg-white w-5 h-5 text-black rounded-full shadow-2xl text-center text-xs p-1">4</span>
                        </p>
                    </div>

                    <!-- card detail -->
                    <div class="px-1">
                        <div id="task-card"
                            class="bg-white rounded-b shadow-md p-1 mb-4 border-t-2 border-t-orange-500">
                            <!-- card header -->
                            <p class="flex justify-between p-1 mb-2">
                                <span class="text-[10px] font-bold">Task 001</span>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                    stroke-width="1.5" stroke="currentColor" class="size-6 w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5" />
                                </svg>
                            </p>
                            <!-- card details -->
                            <p class="task-detail flex justify-between mb-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                    </svg>

                                </span>
                                <span class="flex gap-2 items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M9 12.75 11.25 15 15 9.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="m18.375 12.739-7.693 7.693a4.5 4.5 0 0 1-6.364-6.364l10.94-10.94A3 3 0 1 1 19.5 7.372L8.552 18.32m.009-.01-.01.01m5.699-9.941-7.81 7.81a1.5 1.5 0 0 0 2.112 2.13" />
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6 w-3 h-3">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
                                    </svg>
                                </span>
                            </p>
                            <!-- refrence task -->
                            <p class="flex justify-between">
                                <span class="text-gray-500 text-[8px] font-bold">
                                    Task-101
                                </span>
                                <span class="text-[8px] font-light">17-OCT-2025</span>
                            </p>
                            <p class="flex gap-1 mt-2">
                                <span class="w-2 h-[2px] bg-green-500"></span>
                                <span class="w-2 h-[2px] bg-blue-500"></span>
                                <span class="w-2 h-[2px] bg-orange-500"></span>
                                <span class="w-2 h-[2px] bg-red-500"></span>
                            </p>
                        </div>
                    </div>
                </div>
            </div>
  </template>