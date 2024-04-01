<script setup>
import { ref } from 'vue';

let names = ref(
    ['one', 'two', 'three']
)
</script>

<template>
    <h1> Iteration elements is:---</h1>
    <p v-for="(person, index) in names" :key="index">{{ person }} </p>
</template>