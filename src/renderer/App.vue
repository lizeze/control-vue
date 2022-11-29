<script setup lang="ts">
 import Home from './pages/Home.vue'

window.electron.ipcRenderer.send('message', 'Hello from App.vue!');
</script>

<template>
  <div id="app">
  <Home></Home>
  </div>
</template>

<style>
.icon {
       width: 2em; height: 2em;
       vertical-align: -0.15em;
       fill: currentColor;
       overflow: hidden;
    }</style>