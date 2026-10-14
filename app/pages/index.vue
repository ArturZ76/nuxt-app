<template>
  <div>
    <h1 class="text-4xl font-black">Hello Home Page</h1>
    <p>{{ counter }}</p>
    <button @click="counter++">Click</button>
    <nuxt-link to="/about">About</nuxt-link>
  </div>
</template>

<script setup lang="ts">

// const counter = ref(0) //it's local on page
const counter = useState<number>('count', () => 0)   //it will goes through whole app global - 


useHead({
  title: 'My second nuxt website'
})
</script>

<style scoped></style>