<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        Long lived, slow growing.  Plants have to be at least 14 inches across before
        they'll flower.  Sometimes they are self-fertile, but you'd get more seeds
        cross-pollinating with another plant.
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                Well 5 are still kicking - they aren't the happiest bunch of cacti I have, but as
                long as they still live, there's hope. This might be a particularly slow growing
                species.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_04" alt="echinocactus Grusonii seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="echinocactus Grusonii seedlings from 2019/09/17"  />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 25 seeds from cactusstore.com.  4 seem to have germinated, although a couple
                seem a little upside down. It looks like there are 10 of them, but most seem etoliated,
                and the rest look stunted. I'm not sure I can reach in and pull the hat off that one at
                the back without disturbing  others, so I'll leave it for now.  I don't have much faith
                in the futures of these sad looking cacti.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="echinocactus Grusonii seedlings from 2019/07/23"  />
          <img v-bind:src="batch_01_seedlings" alt="echinocactus Grusonii seedlings from 2019/04/18"  />
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/echinocactusGrusonii/echinocactusGrusonii.jpg';
  import batch_01_seedlings from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_04.jpg';

  export default {
    head () {
      return {
        name: 'echinocactusGrusonii',
        title: 'Echinocactus grusonii'
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
