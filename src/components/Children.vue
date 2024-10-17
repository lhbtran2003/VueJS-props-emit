<script setup lang="ts">
defineProps({
    count: {
        type: String,
        required: true
    }
})
 
</script>
<template>
   <h1>Đây là component con</h1>
   <slot name="a"></slot>
   <h2>há há há</h2>
   <slot name="b"></slot>
</template>
<style></style>