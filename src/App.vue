<script setup>
import { computed, ref } from 'vue';
import { BLOG_DATA } from './data'
import BlogList from './components/BlogList.vue'
</script>
<template>
  <div>
    <h1 class="p-6 text-3xl font-bold text-center">Vue 3 Component with props</h1>
    <div class="max-w-5xl mx-auto ">
      <h2 class="text-3xl font-bold text-center">My Blog</h2>
      <BlogList :data="BLOG_DATA" />
    </div>
  </div>
</template>