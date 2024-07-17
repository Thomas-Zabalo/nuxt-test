<template>
    <div class="l-content">
        <section class="">
            <div class="container mx-auto px-6 py-16 text-center">
                <span class="border border-green-300 px-3 py-1 rounded-full">Salut !</span>
                <h1 class="text-4xl font-bold text-gray-200">Simplifiez votre gestion avec notre solution SaaS</h1>
                <p class="mt-4 text-gray-400">Automatisez vos tâches, améliorez votre productivité et optimisez vos
                    processus métiers.</p>
                <a href="#"
                    class="focus:outline-none focus-visible:outline-0 disabled:cursor-not-allowed disabled:opacity-75 flex-shrink-0 font-medium rounded-md text-sm gap-x-2 px-3 py-2 shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 disabled:bg-gray-50 dark:bg-gray-800 dark:hover:bg-gray-700/50 dark:disabled:bg-gray-800 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400 inline-flex items-center">Découvrir</a>
            </div>
        </section>

        <!-- Features Section -->
        <section class="container mx-auto px-6 py-16">
            <div class="text-center">
                <h2 class="text-3xl font-bold text-gray-200">Fonctionnalités</h2>
                <p class="mt-4 text-gray-400">Découvrez ce que notre solution peut faire pour vous</p>
            </div>
            <div class="mt-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div
                    class="p-6 rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 disabled:bg-gray-50 dark:bg-gray-800 dark:hover:bg-gray-700/50 dark:disabled:bg-gray-800 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
                    <h3 class="text-xl font-semibold text-white">Automatisation</h3>
                    <p class="mt-2 text-gray-400">Automatisez les tâches répétitives pour gagner du temps et de
                        l'efficacité.</p>
                </div>
                <div
                    class="p-6 rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 disabled:bg-gray-50 dark:bg-gray-800 dark:hover:bg-gray-700/50 dark:disabled:bg-gray-800 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
                    <h3 class="text-xl font-semibold text-white">Collaboration</h3>
                    <p class="mt-2 text-gray-400">Collaborez facilement avec votre équipe grâce à nos outils intégrés.
                    </p>
                </div>
                <div
                    class="p-6 rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 disabled:bg-gray-50 dark:bg-gray-800 dark:hover:bg-gray-700/50 dark:disabled:bg-gray-800 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
                    <h3 class="text-xl font-semibold text-white">Analytique</h3>
                    <p class="mt-2 text-gray-400">Obtenez des insights précieux avec nos outils d'analyse avancés.</p>
                </div>
            </div>
        </section>

        <!-- Pricing Section -->
        <section class="">
            <div class="container mx-auto px-6 py-16 text-center">
                <h2 class="text-3xl font-bold text-gray-200">Tarifs</h2>
                <p class="mt-4 text-gray-400">Choisissez le plan qui vous convient le mieux</p>
                <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="flex flex-col justify-between  p-6 rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700/50 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
                    <div>
                        <h3 class="text-xl font-semibold text-white">Basique</h3>
                        <p class="mt-2 text-gray-600 font-bold">€9/mois</p>
                        <ul class="mt-4 text-gray-600 text-left">
                            <li class="mt-2">Jusqu'à 5 utilisateurs</li>
                            <li class="mt-2">Automatisation des tâches de base</li>
                            <li class="mt-2">1 GB de stockage</li>
                            <li class="mt-2">Support par email</li>
                        </ul>
                    </div>
                    <div class="mt-6 flex-grow flex items-end">
                        <a href="#" class="bg-green-500 hover:bg-green-300 text-white px-4 py-2 rounded w-full text-center">Souscrire</a>
                    </div>
                </div>
                <div class="flex flex-col justify-between  p-6 rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700/50 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
                    <div>
                        <h3 class="text-xl font-semibold text-white">Standard</h3>
                        <p class="mt-2 text-gray-600 font-bold">€29/mois</p>
                        <ul class="mt-4 text-gray-600 text-left">
                            <li class="mt-2">Jusqu'à 20 utilisateurs</li>
                            <li class="mt-2">Automatisation avancée</li>
                            <li class="mt-2">10 GB de stockage</li>
                            <li class="mt-2">Support par email et chat</li>
                            <li class="mt-2">Accès aux intégrations tierces</li>
                        </ul>
                    </div>
                    <div class="mt-6 flex-grow flex items-end">
                        <a href="#" class="bg-green-500 hover:bg-green-300 text-white px-4 py-2 rounded w-full text-center">Souscrire</a>
                    </div>
                </div>
                <div class="flex flex-col justify-between  p-6 rounded-md shadow-sm ring-1 ring-inset ring-gray-300 dark:ring-gray-700 text-gray-700 dark:text-gray-200 bg-gray-50 hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700/50 focus-visible:ring-2 focus-visible:ring-primary-500 dark:focus-visible:ring-primary-400">
                    <div>
                        <h3 class="text-xl font-semibold text-white">Premium</h3>
                        <p class="mt-2 text-gray-600 font-bold">€49/mois</p>
                        <ul class="mt-4 text-gray-600 text-left">
                            <li class="mt-2">Utilisateurs illimités</li>
                            <li class="mt-2">Automatisation complète</li>
                            <li class="mt-2">Stockage illimité</li>
                            <li class="mt-2">Support prioritaire 24/7</li>
                            <li class="mt-2">Accès aux fonctionnalités bêta</li>
                            <li class="mt-2">Analytique avancée</li>
                        </ul>
                    </div>
                    <div class="mt-6 flex-grow flex items-end">
                        <a href="#" class="bg-green-500 hover:bg-green-300 text-white px-4 py-2 rounded w-full text-center">Souscrire</a>
                    </div>
                </div>
            </div>
            </div>
        </section>
    </div>
</template>
<script setup>

</script>

<style scoped>
.l-content {
    padding-inline: 32px;
    margin-inline: auto;
}

h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

p {
    margin: 20px 0;
}
</style>