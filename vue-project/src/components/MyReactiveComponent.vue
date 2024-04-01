<script setup>
import { reactive } from 'vue';

let instialState = reactive({ count: 0 })

</script>

<template>
  <h1> Count is : {{ instialState.count }}</h1>
  <button class="btn" @click="instialState.count++"> + </button>
  <button class="btn" @click="instialState.count--"> - </button>

</template>

<style scoped>
.btn {
  color: brown;
  background-color: blue;
}
</style>