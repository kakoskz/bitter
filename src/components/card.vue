<script>
import BotonSaludo from './button.vue';

export default {
  name: 'card',
  components: { BotonSaludo },

  data() {
    return { mensaje: '' }
  },
  methods: {
    mostrarSaludo() {
      this.mensaje = 'Hola desde el hijo'
    }
  }
}
</script>

<template>
  <div>
    <BotonSaludo @saludo="mostrarSaludo" />
    <p v-if="mensaje">{{ mensaje }}</p>
  </div>
</template>