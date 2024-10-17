<script setup lang="ts">
import Children from './Children.vue';


</script>
<template>
    <h1>Component Cha</h1>
    <Children :count='"hehe"'>
        <template #a>
           <div>
            hế lô
        </div>
        </template>
        <template #b>
            <div>
            chào các tục tưng
        </div>
        </template>
        
    </Children>

</template>
<style></style>