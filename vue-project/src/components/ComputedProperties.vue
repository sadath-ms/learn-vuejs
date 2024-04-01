<script setup>
import { ref, computed} from 'vue';
let counterValue = ref(0)

const incrementCounter = () => {
  counterValue.value ++
}
const squaredCounter = computed(
  () => counterValue.value ** 2
)

</script>
<template>
  <h1> ----  Computed Proerties ---- </h1>
  <br/>

  <h2> Counter : {{ counterValue }}</h2>
  <h2> Squared Counter : {{ squaredCounter }}</h2>
  <button @click="incrementCounter"> + </button>
</template>