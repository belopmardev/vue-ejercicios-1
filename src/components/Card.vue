<template>
  <div class="container">
    <h2>Esto es el componente Tarjeta número {{number}}</h2>
    <div class="card">
      <div class="card-content">
        <img alt="Vue logo" src="../assets/logo.png" />
        <h3>Título de la tarjeta {{number}}</h3>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laudantium
          in facere consequatur ab cupiditate quo ipsa natus veritatis rem
          aspernatur corporis doloribus libero voluptas temporibus, quis
          dignissimos repellendus dolor recusandae! Iure obcaecati voluptatem
          harum quisquam magni molestiae consequuntur illo temporibus ad? Id,
          fugiat illum dolorem ab suscipit beatae alias sint quam debitis in
          accusantium minus quibusdam expedita quae reiciendis cum? Aut id
          corrupti molestias dolore ullam vitae eveniet voluptas? Rerum sequi
          iste assumenda sint eos?
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props:{
    number:""
  }
}
</script>

<style lang="scss" scoped>

h2 {
  color: #9E1A1A;
}
.container {
  margin: 3rem;
}

.card {
  margin: 0 auto;
  width: 70%;
  border: solid 2px #42b983;
  box-shadow: 10px 10px 10px grey;
}

.card-content {
  padding: 0.75rem;
  p{
    text-align: left;
  }
  img {
  float: left;
  margin: 0.5rem;
  clear: both;
  overflow: hidden;
  }
}
</style>