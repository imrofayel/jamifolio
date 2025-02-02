<template>
  <ClientOnly>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </ClientOnly>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(async () => {
  await import('lenis/dist/lenis.css');
  const { default: Lenis } = await import('lenis');
  const lenis = new Lenis();

  function raf(time: number) {
    lenis.raf(time);
    requestAnimationFrame(raf);
  }

  requestAnimationFrame(raf);
});
</script>
