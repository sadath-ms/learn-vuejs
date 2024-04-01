<script setup>

const props = defineProps(['name'])

console.log(props, 'props is:--')

</script>

<template>
    <h1> props is: {{props.name}}</h1>
</template>