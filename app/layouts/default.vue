<template class="l-body">
    <div class="bg-slate-900">
        <Header />
        <!-- Page content -->
        <div class="l-content mx-auto max-w-3xl">
            <slot />
        </div>
    </div>
</template>


<style>
.l-body {
    margin-inline: 64px;
}

.l-main {
    margin-block-start: 64px;
}
</style>