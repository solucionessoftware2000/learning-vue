<script setup lang="ts">
import PostCard from './PostCard.vue';
</script>

<template>
    <h1 class="post-head">Listado de posts:</h1>
    <div class="post-container">
        <PostCard/>
        <PostCard/>
        <PostCard/>
        <PostCard/>
    </div>
</template>

<style scoped>
.post-head{
    color: white;
}
</style>
