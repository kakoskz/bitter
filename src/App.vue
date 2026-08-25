<script>
import Card from './components/card.vue';
import Form from './components/form.vue'
export default {

  name: 'app',
  components: { Card, Form }
}
console.log('EL Hijo Me Aviso Algo')
</script>


<template>
    <Card/>
  <div >
    <h2>Actividad 4</h2>
    <Form/>
  </div>
</template>
