<script setup lang="ts">
useHead({
  title:'Fotohaven'
})
</script>
<template>
<UContainer>
    
    <UCard class="mt-10">
        <div class="flex justify-between">
          <h1 class="text-xl font-large"><b>Fotohaven</b></h1>
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink>About</NuxtLink>
          <NuxtLink>Photosearch</NuxtLink>
          <NuxtLink to="https://annead.vercel.app">Annead</NuxtLink>
          <ColorScheme><USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" /></ColorScheme>
        </div>
    </UCard>
    <UCard class="mt-10">
      <UAlert class="text-center"
  icon="i-heroicons-command-line"
  color="sky"
  variant="solid"
  title="Website in early Development!"
/>

      <NuxtPage/>
    </UCard>
  </UContainer>
</template>
<style>
@tailwind base;
</style>
