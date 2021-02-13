<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Estás en la Home</h1>
    <Saludo msg="Bienvenido/a/e"/>
    <Card number="1"/>
    <Card number="2"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue'
import Saludo from '@/components/Saludo.vue'

export default {
  name: 'Home',
  components: {
    Card,
    Saludo
  }
}
</script>
