<script setup>
import { ref , defineProps} from 'vue'
const Prop = defineProps(["name" , "card"])
</script>

<template>
<div class=" m-auto rounded-2xl border-t-4 border-b-4 justify-self-center border-red-500 flex justify-center flex-col flex-wrap gap-4 items-center w-[400px] bg-amber-200 p-5">
  <img class="w-[100px] rounded-4xl border-8 border-gray-300 " src="https://images.contentstack.io/v3/assets/bltcedd8dbd5891265b/blt5f18c2119ce26485/6668df65db90945e0caf9be6/beautiful-flowers-lotus.jpg?q=70&width=3840&auto=webp" alt="">
  <h1 class=" text-2xl">{{ name }} {{ card }}</h1>
  <h2>Hello p 1 </h2>
  <p class=" w-[300px]">Lorem ipsum dolor, sit amet consectetur adipisicing elit.Lorem ipsum dolor, sit amet consectetur adipisicing elit.Lot.</p>
</div>
</template>
