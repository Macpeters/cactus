<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="closeup"  />
      <h2>Notes on the species</h2>
      <div>
        This cactus flowers around the U.S. Thanksgiving, so is often sold for
        Christmas gifts.
        For flowering, this plant requires high humidity and 12+ hours of darkness.
        Regular pruming will encourage more branching
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">

        <article class="batch">
          <h2>Mature Plant</h2>
          <div>
            This was a fully mature plant when I bought it.
          </div>
          <img v-bind:src="flowers"  alt="schlumberga Truncata flowers 02/02/2020" />
          <img v-bind:src="fullPlant"  alt="schlumberga Truncata plant 02/02/2020" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import fullPlant from '../../assets/cacti/schlumbergaTruncata/fullPlant.jpg';
  import closeup from '../../assets/cacti/schlumbergaTruncata/closeUp.jpg';
  import flowers from '../../assets/cacti/schlumbergaTruncata/flowers.jpg';

  export default {
    head () {
      return {
        name: 'schlumbergeraTruncata',
        title: 'Schlumbergera truncata'
      }
    },
    data() {
      return {
        fullPlant,
        closeup,
        flowers
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
