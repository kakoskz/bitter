<script setup>
    defineProps(['nombre'])

    const emit = defineEmits(['enviarNombre'])
</script>

<template>
    <p>Hola, soy {{ nombre }}</p>
    <button @click="emit('enviarNombre')">Avisar al Padre</button>
</template>

<style scoped>

</style>