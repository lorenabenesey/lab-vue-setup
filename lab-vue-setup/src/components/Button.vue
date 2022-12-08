<template>
  <button @click="count++">Add 1</button>
  <p>Count is: {{ count }}</p>
</template>

<script setup>
function sayHello(hello) {
  sayHello();
}
</script>

<style>
button {
  font-size: 20px;
  width: 150px;
  height: 50px;
  border-radius: 5%;
}
</style>
