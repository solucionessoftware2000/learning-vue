<script setup lang="ts">
import { ref, type Ref } from 'vue';

const countries:Ref<Array<string>> = ref([
    'Spain', 'France', 'UK', 'Italy', 'Portugal'
])
</script>

<template>
    <ul>
        <li v-for="country in countries" :key="country">{{ country }}</li>
    </ul>
</template>

<style scoped>
</style>
