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
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.people {
  display: flex;
  justify-content: center;
  width: 100%;
  height: 60vh;
}
.itemContainer {
  display: flex;
  padding-top: 3em;
  margin: 0 3.5em;
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
}

#lineCircle {
  height: 1em;
  width: 6em;
}

</style>
