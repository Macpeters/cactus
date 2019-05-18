<template>
  <div>
    <img v-bind:src="image"  />

    <article class="main-notes">
      <h2>Notes on the species</h2>
      <div>
        All my seeds so far have come from magiccactus.com
      </div>
    </article>

    <article>
      <h2>Batch 2</h2>
      <div>
        <h3>Sowing the seeds: 04/2019</h3>
          <div>I planted 30 seeds in batches of 10 with varying light levels</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
              28/30 seedlings are still going strong - they didn't seem to care how much light I gave them, and they 
              had a solid germ rate.  Still incubating.
          </div>
      </div>
    </article>

    <article>
      <h2>Batch 1</h2>
      <div>
        <h3>Sowing the seeds: 03/2019</h3>
          <div>I planted 30 seeds, 1 still lives</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
              This batch was dropped just after sowing :( and only one survived.  It is out of incubation early.
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusPeruvianus.jpg';

  export default {
    head () {
      return {
        name: 'trichocereusPeruvianus',
        title: 'Trichocereus peruvianus'
      }
    },
    data() {
      return {
        image
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>