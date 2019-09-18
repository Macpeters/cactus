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
              <div>I planted 25 seeds from cactusstore.com, 18 have germinated.</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                I'm really glad these guys are doing so well - it looks like there are 18 of them, 
                all perky, with little spikes growing.  There's a little red at the base of a few, 
                which I want to keep an eye on.  I've moved them around a bit - they seem senstive 
                to the light still.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="Cleistocactus smaragdiflorus seedlings from 18/04/2019"  />
          <img v-bind:src="batch_01_seedlings_02" alt="Cleistocactus smaragdiflorus seedlings from 23/07/2019"  />
          <img v-bind:src="batch_01_seedlings_03" alt="Cleistocactus smaragdiflorus seedlings from 17/09/2019"  />
        </article>
      </div>
    </div>   
  </div>
</template>

<script>
  import image from '../../assets/cacti/cleistocactusSmaragdiflorus/cleistocactusSmaragdiflorus.jpeg';
  import batch_01_seedlings from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings_03.jpg';

  export default {
    head () {
      return {
        name: 'cleistocactusSmaragdiflorus',
        title: 'Cleistocactus smaragdiflorus'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
