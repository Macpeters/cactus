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
          <div>16/25 have germinated and they're the biggest seedlings I've got, including those
            I planted last year.  They have an interesting shape to them, as well.  I'm excited
            to see what these do, but also worried that they'll become gigantic very quickly.
          </div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>

          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/carnigieaGigantea.jpeg';

  export default {
    head () {
      return {
        name: 'carnegieaGigantea',
        title: 'Carnegiea gigantea',
        data() { return {} },
        meta: [
          { hid: 'description', name: 'description', content: "See what cacti I'm growing" }
        ]
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
