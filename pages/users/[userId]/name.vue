<script setup>
const route = useRoute();
</script>

<template>
    <h1>{{ route.params.userId }}</h1>
</template>