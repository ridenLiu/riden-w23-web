<script setup>


import {ref} from "vue";

const count = ref(0)

function increment() {
  count.value++
  console.log('running',count.value)
}

</script>

<template>
  <div>
    <h1>this is home</h1>
    <button @click="increment">{{ count }}</button>
  </div>
</template>

<style scoped>

</style>