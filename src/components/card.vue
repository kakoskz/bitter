<script>
    import button from './button.vue';


    export default {
        name: 'button',
        components: { button },

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
        <button @saludo="mostrarSaludo" />
        <p v-if = "mensaje">{{ mensaje }}</p>
    </div>
</template>