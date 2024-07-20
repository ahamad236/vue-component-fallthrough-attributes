<template>
    <h1>
        Home Component
    </h1>
    <FirstPage class="container" @click="parentClick"></FirstPage>
</template>

<script setup lang="ts">
    import FirstPage from "./FirstPageComponent.vue"

    function parentClick(){
        alert('parent Click')
    }
</script>