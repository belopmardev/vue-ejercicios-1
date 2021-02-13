<template>
    <div>
        <h2>Esto es el componente Saludo que dice <span class="msg">{{ msg }}</span></h2>
    </div>
</template>

<script>
export default {
    name:"Saludo",
    props: {
        msg: String
    }
}
</script>

<style lang="scss" scoped>
    h2{
        color: #2c3e50;
        span{
            background-color:#42b983;
            padding: 0.5rem;
        }
    }
</style>