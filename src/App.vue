<script setup lang="ts">
// const BOX = {
//   2: {
//     title: '2',
//     bgColor: '#EEE4DA',
//     textColor: '#776E65',
//   },
//   4: {
//     title: '4',
//     bgColor: '#EDE0C8',
//     textColor: '#776E65',
//   },
//   8: {
//     title: '8',
//     bgColor: '#F2B179',
//     textColor: '#F9F6F2',
//   },
//   16: {
//     title: '16',
//     bgColor: '#F59563',
//     textColor: '#F9F6F2',
//   },
//   32: {
//     title: '32',
//     bgColor: '#F67C5F',
//     textColor: '#F9F6F2',
//   },
// }
</script>

<template>
  <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200" flex flex-wrap flex-col items-center justify-center>
    <!-- <Box title="2" bg-color="#EEE4DA" text-color="#776E65" />
    <Box title="4" bg-color="#EEE1C9" text-color="#776E65" />
    <Box title="8" bg-color="#F3B27A" />
    <Box title="16" bg-color="#F69664" />
    <Box title="32" bg-color="#F77C5F" />
    <BaseBox /> -->
    <Playground />
    <Footer />
  </main>
</template>
