<script setup lang='ts'>

</script>

<template>
  <div class="relative w-580px h-580px bg-#BBADA0 rounded-1 flex flex-wrap gap-20px p-20px ">
    <BaseBox v-for="n in 16" :key="n" />
    <GameOverOverlay />
  </div>
</template>

<style>

</style>
