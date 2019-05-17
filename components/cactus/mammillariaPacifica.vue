<template>
  <div>
    <img v-bind:src="image"  />

    <article>
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <article>
      <h2>Batch 1</h2>
      <div>
        <h3>Sowing the seeds: 04/2019</h3>
          <div>I planted 25 seeds - 9 appear to have germinated</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
              It's still very early, but these are super tiny - barely visible
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/mammillariaPacifica.jpg';
  export default {
    head () {
      return {
        name: 'mammillariaPacifica',
        title: 'Mammillaria pacifica'
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
