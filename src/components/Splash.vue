<template>
  <div class="hello">
    <div class="header">
      <img src="../assets/skyline.png" alt="Living Loving Tampa Splash">
      <h1>{{ msg }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Splash',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@font-face {
  font-family: "Inkferno";
  src: url('../assets/fonts/INKFERNO.otf');
}

.hello {
  margin: 0;
}

img {
  width: 100%;
  height: 100%;
}

h1,
h2 {
  font-weight: normal;
  font-family: 'Inkferno', sans-serif;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}





</style>
