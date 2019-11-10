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
            <h3>Seedlings</h3>
              <div>
                6 remain of this batch - not a spectacular rate.  The ones that are still alive seem 
                to be growing oddly.  I've seen this pinching on other species, but it's much more pronounced
                on these guys. The top bit doesn't look like it's even got a strong enough line to the nutrients
                of the main plant in some cases.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_04" alt="echinocereus Coccineus seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="echinocereus Coccineus seedlings from 2019/09/17"  />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>
                I planted 25 seeds from cactusstore.com - 18 have germinated.
                These guys have done well.  All 18 remain, with little spikes and what could be arms, but we'll
                see.  There's only one that looks stunted because it's hat never came off (a little piece of the seed
                shell).  I've just knocked that off, gently, so maybe it'll perk up now.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="echinocereus Coccineus seedlings from 2019/07/23"  />
          <img v-bind:src="batch_01_seedlings" alt="echinocereus Coccineus seedlings from 2019/04/18"  />     
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/echinocereusCoccineus/echinocereusCoccineus.jpg';
  import batch_01_seedlings from '../../assets/cacti/echinocereusCoccineus/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/echinocereusCoccineus/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/echinocereusCoccineus/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/echinocereusCoccineus/batch_01_seedlings_04.jpg';

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
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        batch_01_seedlings_04
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
