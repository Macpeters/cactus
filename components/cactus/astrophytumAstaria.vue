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
        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 25 seeds from seedworld - it took a long time for them to arrive, and they were
                a mixture of species instead of a mixture of varieties, which is fine.  There were also only 75, when 
                I expected 100, which is less fine.  I'll order from a proper cactus seed retailer next time.
              </div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                It looks like everything has germinated, which is pretty solid.  They looked fairly
                globular at first, but now some of them are looking more columnar.  All these seedlings
                seem to be thriving.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="Astrophytum astaria seedlings from 23/05/2019" />
           <img v-bind:src="batch_01_seedlings_02" alt="Astrophytum astaria seedlings from 23/07/2019" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/astrophytumAstaria/astrophytumAstaria.jpeg';
  import batch_01_seedlings from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings_02.jpg';

  export default {
    head () {
      return {
        name: 'astrophytumAstaria',
        title: 'Astrophytum astaria'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_01_seedlings_02
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
