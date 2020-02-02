<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="closeup"  />
      <h2>Notes on the species</h2>
      <div>
        This is the true Christmas Cactus, and isn't often sold anymore because
        it flowers during and after Christmas, just a little too late to be sold for gifts.
        For flowering, this plant requires high humidity and 12+ hours of darkness.  Regular pruming
        will encourage more branching.
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Cuttings</h2>
          <div>
            I've never really tried growing new plants from cuttings, so I decided to experiment a little.  They
            seem to have put down roots easily, and appear to be thriving and growing.  This was super easy.  I
            let the cuttings dry out for a few days, then stuck them in cactus soil, and kept them about as
            damp as I would an adult plant.
          </div>
          <img v-bind:src="cuttings_01_03"  alt="several cuttings from a mature S. buckleyi  plant 2019/11/10" />
          <img v-bind:src="cuttings_01_02"  alt="several cuttings from a mature S. buckleyi  plant 2019/09/17" />
          <img v-bind:src="cuttings_01"  alt="several cuttings from a mature S. buckleyi  plant 2019/07/23" />
        </article>

        <article class="batch">
          <h2>Mature Plant</h2>
          <div>
            This was a fully mature plant when I bought it - it is one of the few plants I have that
            didn't start from seed.  I have seen it produce a single flower, once.
          </div>
          <img v-bind:src="fullPlant"  alt="photo of S. buckleyi enjoying the outdoors 2019/07/23" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import closeup from '../../assets/cacti/schlumbergaBuckleyi/closeup.jpg';
  import fullPlant from '../../assets/cacti/schlumbergaBuckleyi/fullPlant.jpg';
  import cuttings_01 from '../../assets/cacti/schlumbergaBuckleyi/cuttings_01.jpg';
  import cuttings_01_02 from '../../assets/cacti/schlumbergaBuckleyi/cuttings_01_02.jpg';
  import cuttings_01_03 from '../../assets/cacti/schlumbergaBuckleyi/cuttings_01_03.jpg';

  export default {
    head () {
      return {
        name: 'schlumbergeraBuckleyi',
        title: 'Schlumbergera buckleyi'
      }
    },
    data() {
      return {
        closeup,
        fullPlant,
        cuttings_01,
        cuttings_01_02,
        cuttings_01_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
