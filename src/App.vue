<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue';
import MainPage from './components/MainPage.vue';

</script>

<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" /> -->
  <div id="app">
    <MainPage></MainPage>
  </div>
</template>

<style>
* {
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  width: 100vw;
  height: 100vh;
  background: #F9A03F;
}
</style>
