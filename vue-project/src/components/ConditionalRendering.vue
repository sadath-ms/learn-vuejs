
<script setup>
import { ref } from 'vue'

let isUserLoggedIn = ref(false)
let username = "ABCdef"

</script>
<template>
    <h1> Conditional Redering ....</h1>
    <div>
        <p v-if="isUserLoggedIn"> User Logged In : {{  username }}</p>
        <p v-else> Please login to access the content...  </p>
        <div>
            <p v-show="isUserLoggedIn"> Please access and modify the content</p>
        </div>
    </div>
</template>