<script setup>
import PostList from "../components/PostList.vue";
</script>

<template>
    <div>
        <h1>All Posts</h1>
        <PostList />
        <h2> Recent Posts </h2>
        <PostList />
    </div>
</template>

<style scoped>
    h2 {
        color: blue;
    }
</style>
