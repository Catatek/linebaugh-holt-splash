<template>
<div class="Footer">
  <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
  <div class="break">
    <span>Serving the metro Tampa and</span>
    <span>St. Petersburg area!</span>
  </div>
  <div class="branding">
    <div class="left">
      <img src="../assets/remax.png" alt="Remax Logo">
      <h4>Bay to Bay</h4>
      <div class="contactDetails">
        <span>(813) 259-0000</span>
        <span>1001 S Maddill Avenue</span>
        <span>Tampa, FL 33629</span>
      </div>
    </div>

    <img src="../assets/lltlogo.png" alt="">

    <div class="social">
      <i class="fa fa-twitter fa-3x" aria-hidden="true"></i>
      <i class="fa fa-facebook-square fa-3x" aria-hidden="true"></i>
      <i class="fa fa-instagram fa-3x" aria-hidden="true"></i>
    </div>
  </div>
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
    People,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.break {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  height: 8em;
  width: 100%;
  color: white;
  background-color: #00b2aa;
  font-size: 24px;
  font-weight: bold;
  border-bottom: 1em solid white;
}

.break span {
  margin-left: 6%;
}

.branding {
  display: flex;
  justify-content: space-around;
  padding: 2em;
}

.branding h4 {
  color: #9e2a2a;
}

.left {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.contactDetails {
  display: flex;
  flex-direction: column;
  text-align: left;
}

.social {
  display: flex;
  align-items: center;
}

i {
  color: #00b2aa;
  margin-left: .5em;
}
</style>
