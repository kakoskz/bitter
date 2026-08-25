<script>
import Card from './components/card.vue';
import Form from './components/form.vue'
import Tareas from './components/tareas.vue';
export default {

  name: 'app',
  components: { Card, Form , Tareas }
}
console.log('EL Hijo Me Aviso Algo')
</script>


<template>
    <Card/>
  <div >
    <h2>Actividad 4</h2>
    <Form/>
  </div>

  <div>
    <h2>Actividad 5</h2>
    <Tareas/>
  </div>
</template>
