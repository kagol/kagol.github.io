<script setup lang="ts">
import { blogUrl } from '../shared'

defineProps<{ msg: string }>()
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>「诚实和勤勉，应该成为你永久的伴侣。」</p>

  <p>
    我的博客：<a :href="blogUrl" target="_blank">{{ blogUrl }}</a>
  </p>
</template>

<style scoped>
h1 {
  background: -webkit-linear-gradient( 120deg, #bd34fe 30%, #41d1ff );
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent
}
</style>
