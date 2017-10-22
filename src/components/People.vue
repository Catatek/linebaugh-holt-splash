<template>
<div class="people">
  <div class="itemContainer">
    <img src="../assets/kisha.jpg" alt="Kisha photo">
    <span>Kisha Linebaugh</span>
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>(813) 362-1218</span>
  </div>

  <div class="itemContainer">
    <img src="../assets/christy.jpg" alt="Kisha photo">
    <span>Cristy Holt</span>
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>(813) 505-6210</span>
  </div>

  <div class="itemContainer">
    <img src="../assets/kaitlin.jpg" alt="Kisha photo">
    <span>Kaitlin Brennan</span>
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>(727) 269-1236</span>
  </div>

  <div class="itemContainer">
    <img src="../assets/natalie.jpg" alt="Kisha photo">
    <span>Natalie Fenderson</span>
    <img id="lineCircle" src="../assets/linecircle.png" alt="line dot design">
    <span>(813) 242-7335</span>
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
  padding: 0 2em;
}
.itemContainer {
  display: flex;
  margin: 0 3em;
  flex-direction: column;
  align-content: center;
  align-items: center;
}

.itemContainer > img {
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
