<script setup>
import { reactive , ref } from 'vue';

let nums = reactive({
    b : 20,
    a : 10 
})
let {a} = nums
let {b} = nums
setTimeout(() => {
    a = 50;
    console.log(a);
    
}, 2000);

</script>


<template>

<div class=" text-5xl">{{ nums.a + b }}</div>

</template>