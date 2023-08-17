<script setup>
    defineProps({
        header: String,
        subHeader: String,
        msg: String
    })
</script>

<template>
    <h3>{{ subHeader }}</h3>
    <h1>{{ header }}</h1>
    <div class="card">{{ msg }}</div>
</template>

<style scoped>
    .card {
        padding: 41px 0 0 0;
        font-size: 40px;
        line-height: 1.5;
    }
</style>
