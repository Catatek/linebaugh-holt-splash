<template>
<div class="people">
  <div class="itemContainer">
    <img src="../assets/kisha.jpg" alt="Kisha photo">
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>Kisha Linebaugh</span>
  </div>

  <div class="itemContainer">
    <img src="../assets/christy.jpg" alt="Kisha photo">
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>Cristy Holt</span>
  </div>

  <div class="itemContainer">
    <img src="../assets/kaitlin.jpg" alt="Kisha photo">
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>Kaitlin Brennan</span>
  </div>

  <div class="itemContainer">
    <img src="../assets/natalie.jpg" alt="Kisha photo">
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>Natalie Fenderson</span>
  </div>
</div>
</template>

<script>
export default {
  name: 'People',
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.people {
  display: flex;
  justify-content: center;
  width: 100%;
  height: 60vh;
  /*padding: 3em 0;*/
}


.itemContainer {
  display: flex;
  padding-top: 3em;
  margin: 2em 3.5em;
  flex-direction: column;
  align-content: center;
  align-items: center;
}

.itemContainer > img {
  margin-top: 1em;
  width: 8.5em;
  height: 8.5em;
}

.itemContainer > span {
 margin: .7em 0;
 color: #9D2B2B;
 font-family: 'Montserrat', sans-serif;
 font-size: 1.3em;
}

#lineCircle {
  height: .8em;
  width: 6em;
}

</style>
