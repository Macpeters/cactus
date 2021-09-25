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
          <section>
          <h2>Plants</h2>
          <h3>09/2021 - 5 remain</h3>
          <div>
            <p>
              I've sold a few, and it seems that some died, so I'm down to 5.  They've weathered the summer
              outside, and while one seems a bit red, they're pretty happy otherwise, and growing.
            </p>
          </div>
          </section>
          <img v-bind:src="batch_01_plants_02" alt="Astrophytum astaria from 2021/09/19" />

          <section>
            <h2>Seedlings</h2>
            <h3>05/2019 - 29 remain</h3>
            <div>
              <p>
                The seedlings have begun to grow more stocky, which I'm happy about.  This is closer to
                what I expect these guys to look like.  They are starting to straighten up and settle in,
                developing into beautiful geometric shapes.  32 Remain.
              </p>
              <p>
                It's august now, and these guys are definitely starting to look like I expect them to - beautiful
                geometric globs with striking spots of wool.  The dots around the wool are just starting to appear
                as well.  Theres one that has a strange colouring/marking scheme going on - I don't know if he's
                sick, or just odd. 29 Remain, which means I had 3 losses over the summer.  Not terrible, considering.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_01_plants_01" alt="Astrophytum astaria from 2020/08/21" />
          <img v-bind:src="batch_01_seedlings_05" alt="Astrophytum astaria seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Astrophytum astaria seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Astrophytum astaria seedlings from 2019/09/17" />

          <section>
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
          </section>
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
  import batch_01_plants_01 from '../../assets/cacti/astrophytumAstaria/batch_01_plants_01.jpg';
  import batch_01_plants_02 from '../../assets/cacti/astrophytumAstaria/batch_01_plants_02.jpg';

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
        batch_01_seedlings_05,
        batch_01_plants_01,
        batch_01_plants_02
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
