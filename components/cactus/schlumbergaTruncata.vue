<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="closeup"  />
      <h2>Notes on the species</h2>
      <div>
        For flowering, this plant requires high humidity and 12+ hours of darkness.  Regular pruming will 
        encourage more branching
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Cuttings</h2>
          <div>
            I've never really tried growing new plants from cuttings, so I decided to experiment a little.
          </div>
          <img v-bind:src="cuttings_01_02"  alt="several cuttings from a mature schlumberga plant 17/09/2019" />
          <img v-bind:src="cuttings_01"  alt="several cuttings from a mature schlumberga plant 23/07/2019" /> 
        </article>

        <article class="batch">
          <h2>Mature Plant</h2>
          <div>
            This was a fully mature plant when I bought it - it is one of the few plants I have that 
            didn't start from seed.  I have seen it produce a single flower, once.
          </div>
          <img v-bind:src="fullPlant"  alt="photo of schlumberga enjoying the outdoors 23/07/2019" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import closeup from '../../assets/cacti/schlumbergaTruncata/closeup.jpg';
  import fullPlant from '../../assets/cacti/schlumbergaTruncata/fullPlant.jpg';
  import cuttings_01 from '../../assets/cacti/schlumbergaTruncata/cuttings_01.jpg';
  import cuttings_01_02 from '../../assets/cacti/schlumbergaTruncata/cuttings_01_02.jpg';

  export default {
    head () {
      return {
        name: 'schlumbergeraTruncata',
        title: 'Schlumbergera truncata'
      }
    },
    data() {
      return {
        closeup,
        fullPlant,
        cuttings_01,
        cuttings_01_02
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
