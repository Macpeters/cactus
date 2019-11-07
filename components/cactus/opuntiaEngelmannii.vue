<template>
  <div class="cactus-log">
    

    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Rescued Prickly Pear</h2>
          <div>
            <h3>Purchased June/19</h3>
              <div>When I got this plant it was dripping with water, and drooping with sadness.  I transplanted
                it into dryer soil, and propped it up, and now there's fresh growth happening.  I'm not
                certain of the species - it's some kind of Opuntia. 
              </div>
          </div>
          <div>
            <h3>Cuttings</h3>
              <div>
                The long growth turned out to be simple etoliated plant growth.  It didn't look 
                like the plant as a whole would be well saved, but there were two decent pads, so 
                I've replanted both of those, and I'll see if either of them do well.  Some people
                say they've planted a pad straight into dirt, others that you must leave the pad to
                dry for a week.  I tried both ways.
              </div>
          </div>
           <img v-bind:src="adult_01" alt="Opuntia plant 20/07/2019"  />
           <img v-bind:src="adult_02" alt="Opuntia - is this a flower? 20/07/2019"  />
           <img v-bind:src="small_cutting_01" alt="Cutting planted straight away 17/09/2019"  />
           <img v-bind:src="large_cutting_01" alt="Cutting left to dry for a week 17/09/2019"  />
        </article>

        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>The seeds are unique as large discs which require 24 hours soaking in 
                water before sowing.  So far only 1/25 has germinated.  These are from cactusstore.com.
                As of July 23, there are 2 seedlings growing in this pot, but they are clearly not of 
                the same species.  One of them looks like a trichocereus, the other looks like some kind
                of succulent.  I'll let them keep growing, and maybe one day I'll be able to ID them 
                properly.
              </div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>

              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_03" alt="Opuntia engelmannii seedlings from 17/09/2019"  />
          <img v-bind:src="batch_01_seedlings_02" alt="Opuntia engelmannii seedlings from 23/07/2019"  />
          <img v-bind:src="batch_01_seedlings" alt="Opuntia engelmannii ? seedlings from 18/04/2019"  />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/opuntiaEngelmannii/opuntiaEngelmannii.jpeg';
  import batch_01_seedlings from '../../assets/cacti/opuntiaEngelmannii/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/opuntiaEngelmannii/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/opuntiaEngelmannii/batch_01_seedlings_03.jpg';
  import adult_01 from '../../assets/cacti/opuntiaEngelmannii/adult_01.jpg';
  import adult_02 from '../../assets/cacti/opuntiaEngelmannii/adult_02.jpg';
  import small_cutting_01 from '../../assets/cacti/opuntiaEngelmannii/small_cutting_01.jpg';
  import large_cutting_01 from '../../assets/cacti/opuntiaEngelmannii/large_cutting_01.jpg';

  export default {
    head () {
      return {
        name: 'opuntiaEngelmannii',
        title: 'Opuntia engelmannii'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        adult_01,
        adult_02,
        small_cutting_01,
        large_cutting_01
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>

