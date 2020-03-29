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
          <h2>04/2019 - 15 remaining</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                The ones in one pot seem to be growing oddly.  I've seen this pinching on other species, but it's
                much more pronounced on these guys. The top bit doesn't look like it's even got a strong enough
                line to the nutrients of the main plant in some cases. Most are doing well, though - not showing
                any signs of clustering yet.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_05" alt="echinocereus Coccineus seedlings from 2020/03/29"  />
          <img v-bind:src="batch_01_seedlings_04" alt="echinocereus Coccineus seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="echinocereus Coccineus seedlings from 2019/09/17"  />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                I planted 25 seeds from cactusstore.com - 18 germinated.
                These guys have done well.  A couple look stunted because their hats never came off
                (a little piece of the seed shell).  I've just knocked those off, gently, so maybe they'll perk up now.
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
  import batch_01_seedlings_05 from '../../assets/cacti/echinocereusCoccineus/batch_01_seedlings_05.jpg';

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
        batch_01_seedlings_04,
        batch_01_seedlings_05
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
