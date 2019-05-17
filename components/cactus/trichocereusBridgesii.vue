<template>
  <div>
    <img v-bind:src="image"  />

    <article>
      <h2>Notes on the species</h2>
      <div>
        All my seeds so far have been purchased from Magiccactus.com
      </div>
    </article>

    <article>
      <h2>Batch 2</h2>
      <div>
        <h3>Sowing the seeds: 04/2019</h3>
          <div>I had 30 seeds split into batches of 10 and 20, with varying light conditions.  
            More light had 50% germ rate, compared to 10% for less light.</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            Altogether there are 13 seedlings - tall, skinny little things with adorable little spines trying 
            to form.  Still incubating.
          </div>
      </div>
    </article>

    <article>
      <h2>Batch 1</h2>
      <div>
        <h3>Sowing the seeds: 03/2019</h3>
          <div>30 seeds in 2 inch plastic pots in baggies.  Except that I dropped them immediately after sowing :(</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            There is but one lone survival of this batch.  He's going to join the lopophoras that came out of incubation 
            too early - hardened off and stuck under 24 hour flor lighting to see how he likes it.
          </div>
      </div>
    </article>
 
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusBridgesii.jpeg';

  export default {
    head () {
      return {
        name: 'trichocereusBridgesii',
        title: 'Trichocereus bridgesii'
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
