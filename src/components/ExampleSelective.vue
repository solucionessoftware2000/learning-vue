<script setup lang="ts">
const age = 17
</script>

<template>
    <h1 v-if="age < 18">Eres menor de edad</h1>
    <h1 v-else>Eres mayor de edad</h1>
</template>

<style scoped>
</style>
