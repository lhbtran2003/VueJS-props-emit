<script setup lang="ts">
import {ref} from "vue";

const todoList = ref([
  {id: 1, name: a},
  {id: 2, name: b},
  {id: 3, name: c}
])
const handleDelete = (id: number) => {
  todoList.value = todoList.value.filter(todo => todo.id != id)
}
</script>

<template>
  <h1>TodoList</h1>
  <ul>
    <il :v-for="todo in todoList" :key="todo.id">
      <TodoItem @delete="handleDelete"/>

    </il>
  </ul>
</template>

<style scoped>

</style>