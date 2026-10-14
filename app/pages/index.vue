<template>
  <div>
    <h1 class="text-4xl font-black">Hello Home Page</h1>

    <nuxt-link to="/about">About</nuxt-link>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'My second nuxt website'
})
</script>

<style scoped></style>