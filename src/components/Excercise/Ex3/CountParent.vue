<script setup lang="ts">
import {ref} from "vue";
import {c} from "vite/dist/node/types.d-aGj9QkWt";
import CountChildren from "./CountChildren.vue";
const  count = ref(0);
const incrementCount = () => {
  count.value++;
}
</script>

<template>
  <h1>Count: {{count}}</h1>
  <CountChildren @increment="incrementCount"/>
</template>

<style scoped>

</style>