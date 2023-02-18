<template>
    <div>
        <header>
            <nav class="w-full fixed flex flex-row justify-between items-center px-10 py-6 bg-green-200">
                <NuxtLink to="/"><h1 class=" font-semibold text-2xl">Nuxt Template</h1></NuxtLink>
                <ul class="flex flex-row justify-between gap-7 ">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/test/">Test</NuxtLink></li>
                    <li><NuxtLink to="/test/dummyvalue">Dummy Value example</NuxtLink></li>
                </ul>
            </nav>
        </header>
        <div class="w-100 h-screen bg-green-50">
            <slot />
        </div>
    </div>
</template>

<script setup>
definePageMeta({
    layout: 'test'
})
</script>

<style lang="scss" scoped>

</style>