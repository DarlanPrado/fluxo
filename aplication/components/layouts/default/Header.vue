<template>
    <header class="w-full h-16 dark:bg-gray-800 bg-gray-100 px-5  border-b-2 dark:border-gray-700 border-gray-200">
        <div class="w-full h-full flex items-center justify-between">
            <div>
                <NuxtLink to="/">
                    <h1 class="text-3xl font-bold text-primary-500">Fluxo</h1>
                </NuxtLink>
            </div>
            <div>
                <ChangeThemeMode />
            </div>
        </div>
    </header>
</template>