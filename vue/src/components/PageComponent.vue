<template>
    <header class="bg-white shadow">
        <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
            <h1 class="text-3xl font-bold text-gray-900">{{ title }}</h1>
            <slot name="header"></slot>
        </div>
    </header>
    <main>
        <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
            <!-- Replace with your content -->
            <slot></slot>
            <!-- /End replace -->
        </div>
    </main>
</template>

<script setup>
const props = defineProps({
    title: String
})
</script>

<style lang="">
    
</style>