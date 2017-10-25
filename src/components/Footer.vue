<template>
<div class="Footer">
  <div class="baytobay">
  <img class="REMAX" src="../assets/remax.png" alt="Remax Logo">
  <span>Bay to Bay</span>
  </div>
  <div class="contactDetails">
    <span>(813) 259-0000</span>
    <span>1001 S Maddill Avenue</span>
    <span>Tampa, FL 33629</span>
  </div>
  <img class="LLT" src="../assets/lltlogo.png" alt="">
</div>
</template>

<script>
import Splash from '@/components/Splash';
import People from '@/components/People';

export default {
  name: 'Footer',
  data() {
    return {};
  },
  components: {
    Splash,
    People
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@import url('https://fonts.googleapis.com/css?family=Montserrat');

.Footer {
  display: flex;
  align-items: center;
  justify-content: space-around;
  height: 18em;
  width: 100%;
  color: white;
  background-color: #00b2aa;
  font-size: 18px;
  font-weight: bold;
}

.baytobay {
  display: flex;
  flex-direction: column;
  text-align: left;
}

.baytobay > span {
  margin-top: .5em;
  font-family: 'Montserrat', sans-serif;
  font-size: 1.3em;
}

.contactDetails span {
  font-family: 'Montserrat', sans-serif;
  text-align: left;
  padding: .15em 0;
}

.baytobay > .REMAX {
width: 210px;
}

.Footer > .LLT {
width: 150px;
}

.Footer > .contactDetails {
  display: flex;
  flex-direction: column;
}

</style>
