<script setup lang='ts'>
const show = ref(false)
</script>

<template>
  <div v-show="show" class="absolute flex flex-col items-center justify-center left-0 right-0 top-0 bottom-0 bg-[#dddddd]/50 text-[55px] font-bold rounded-1">
    <p class="text-[#666]">
      Game Over
    </p>
    <button class="text-[#fff] text-[20px] font-bold rounded-1 bg-[#876] h-[40px] w-[200px]">
      Try Again
    </button>
  </div>
</template>

<style>

</style>
