<script setup>
import Like from "./components/Like.vue";

function rubahWarna() {
  document.querySelector("h1").style.color = "red";
}
</script>

<template>
  <Like />
  <h1>You did it!</h1>
  <button @click="rubahWarna()">Rubah Warna H1</button>
  <h5>Ini buat nya dari PC 1</h5>
</template>

<style scoped>
h1 {
  color: #42b983;
}
</style>
