<template>
  <input type="text" v-model="author.name" />
  <div>
    <Blog />
  </div>
</template>

<script setup lang="ts">
import { provide, reactive, readonly } from 'vue';
import Blog from './Blog.vue';
</script>

<style scoped lang="scss"></style>
