<template>
  <div class="hello">
    <div class="header">
      <img class="mobileLlt" src="../assets/lltlogo1.png">
      <h1>Community minded real estate</h1>
      <hr>
      <h3>Our site is currently under construction. Please find our contact information below</h3>
    </div>
    <div class="unlock">
      <h1>{{ msg }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Splash',
  data() {
    return {
      msg: 'Unlocking Tampa Bay'
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@font-face {
  font-family: "Jenna";
  src: url('../assets/fonts/JennaSue.ttf');
}

@import url('https://fonts.googleapis.com/css?family=Montserrat');

.hello {
  margin: 0;
}

.mobileLlt {
  display: none;
}

.header {
  background-image: url('../assets/skyline.png');
  background-size: cover;
  background-repeat: no-repeat;
  height: 105vh;
}

.header hr {
  position: absolute;
  top: 36.8em;
  right: 3em;
  color: #ffffff;
  width: 35em;
  border: 1.5px solid #ffffff;
}
.header h3 {
  position: absolute;
  top: 34em;
  right: 2.7em;
  color: #ffffff;
  font-family: 'Montserrat', sans-serif;
  font-size: 1.1em;
}

img {
  width: 100%;
  height: 100%;
}

.header h1 {
  position: absolute;
  right: .6em;
  top: 5.5em;
  color: #ffffff;
  font-family: 'Jenna', sans-serif;
  font-size: 5em;
}


.unlock h1 {
  color: #00B2AA;
  padding-top: 2em;
  font-size: 2.2em;
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

@media (max-width: 480px) {
  .header {
    background-position: center;
  }

  .mobileLlt {
    display: block;
    position: absolute;
    left: 2em;
    top: 1.5em;
    width: 30%;
    height: 30%;

  }


  .header h1 {
    font-size: 3em;
    top: 8em;
  }

  .header hr {
    width: 20em;
    top: 29.5em;
    right: 2.2em;
    border: .5px solid #ffffff;
  }

  .header h3 {
    font-size: 1em;
    top: 30em;
    right: .5em;
    line-height: 1.5em;
  }
}





</style>
