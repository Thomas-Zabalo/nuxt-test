<template>
    <div>
        <Header />

        <!-- Page content -->
        <div>
            <slot />
        </div>
    </div>
</template>

<style>
.router-link-exact-active {
    color: green;
}
</style>