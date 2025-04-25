<script setup lang="ts">
import { ref, type Ref } from 'vue';

interface ICountry {
    code: string,
    name: string
}

const countries:Ref<Array<ICountry>> = ref([
    {
        code: 'es',
        name: 'Spain'
    },
    {
        code: 'en',
        name: 'UK'
    },
    {
        code: 'fr',
        name: 'France'
    }
])
</script>

<template>
    <ul>
        <li v-for="country in countries" :key="country.code">{{ country.name }}</li>
    </ul>
</template>

<style scoped>
</style>
