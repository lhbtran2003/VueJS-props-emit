<script setup lang="ts">
import ChildrenComponent from "./ChildrenComponent.vue";

const nameCompany = "Công ty TNHH một mình tao"
</script>

<template>
  <h1>
    {{ nameCompany }}
  </h1>
  <ChildrenComponent text="Công ty TNHH như cái chợ"/>
</template>

<style scoped>

</style>