<script setup>

const props = defineProps(['name', 'age', 'location'])
</script>

<template>
    <h1> {{ props.name }} -- {{ props.age }} -- {{ props.location }}</h1>
</template>