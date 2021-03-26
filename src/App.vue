<template>
  <NavBar />
  <main class="px-7 py-10">
    <router-view />
    <Footer />
  </main>
</template>

<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  meta: [
    { property: 'og:title', content: 'Daniel Lvovsky' },
    { property: 'og:image', content: 'https://daniellvovsky.com/avatar.png' },
    { name: 'description', content: 'Daniel Lvovsky\'s Portfolio' },
    { name: 'twitter:card', content: 'summary' },
    { name: 'twitter:creator', content: '@daniellvovsky' },
  ],
})
</script>
