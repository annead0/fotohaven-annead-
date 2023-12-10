
<template>
<UContainer>
    <h1 style="text-decoration:underline; text-align:center;"><b>Fotohaven</b></h1>
    <UCard class="mt-10">
        <div class="flex justify-between">
          <ColorScheme><USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" /></ColorScheme>
        </div>
    </UCard>
  </UContainer>
</template>
<style>
#title{
  text-decoration:underline;
  text-align:center;
  font-weight:bold;
}
</style>