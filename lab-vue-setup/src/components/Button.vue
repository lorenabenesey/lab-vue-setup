<template>
  <button @click="count++">Add 1</button>
  <p>The button above has been clicked {{ counter }} times.</p>
</template>

<script setup>
import { ref } from 'vue'
const counter = ref(0);
</script>

<style>
button {
  font-size: 20px;
  width: 150px;
  height: 50px;
  border-radius: 5%;
}
</style>
