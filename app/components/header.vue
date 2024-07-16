<template>
    <div>
        <header
            class="bg-slate-800 backdrop-blur border-b border-gray-200 dark:border-gray-800 -mb-px sticky top-0 z-50">
            <nav class="mx-auto px-4 sm:px-6 lg:px-8 max-w-7xl flex items-center justify-between gap-3 h-16">
                <div class="lg:flex-1 flex items-center gap-1.5">
                    <NuxtLink to="/"
                        class="flex-shrink-0 font-bold text-xl text-gray-900 dark:text-white flex items-end gap-1.5 hover:text-[#00dc82] transition duration-150"
                        aria-label="Nuxt Taskmaster" aria-current="page">Nuxt Taskmaster
                    </NuxtLink>
                </div>

                <ul class="items-center gap-x-8 hidden lg:flex">
                    <li class="relative">
                        <NuxtLink to="/dashboard"
                            class="text-sm/6 font-semibold flex items-center gap-1 hover:text-[#00dc82] text-gray-900 dark:text-white transition duration-150">
                            Dashboard</NuxtLink>
                    </li>
                    <li class="relative">
                        <NuxtLink to="/docs"
                            class="text-sm/6 font-semibold flex items-center gap-1 hover:text-[#00dc82] text-gray-900 dark:text-white transition duration-150">
                            Docs</NuxtLink>
                    </li>
                    <li class="relative">
                        <NuxtLink to="/blog"
                            class="text-sm/6 font-semibold flex items-center gap-1 hover:text-[#00dc82] text-gray-900 dark:text-white transition duration-150">
                            Blog</NuxtLink>
                    </li>
                </ul>

                <div class="lg:flex-1 flex items-center gap-1.5 justify-end">
                    <NuxtLink
                        class="focus:outline-none focus-visible:outline-0 disabled:cursor-not-allowed disabled:opacity-75 flex-shrink-0 font-medium rounded-md text-sm gap-x-2 px-3 py-2 shadow-sm text-white dark:text-gray-900 bg-gray-900 hover:bg-gray-800 disabled:bg-gray-900 dark:bg-white dark:hover:bg-gray-100 dark:disabled:bg-white focus-visible:ring-inset focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400 items-center hidden lg:flex"
                        to="/login">
                        <span class="">Sign in</span>
                    </NuxtLink>
                    <NuxtLink
                        class="focus:outline-none focus-visible:outline-0 disabled:cursor-not-allowed disabled:opacity-75 flex-shrink-0 font-medium rounded-md text-sm gap-x-2 px-3 py-2 shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 disabled:bg-gray-50 dark:bg-gray-800 dark:hover:bg-gray-700/50 dark:disabled:bg-gray-800 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400 inline-flex items-center"
                        to="/login">
                        <span class="">Get started</span>
                        <icon name="i-heroicons-arrow-right-20-solid" class="flex-shrink-0 h-5 w-5" aria-hidden="true" />
                    </NuxtLink>
                </div>
            </nav>
        </header>
    </div>
</template>

<script setup>

</script>

<style scoped></style>
