<template>
  <div class="about">
    <h1>Estás en la página about</h1>
    <p>En esta página se muestran tres componentes <b>Tarjeta</b> diferentes</p>
    <Card number="1"/>
    <Card number="2"/>
    <Card number="3"/>
  </div>
</template>
<script>

import Card from '@/components/Card.vue'
export default {
  components:{
    Card
  }
}
</script>
