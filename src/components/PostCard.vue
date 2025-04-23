<script setup lang="ts">
import PostButton from './PostButton.vue';
</script>

<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt culpa fuga accusantium aperiam voluptate aut sunt sit quia facere animi! Placeat ut itaque incidunt quos ipsa velit a provident at?</p>
        <PostButton/>
    </div>
</template>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #CCC;
}
</style>