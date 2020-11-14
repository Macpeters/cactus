<template>
  <section class="container">
    <div>
      <img v-bind:src="cactus"  />
    </div>
  </section>
</template>

<script>
import cactus from '../assets/cacti/astrophytumAstaria/astrophytumAstaria.jpeg'

export default {
  components: {
  },
  data() {
    return {
      cactus
    };
  }
}
</script>

<style scoped>
  img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    max-height: 100vh;
    max-width: 90vw;
  }
</style>
