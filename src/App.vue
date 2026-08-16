<script setup>
import hijo from './components/hijo.vue'

console.log('EL Hijo Me Aviso Algo')

alert('Hola desde el hijo!')
</script>


<template>
  <hijo nombre="Juan" @enviarNombre="onEnviarNombre" />
</template>
