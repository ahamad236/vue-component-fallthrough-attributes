<template>
    <h2 v-bind="attrs">
        Second Page Component
    </h2>
</template>
<script setup lang="ts">
    import { useAttrs } from "vue"

    const attrs = useAttrs()
</script>