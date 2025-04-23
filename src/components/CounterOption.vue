<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'CounterOption',
    components: {},
    data(){
        let counter: number = 0;
        return {counter}
    },
    methods:{
        addCounter(){
            this.counter++
        }
    }
})
</script>

<template>
    <h3>{{ counter }}</h3>
    <button @click="addCounter">Incrementar</button>
</template>

<style scoped>
</style>
