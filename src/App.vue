<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import AutoComplete from './components/AutoComplete.vue';
</script>

<template>
  <div class="flex flex-wrap  justify-center h-48">
    <div class="w-1/2  justify-center content-center border-2 border-black">
      <img alt="Vue logo" src="./assets/logo.png" class="object-center border-4 border-red-300" />
      <AutoComplete />
    </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
