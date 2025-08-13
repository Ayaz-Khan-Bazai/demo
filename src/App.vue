<script setup>
import HelloWorld from './components/HelloWorld.vue'
import reactiveRef from './components/reactiveRef.vue'
import Watchers from './components/Watchers.vue'
import { ref } from 'vue'
const isDark = ref(false)

</script>

<template>

  <Watchers />
  <!-- <reactiveRef /> -->

</template>

<style>
body {
  margin-top: 100px;
}
</style>
