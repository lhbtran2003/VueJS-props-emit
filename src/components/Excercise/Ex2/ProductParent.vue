<script setup lang="ts">
import ProductChildren from "./ProductChildren.vue";

const object = {
  id: 1,
  name: 'btran qua xa na de huong'
}
</script>

<template>
<ProductChildren :content="object"/>
</template>

<style scoped>

</style>