<template>
    <div>
        <div
            class="flex flex-col justify-between p-3 h-full rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700/50 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
            <div>
                <h3 class="text-xl font-semibold text-white truncate">{{ product.title }}</h3>
                <img :src="product.image" alt="Product thumb" class=" thumb">
                <p class="font-bold text-gray-500 m-4 truncate ">{{ product.description }}</p>
                <NuxtLink :to="`/products/${product.id}`">
                    <p class="bg-green-500 hover:bg-green-300 text-white px-4 py-2 rounded w-full text-center">View
                        details
                    </p>
                </NuxtLink>
            </div>
        </div>
    </div>

</template>

<script setup>
// Call props as array
const { product } = defineProps(['product'])
</script>

<style scoped>
.thumb {
    max-height: 120px;
    max-width: 70%;
    margin: 0 auto;
}
</style>