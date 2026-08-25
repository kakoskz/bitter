<script>
    import button from './button.vue';


    export default {
        name: 'card',
        components: { card },

        data(){
            return { mensaje: '' }
        },methods: {
            mostrarSaludo() {
                this.mensaje = 'Hola desde el hijo '
            }
        }
    }
</script>

<template>
    <div>
        <BotonSaludo @saludo="mostrarSaludo" />
        <p v-if = "mensaje">{{ mensaje }}</p>
    </div>
</template>