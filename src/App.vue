<template>
<body>
  <div id="app">
  <img alt="avengers" width="35%" src="./assets/h1.png" />
  
    <Game msg />
  </div>
</body>
</template>

<script>
import Game from "./components/game.vue";

export default {
  name: "App",
  components: {
    Game,
  },
};
</script>

<style>
#app {
  font-family: 'Staatliches', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding: 3em;
}
body { 
  background-image: url("./assets/bk.jpg"); 
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
