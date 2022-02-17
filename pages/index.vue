<template lang="pug">
  div(@click="clickCount++") Current click count: {{ clickCount }}
    Tutorial
</template>

<script setup>
const clickCount = ref(0)
</script>
