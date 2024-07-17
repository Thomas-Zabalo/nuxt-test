<template class="l-body">
    <div class="bg-slate-900">
        <Header />
        <!-- Page content -->
        <div class="l-main mx-auto max-w-5xl">
            <slot />
        </div>
        <Footer />
    </div>
</template>


<style>
body {
    color: white;
}

.l-body {
    margin-inline: 64px;
}

.l-main {
    margin-block-start: 64px;
}
</style>
