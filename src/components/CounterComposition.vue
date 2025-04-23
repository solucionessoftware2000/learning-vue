<script lang="ts">
import { defineComponent, ref } from 'vue';
export default defineComponent({
    name: 'CounterComposition',
    components: {},
    setup(){
        let counter = ref(0)
        const addCounter = ():void => {
            counter.value++
        }
        return{
            counter,
            addCounter
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
