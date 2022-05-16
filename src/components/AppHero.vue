<template>
  <div class="app">
    <h1>Jumbotron</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure assumenda
      labore placeat, nisi praesentium quae cumque nulla qui et culpa autem
      perspiciatis, non ex hic deleniti itaque, at eveniet! Officiis.
    </p>
  </div>
</template>

<script>
export default {
  name: "AppHero",
};
</script>

<style scoped>
.app {
  margin: 0 auto;
  padding: 0.8rem;
  background-image: url(../assets/jumbo.png);
  background-repeat: no-repeat;
  background-position: center top;
  background-size: cover;
  width: 75%;
  height: 50vh;
  color: darkgray;
}
p {
  text-align: left;
}
</style>
