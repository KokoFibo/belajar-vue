<script setup>
import { ref } from "vue";
function addLike() {
  like.value++;
}

const like = ref(0);
</script>

<template>
  <h3>Like({{ like }})</h3>
  <button @click="addLike()">Like</button>
</template>

<style scoped>
h1 {
  color: #42b983;
}
</style>
