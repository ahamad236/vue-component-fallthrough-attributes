<template>
    <button class="child-container" @click="childClick">
        First Page Component
    </button>
</template>

<script setup lang="ts">
    import SecondPage from "./SecondPageComponent.vue"
    function childClick(){
        alert('childClick called')
    }
</script>