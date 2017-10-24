<template>
<div class="Index">
  <Splash></Splash>
  <People></People>
  <Footer></Footer>
</div>
</template>

<script>
import Splash from '@/components/Splash';
import People from '@/components/People';
import Footer from '@/components/Footer';

export default {
  name: 'Index',
  data() {
    return {};
  },
  components: {
    Splash,
    People,
    Footer,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Index {
  margin: 0;
}
</style>
