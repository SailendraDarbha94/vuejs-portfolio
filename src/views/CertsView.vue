<script setup lang="ts">
import Certificates from '../components/MyCertificates.vue'
</script>

<template>
  <main>
    <nav class="flex justify-center mt-2 top-0 left-0 fixed w-full shadow-xl pb-2">
        <RouterLink to="/" class="mx-2 p-2 w-40 text-center rounded-lg bg-slate-200 font-semibold text-black hover:bg-yellow-300">Home</RouterLink>
        <RouterLink to="/blog" class="mx-2 p-2 w-40 text-center rounded-lg bg-slate-200 text-black font-semibold hover:bg-yellow-300">Blog</RouterLink>
    </nav>
    <Certificates />
  </main>
</template>
