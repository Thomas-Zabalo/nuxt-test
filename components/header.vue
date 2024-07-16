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
            </nav>
        </header>
    </div>
</template>

<script setup>

</script>

<style scoped></style>
