<template>
<UContainer>
    
    <UCard class="mt-10">
        <div class="flex justify-between">
          <h1 class="text-xl font-large"><b>Fotohaven</b></h1>
          <NuxtLink to="/">Home</NuxtLink>
          <ColorScheme><USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" /></ColorScheme>
        </div>
    </UCard>
    <UCard class="mt-10">
      <UAlert
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
