<script setup lang="ts">
defineProps({
  text: {
    type: String,
    required: true
  }
})
</script>

<template>
<h2>{{text}}</h2>
</template>

<style scoped>

</style>