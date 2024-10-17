<script setup lang="ts">
defineProps({
  content: {
    type: Object,
    required: true,
  }

})
</script>

<template>
<h2>{{content}}</h2>
</template>

<style scoped>

</style>