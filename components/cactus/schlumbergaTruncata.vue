<template>
  <div>
    <img v-bind:src="image"  />

    <article>
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <article>
      <h2>Mature Plant</h2>
      <div>
        This was a fully mature plant when I bought it - it is one of the few plants I have that 
        didn't start from seed.  I have seen it produce a single flower, once.
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/schlumbergaTruncata.jpg';
  export default {
    head () {
      return {
        name: 'schlumbergeraTruncata',
        title: 'Schlumbergera truncata'
      }
    },
    data() {
      return {
        image
      };
    }
  }
</script>

<style lang="css" src="./logs.css" scoped></style>
