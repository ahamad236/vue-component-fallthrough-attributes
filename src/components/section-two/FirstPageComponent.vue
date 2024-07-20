<template>
    <h2>
        First Page Component
    </h2>
    <button v-bind="$attrs">Submit</button>
</template>
<script setup lang="ts">
    defineOptions({
        inheritAttrs: false
    })
</script>