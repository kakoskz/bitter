<script>
    export default{ 
        name : 'BotonSaludo'
    }
</script>


<template>
    <button @click="$emit('saludo')">mandar saludo</button>
</template>