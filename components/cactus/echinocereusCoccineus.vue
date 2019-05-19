<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article>
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 25 seeds from cactusstore.com - 18 have germinated.</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="echinocereus Coccineus seedlings from 18/04/2019"  />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/echinocereusCoccineus/echinocereusCoccineus.jpg';
  import batch_01_seedlings from '../../assets/cacti/echinocereusCoccineus/batch_01_seedlings.jpg';

  export default {
    head () {
      return {
        name: 'echinocereusCoccineus',
        title: 'Echinocereus coccineus'
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
