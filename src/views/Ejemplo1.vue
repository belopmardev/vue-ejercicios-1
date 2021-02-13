<template>
    <h1>Estás en ejemplo 1</h1>
    <p>En esta página se muestran componentes <b>Saludo</b> con mensajes diferentes</p>
    <Saludo msg="¡Hola!"/>
    <Saludo msg="Hello!"/>
    <Saludo msg="Hi!"/>
    <Saludo msg="Ciao!"/>
    <Saludo msg="Salut!"/>
    <Saludo msg="Alô!"/>
    <Saludo msg="Hej!"/>
    <Saludo msg="Yassou!"/>

</template>

<script>
import Saludo from '@/components/Saludo.vue'
export default {
  components:{
    Saludo
  }
}
</script>
<style lang="scss" scoped>

</style>