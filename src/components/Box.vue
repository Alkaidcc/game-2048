<script setup lang='ts'>
defineProps({
  title: {
    type: String,
    required: true,
  },
  bgColor: {
    type: String,
    required: true,
  },
  textColor: {
    type: String,
    default: '#F9F6F2',
  },
})
</script>

<template>
  <BaseBox :bg-color="bgColor" text-10>
    {{ title }}
  </BaseBox>
</template>

<style scoped>
.box {
  color: v-bind(textColor);
}
</style>
