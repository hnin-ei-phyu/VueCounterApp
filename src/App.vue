<script setup>
  import {ref} from "vue";

  const count = ref(0);
</script>
<template>
  <main>
    <div>
      <h2>The Current Count is...</h2>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>&nbsp;&nbsp;
      <button @click="count++">+</button>
    </div>
  </main>

</template>

<style scoped>
  main {
    width: 100vw;
    height: 100vh;
    background-color: skyblue;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div{
    text-align: center;
  }
</style>