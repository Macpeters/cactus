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
          <h2>Batch 02 03/2019 - 4 remain</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                <p>
                  All looking strong and happy.  Except that one I lost to rot :( I have to start treating
                  these like adults and not watering them as often.
                </p>
                <p>
                  The summer has been good to these guys, they're super happy, and they've grown a lot.  There's
                  no question that they're little adults now, and keeping them in clay has made it easy to avoid
                  over watering them.  Now that they're bigger, and I can keep a better eye on the individuals, I
                  have faith that these will all survive moving forward.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_02_plants_01"  alt="Trichocereus bridgesii seedlings from 2020/08/21" />
          <img v-bind:src="batch_02_seedlings_05"  alt="Trichocereus bridgesii seedlings from 2020/03/29" />
          <img v-bind:src="batch_02_seedlings_04"  alt="Trichocereus bridgesii seedlings from 2019/11/10" />
          <img v-bind:src="batch_02_seedlings_03"  alt="Trichocereus bridgesii seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                <p>
                  I had 30 seeds split into batches of 10 and 20, with varying light conditions.
                More light had 50% germ rate, compared to 10% for less light.  There are still 13 as
                of July 23. Altogether there are 13 seedlings - tall, skinny little things with adorable little spines trying
                  to form.  Still incubating.
                </p>
                <p>They came out of incubation mid-july</p>
              </div>
          </div>
          <img v-bind:src="batch_02_seedlings_02"  alt="Trichocereus bridgesii seedlings from 2019/07/23" />
          <img v-bind:src="batch_02_seedlings"  alt="Trichocereus bridgesii seedlings from 2019/04/18" />
        </article>

        <article class="batch">
          <h2>Batch 01 03/2018 - 2 remain</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                The two still live, and seems to be happy.  They've grown a lot over the summer, and they seem to have settled into
                their life as adorable little adults.
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01"  alt="Trichocereus bridgesii from 2020/08/21" />
          <img v-bind:src="batch_01_seedlings_05"  alt="Trichocereus bridgesii seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04"  alt="Trichocereus bridgesii seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03"  alt="Trichocereus bridgesii seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                <p>
                  30 seeds in 2 inch plastic pots in baggies.  Except that I dropped them immediately after sowing :(
                </p>
                <p>
                  There are but two lone survivors of this batch, who are going to join the lopophoras that came out of incubation
                  too early - hardened off and stuck under 12 hour flor sundblaster knockoffs.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02"  alt="Trichocereus bridgesii seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings"  alt="Trichocereus bridgesii seedlings from 2019/04/18" />
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusBridgesii/trichocereusBridgesii.jpeg';
  import batch_01_seedlings from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/trichocereusBridgesii/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/trichocereusBridgesii/batch_01_plants_01.jpg';

  import batch_02_seedlings from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings.jpg';
  import batch_02_seedlings_02 from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings_02.jpg';
  import batch_02_seedlings_03 from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings_03.jpg';
  import batch_02_seedlings_04 from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings_04.jpg';
  import batch_02_seedlings_05 from '../../assets/cacti/trichocereusBridgesii/batch_02_seedlings_05.jpg';
  import batch_02_plants_01 from '../../assets/cacti/trichocereusBridgesii/batch_02_plants_01.jpg';

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
