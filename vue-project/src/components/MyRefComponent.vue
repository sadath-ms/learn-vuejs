<script setup>
import { ref } from "vue"

let count = ref(0)
let names = ref(['abc', 'cde'])

</script>

<template>
  <h1> Count : {{ count }}</h1>
  <button @click="count++"> + </button>
  <button @click="count--"> - </button>

  <h1> Names : {{ names }}</h1>
  <button @click="names.push('sadath')"> Add Name </button>



</template>