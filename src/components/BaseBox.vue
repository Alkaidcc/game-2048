<script setup lang='ts'>
defineProps({
  bgColor: {
    type: String,
    default: '#CDC1B4',
  },
})
</script>

<template>
  <div class="box">
    <slot />
  </div>
</template>

<style>
.box {
  @apply w-120px h-120px rounded-1 flex items-center justify-center;
  background-color: v-bind(bgColor);
}
</style>
