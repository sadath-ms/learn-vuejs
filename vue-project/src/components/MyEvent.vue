<script setup>

// import { ref } from 'vue';

// let count = ref(0)

// const incrementCounter = () => count.value++
// const decrementCounter = () => count.value--


const submitHandler = (e) => {
    e.preventDefault()
    alert('Successfully submitted the form')
}
 

</script>

<template>
    <!-- <h1> Total Clicks : {{ count }} </h1>
    <button @:click="incrementCounter"> Increment </button>
    <button @:click="decrementCounter"> Decrement </button> -->
    <form @:submit="submitHandler">
        <input type="text" placeholder="Enter Username" />
        <input type="text" placeholder="Enter Email" />
        <button type="submit"> Submit </button>


    </form>
</template>

<style scoped>
</style>