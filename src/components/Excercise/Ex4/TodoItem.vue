<script setup lang="ts">
const emit = defineEmits(['delete']);

const props =  defineProps ({
  todo: {
    type: Object as () => {id: number, name: string },
    required: true
  }
})

const handleDelte = () => {
  emit('delete')
}

</script>

<template>
  <span>{{ props.todo.title }}</span>
  <button @click="handleDelete">Delete</button>
</template>

<style scoped>

</style>