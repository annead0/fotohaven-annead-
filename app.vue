<script>
const details={
  title:"Fotohaven"
}
</script>
<template>
<UContainer>
  <template #header>
    <h1 style="text-decoration:underline; text-align:center;"><b>{{details.title}}</b></h1>
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