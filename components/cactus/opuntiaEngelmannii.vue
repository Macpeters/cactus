<template>
  <div class="cactus-log">
    

    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>The seeds are unique as large discs which require 24 hours soaking in 
                water before sowing.  So far only 1/25 has germinated.  These are from cactusstore.com.
              </div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>

              </div>
          </div>
           <img v-bind:src="batch_01_seedlings" alt="Opuntia engelmannii seedlings from 18/04/2019"  />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/opuntiaEngelmannii/opuntiaEngelmannii.jpeg';
  import batch_01_seedlings from '../../assets/cacti/opuntiaEngelmannii/batch_01_seedlings.jpg';

  export default {
    head () {
      return {
        name: 'opuntiaEngelmannii',
        title: 'Opuntia engelmannii'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>

