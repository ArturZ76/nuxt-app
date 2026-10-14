<template>
    <div>
        <h1>Hello About</h1>
        <nuxt-link to="/">Home</nuxt-link>
        {{ counter }}
    </div>
</template>

<script setup lang="ts">
const counter = useState<number>('count', () => 0)
</script>

<style scoped></style>