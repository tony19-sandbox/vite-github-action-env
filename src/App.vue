<script setup>
function logInternal(){
  console.log('VITE_INTERNAL', import.meta.env.VITE_INTERNAL)
}
</script>

<template>
  <h2>See browser console</h2>
  <button @click="logInternal">Click</button>
</template>
