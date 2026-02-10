<script setup>
import CommandTerminal from './components/CommandTerminal.vue'
</script>

<template>
  <CommandTerminal />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Consolas, 'Courier New', monospace;
  background-color: #1e1e1e;
  color: #d4d4d4;
  height: 100vh;
  overflow: hidden;
}

#app {
  height: 100vh;
}
</style>
