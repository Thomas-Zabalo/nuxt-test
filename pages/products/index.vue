<template>
    <div>
        <h2>Product</h2>
        <p>Nostrud occaecat fugiat excepteur eiusmod laboris incididunt non veniam. Proident Lorem excepteur cillum sunt
            commodo esse. Lorem ad sunt non quis laboris sint excepteur ex ullamco. Ex pariatur ex aute sint Lorem magna
            est do ad aliquip ullamco fugiat qui. Ut reprehenderit nisi amet veniam adipisicing reprehenderit excepteur
            incididunt adipisicing id do ex veniam cillum. Culpa id velit esse amet nulla. Ullamco elit ullamco do ipsum
            elit nisi ipsum id amet incididunt eu anim enim ut.
        </p>
        <p>Nostrud occaecat fugiat excepteur eiusmod laboris incididunt non veniam. Proident Lorem excepteur cillum sunt
            commodo esse. Lorem ad sunt non quis laboris sint excepteur ex ullamco. Ex pariatur ex aute sint Lorem magna
            est do ad aliquip ullamco fugiat qui. Ut reprehenderit nisi amet veniam adipisicing reprehenderit excepteur
            incididunt adipisicing id do ex veniam cillum. Culpa id velit esse amet nulla. Ullamco elit ullamco do ipsum
            elit nisi ipsum id amet incididunt eu anim enim ut.
        </p>
    </div>
</template>

<script setup>
definePageMeta({
    layout: 'product'
})

await useFetch('https://fakestoreapi.com/products')

window
</script>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

p {
    margin: 20px 0;
}
</style>