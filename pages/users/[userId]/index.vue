<script setup>
const route = useRoute();
</script>

<template>
    <h1>User - {{ route.params.userId }}</h1>
</template>
