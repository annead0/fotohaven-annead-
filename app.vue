<script setup>
const compName =ref("title");
</script>
<template>
<UContainer>
  <template #header>
    <h1 :class="compName">Fotohaven</h1>
    <UCard class="mt-10">
        <div class="flex justify-between">
          <ColorScheme><USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" /></ColorScheme>
        </div>
    </UCard>
    </template>
  </UContainer>
</template>
<style>
#title{
  text-decoration:underline;
  text-align:center;
  font-weight:bold;
}
</style>