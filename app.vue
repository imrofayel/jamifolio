<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup lang="ts">
import 'lenis/dist/lenis.css';
import { onMounted } from 'vue';

onMounted(async () => {
  const { default: Lenis } = await import('lenis');
  const lenis = new Lenis();

  function raf(time: number) {
    lenis.raf(time);
    requestAnimationFrame(raf);
  }

  requestAnimationFrame(raf);
});
</script>
