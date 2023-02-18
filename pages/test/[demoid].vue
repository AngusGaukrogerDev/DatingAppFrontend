<template>
    <div class="h-screen w-full flex flex-col justify-center items-center ">
        Demo ID is: {{ demoid }}
    </div>
</template>

<script setup>
const { demoid } = useRoute().params;

definePageMeta({
    layout: 'test'
})
</script>

<style lang="scss" scoped>

</style>