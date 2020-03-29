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
          <h2>05/2019 - 32 remain</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                The seedlings have begun to grow more stocky, which I'm happy about.  This is closer to
                what I expect these guys to look like.  They are starting to straighten up and settle in,
                developing into beautiful geometric shapes.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_05" alt="Astrophytum astaria seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Astrophytum astaria seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Astrophytum astaria seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                <p>
                  I planted 25 seeds from seedworld - it took a long time for them to arrive, and they were
                  a mixture of species instead of a mixture of varieties, which is fine.  There were also only 75, when
                  I expected 100, which is less fine.  I'll order from a proper cactus seed retailer next time.
                </p>
                <p>
                  It looks like everything has germinated, which is pretty solid.  They looked fairly
                  globular at first, but now some of them are looking more columnar.  All these seedlings
                  seem to be thriving.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Astrophytum astaria seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Astrophytum astaria seedlings from 2019/05/23" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/astrophytumAstaria/astrophytumAstaria.jpeg';
  import batch_01_seedlings from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/astrophytumAstaria/batch_01_seedlings_05.jpg';

  export default {
    head () {
      return {
        name: 'astrophytumAstaria',
        title: 'Astrophytum astaria'
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
