<template>
  <div>
    <img v-bind:src="image"  />

    <article class="main-notes">
      <h2>Notes on the species</h2>
      <div>
        All my trich seeds so far have come from magiccactus.com
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>09/2019 Batch 2: 23 remain</h2>
          <div>
            <h3>Plants</h3>
              <div>
                  These have gained some size over the summer.  I'm tempted to split them up so they can
                  have more space individually to grow.
              </div>
          </div>
          <img v-bind:src="batch_02_plants_01" alt="Trichocereus peruvianus from 2020/08/21" />
          <div>
            <h3>Seedlings</h3>
              <div>
                  These are clearly thriving.  I'm not sure if they're too crowded, or if they
                  enjoy each other's company, but I'll leave them in there a little longer.
              </div>
          </div>
          <img v-bind:src="batch_02_seedlings_05" alt="Trichocereus peruvianus seedlings from 2020/03/29" />
          <img v-bind:src="batch_02_seedlings_04" alt="Trichocereus peruvianus seedlings from 2019/11/10" />
          <img v-bind:src="batch_02_seedlings_03" alt="Trichocereus peruvianus seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                <p>
                  I planted 30 seeds in batches of 10 with varying light levels.  28/30 seedlings germinated -
                  they didn't seem to care how much light I gave them, and they had a solid germ rate.  Incubated
                  until mid July, when I noticed some fungas and gnats around.
                </p>
                <p>
                  As of July 23, everyone is still alive.  I transplanted these guys into clay
                  pots so I could water from below and bury them a little better, since a few were falling
                  over or growing out of the side of the pot.  The extra couple months of incubation made
                  a big difference.  I'd have liked to leave them in there longer.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_02_seedlings_02" alt="Trichocereus peruvianus seedlings from 2019/07/23" />
          <img v-bind:src="batch_02_seedlings" alt="Trichocereus peruvianus seedlings from 2019/04/18" />
        </article>

         <article class="batch">
          <h2>03/2019 Batch 1: 1 remains</h2>
          <div>
            <h3>Plant</h3>
              <div>
                 This fellow has shot up a lot over the summer - real sunlight has done him some real justice.
                 I am definitely treating this one as an adult now.
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01" alt="Trichocereus peruvianus from 2020/08/21" />
          <div>
            <h3>Seedlings</h3>
              <div>
                 The one cactus is still kicking, and looking properly spikey
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_05" alt="Trichocereus peruvianus seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Trichocereus peruvianus seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Trichocereus peruvianus seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                I planted 30 seeds, 1 still lives. This batch was dropped just after sowing &#128546;  and only one survived.
                It came out of incubation after a only a month, due to fungal issues.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Trichocereus peruvianus seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Trichocereus peruvianus seedlings from 2019/04/18" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusPeruvianus/trichocereusPeruvianus.jpg';
  import batch_01_seedlings from '../../assets/cacti/trichocereusPeruvianus/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/trichocereusPeruvianus/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/trichocereusPeruvianus/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/trichocereusPeruvianus/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/trichocereusPeruvianus/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/trichocereusPeruvianus/batch_01_plants_01.jpg';

  import batch_02_seedlings from '../../assets/cacti/trichocereusPeruvianus/batch_02_seedlings.jpg';
  import batch_02_seedlings_02 from '../../assets/cacti/trichocereusPeruvianus/batch_02_seedlings_02.jpg';
  import batch_02_seedlings_03 from '../../assets/cacti/trichocereusPeruvianus/batch_02_seedlings_03.jpg';
  import batch_02_seedlings_04 from '../../assets/cacti/trichocereusPeruvianus/batch_02_seedlings_04.jpg';
  import batch_02_seedlings_05 from '../../assets/cacti/trichocereusPeruvianus/batch_02_seedlings_05.jpg';
  import batch_02_plants_01 from '../../assets/cacti/trichocereusPeruvianus/batch_02_plants_01.jpg';

  export default {
    head () {
      return {
        name: 'trichocereusPeruvianus',
        title: 'Trichocereus peruvianus'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        batch_01_seedlings_04,
        batch_01_seedlings_05,
        batch_01_plants_01,
        batch_02_seedlings,
        batch_02_seedlings_02,
        batch_02_seedlings_03,
        batch_02_seedlings_04,
        batch_02_seedlings_05,
        batch_02_plants_01
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>