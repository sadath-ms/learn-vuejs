<script setup>

import staticPorpsComp from "./components/staticPorpsComp.vue";
import dynamicPropsComponents from "./components/dynamicPropsComponents.vue";

let name = 'sadath'
let age = '26'
let location = 'bangalore'

</script>

<template>
  <staticPorpsComp name="sadath"/>
  <hr/>
  <dynamicPropsComponents :name="name" :age="age" :location="location"/>

</template>









<!-- <script setup>
import MyEvent from "./components/MyEvent.vue";
</script>

<template>
  <h1>clock</h1>
  <MyEvent/>
</template>

<style scoped></style> -->



<!-- 
<script setup>
import HelloWorld from "./components/HelloWorld.vue";
console.log("coming here.....");
const myName = "sadath";
const githubLink = "https://github.com/sadath-ms/learn-vuejs/tree/dev"

const silverImage = "https://storage.googleapis.com/erp-revamp/awards/silver.jpeg"
const altText = "Just a random image"
const imageWidth = 150
const imageHeight = 150

// Dynamic binding 

const imageInfo = {
  src: silverImage,
  alt: altText,
  width: imageWidth,
  height: imageHeight
}


function add (x, y) {
  return x + y
}
</script>

<template>
  <h1>Login In : {{ myName }}</h1>
  <h2>Vue APP</h2>
  <HelloWorld />
  <h4>Sum of two numbers is: {{ add(3,2) }}</h4>

  <a :href="githubLink"> github</a>
  <br>
  <img :src="silverImage" :alt="altText" :width="imageWidth" :height="imageHeight" />
  <img :="imageInfo" />



</template> 

<style scoped>
  h1 {
    color:green;
    background-color: black;
  }
</style> -->