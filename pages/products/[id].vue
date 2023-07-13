<template>
    <div>
        <p> product details for {{ id }}</p>
        <p> hello word</p>
    </div>
</template>

<script setup>
    const {id} = useRoute().params
    definePageMeta({
        layout: 'products'
    })
</script>

<style lang="scss" scoped>

</style>
