<script setup lang="ts">
const emit = defineEmits(['increment'])
const handleEmit = () => {
  emit('increment')
}
</script>

<template>
<button @click="handleEmit">
  Tang
</button>
</template>

<style scoped>

</style>