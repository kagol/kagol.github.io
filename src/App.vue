<script setup lang="ts">
import Hello from './components/Hello.vue'
</script>

<template>
  <div>
    <a href="https://kagol.gitee.io/blogs/" target="_blank">
      <img src="/image.jpg" class="logo" alt="Kagol logo" />
    </a>
  </div>
  <Hello msg="Hello Kagol" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #eaea9e);
}
</style>
