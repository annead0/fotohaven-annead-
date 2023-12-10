<template>
<UContainer>
    
    <UCard class="mt-10">
        <div class="flex justify-between">
          <h1 class="text-xl font-large text-black"><b>Fotohaven</b></h1>
          <ColorScheme><USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" /></ColorScheme>
        </div>
    </UCard>
    <UCard class="mt-10">
      <NuxtView/>
    </UCard>
  </UContainer>
</template>
<style>
@tailwind base;
</style>
