<script setup>
import { ref } from 'vue';

const formData = ref(
    {'username': '', 'password': ''}
)
</script>

<template>
    <form>
        <div>
            <input type="text" placeholder="Username" v-model="formData.username">
            <input type="password" placeholder="Password" v-model="formData.password">
            <button type="submit">Submit</button>
        </div>
    </form>

    <h1>{{ formData.username }} ---  {{ formData.password }}</h1>
</template>