<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        All my tricho seeds so far have been purchased from Magiccactus.com
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Batch 2</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I had 30 seeds split into batches of 10 and 20, with varying light conditions.  
                More light had 50% germ rate, compared to 10% for less light.  There are still 13 as 
                of July 23</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                Altogether there are 13 seedlings - tall, skinny little things with adorable little spines trying 
                to form.  Still incubating.  They came out of incubation mid-july
              </div>
          </div>
          <img v-bind:src="batch_02_seedlings_03"  alt="Trichocereus bridgesii seedlings from 17/09/2019" />
          <img v-bind:src="batch_02_seedlings_02"  alt="Trichocereus bridgesii seedlings from 23/07/2019" />
          <img v-bind:src="batch_02_seedlings"  alt="Trichocereus bridgesii seedlings from 18/04/2019" />
        </article>

        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 03/2019</h3>
              <div>30 seeds in 2 inch plastic pots in baggies.  Except that I dropped them immediately after sowing :(</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                There is but one lone survival of this batch.  He's going to join the lopophoras that came out of incubation 
                too early - hardened off and stuck under 24 hour flor lighting to see how he likes it.  All these 
                cacti are now under 12 hour flor sundblaster knockoffs.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_03"  alt="Trichocereus bridgesii seedlings from 17/09/2019" />
          <img v-bind:src="batch_01_seedlings_02"  alt="Trichocereus bridgesii seedlings from 23/07/2019" />
          <img v-bind:src="batch_01_seedlings"  alt="Trichocereus bridgesii seedlings from 18/04/2019" />
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusBridgesii/trichocereusBridgesii.jpeg';
  import batch_01_seedlings from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings.jpg';
  import batch_02_seedlings from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings_02.jpg';
  import batch_02_seedlings_02 from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings_03.jpg';
  import batch_02_seedlings_03 from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings_03.jpg';

  export default {
    head () {
      return {
        name: 'trichocereusBridgesii',
        title: 'Trichocereus bridgesii'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_02_seedlings,
        batch_01_seedlings_02,
        batch_02_seedlings_02,
        batch_01_seedlings_03,
        batch_02_seedlings_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
