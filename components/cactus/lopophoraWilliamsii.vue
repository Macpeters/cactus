<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        They seem to have a fairly good germ rate, and are quick to show it.  All my seeds so far have been purchased
        from Sacred Seed in Toronto

        <div>
          <h3>Varieties</h3>
          <ul>
            <li><strong>Caespitosa</strong>: will easily grow multiple heads without any decapitation happening.  This makes them very easy
            to propogate.  These head form large clusters known as 'planchas'</li>
            <li><strong>Menchaka</strong>: tend to have only one head, unless decapitation occurs.</li>
          </ul>
        </div>
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>05/2019: v caespitosa</h2>
          <div>
            <h3>Seedlings - 69 remaining</h3>
              <div>
                These guys benefited from lessons I learned in previous batches - they got a longer incubation,
                and it shows.  They've largely settled into the plump globular shape that I'd expect from adults.
              </div>
              <img v-bind:src="batch_03_seedlings_05" alt="Lopophora williamsii seedlings from 2020/03/29" />
              <img v-bind:src="batch_03_seedlings_04" alt="Lopophora williamsii seedlings from 2019/11/10" />
              <img v-bind:src="batch_03_seedlings_03" alt="Lopophora williamsii seedlings from 2019/09/17" />
          </div>
           <div>
            <h3>Sowing the seeds: 05/2019</h3>
              <div>I sowed 100 seeds in 3 X 2 inch plastic pots in a plastic bin with lid.  It looked like about 64
                germinated to begin with, but it was hard to get an exact count because of the way they werre scattered,
                and it looked like a few more were trying to put down roots.</div>
          </div>
          <img v-bind:src="batch_03_seedlings_02" alt="Lopophora williamsii seedlings from 2019/07/23" />
          <img v-bind:src="batch_03_seedlings" alt="Lopophora williamsii seedlings from 2019/04/18"  />
        </article>

        <article class="batch">
          <h2>03/2019: v caespitosa</h2>
          <div>
            <h3>Seedlings - 9 remaining</h3>
              <div>
                I have had better luck keeping tiny pots in a clear tupperware container for a longer
                incubation period.  I'll do that from now on and probably do a lot better.
              </div>
              <img v-bind:src="batch_02_seedlings_05" alt="Lopophora williamsii seedlings from 2020/03/29" />
              <img v-bind:src="batch_02_seedlings_04" alt="Lopophora williamsii seedlings from 2019/11/10" />
              <img v-bind:src="batch_02_seedlings_03" alt="Lopophora williamsii seedlings from 2019/09/17" />
          </div>
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                20 seeds - a 2 inch plastic pot in a baggy
                15 seedlings remain as of 05/2019.  They are bright green and lush.  A couple are oddly shaped.  I am currenly using an LED grow light,
                and I am considering whether or not flourescent might be a better option in general, although I worry it might be too much for seedlings.
                These ones seem happy enough and I don't really want to mess with that.  They'll be in plastic for a few more months, all going well.
              </div>
          </div>
          <img v-bind:src="batch_02_seedlings_02" alt="Lopophora williamsii seedlings from 2019/07/23" />
          <img v-bind:src="batch_02_seedlings" alt="Lopophora williamsii seedlings from 2019/04/18" />
        </article>
      </div>

      <div class="row">
        <article class="batch">
          <h2>09/2018: v caespitosa</h2>
          <div>
          <h3>Seedlings - 2 remaining</h3>
            <div>
              There are a lot of things I could have done better.  I hope future batches are much more successful.
            </div>
            <img v-bind:src="batch_01_seedlings_05" alt="Lopophora williamsii seedlings from 2020/03/29" />
            <img v-bind:src="batch_01_seedlings_04" alt="Lopophora williamsii seedlings from 2019/11/10" />
            <img v-bind:src="batch_01_seedlings_03" alt="Lopophora williamsii seedlings from 2019/09/17" />
          </div>
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                I sowed 30 seeds - half in a plastic icecube tray with a plastic cover and half in a 2 inch clay pot in a baggy. Many were
                misshapen and odd looking.  I took the seedlings out of plastic much earlier than I needed to and they seemed small and stunted
                compared to other seedlings which were planted later.  The ones in the icecube tray had a much better germination rate.
                There were some redish tinges for a little while, and I experimented with moving the seedlings further from the light,
                which led to yellowing and stretching.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Lopophora williamsii seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Lopophora williamsii seedlings from 2019/04/18" />
        </article>

        <article class="batch">
          <h2>Charlie: v menchaka</h2>
          <div>
            <h3>Born November 6, 2014</h3>
              <div>
                This is one of the only cacti I own that I didn't plant. He was 2.5 years old when I picked him up (Spring 2018-ish).
                Still quite small, as these fellas tend to be, but seems happy enough.  I moved him from his tiny plastic pot to a
                slightly larger clay pot.
              </div>
              <img v-bind:src="charlie_3_5_side"  alt="Lopophora williamsii fron the side, Spring, 2019" />
              <img v-bind:src="charlie_3_5_above"  alt="Lopophora williamsii from above, Spring, 2019" />
              <img v-bind:src="charlie"  alt="Lopophora williamsii, Spring, 2018" />
          </div>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/lopophoraWilliamsii/charlie_3years.jpg';
  import charlie from '../../assets/cacti/lopophoraWilliamsii/charlie_2_5years.jpg';
  import charlie_3_5_above from '../../assets/cacti/lopophoraWilliamsii/charlie_3_5yearsAbove.jpg';
  import charlie_3_5_side from '../../assets/cacti/lopophoraWilliamsii/charlie_3_5_yearsSide.jpg';

  import batch_01_seedlings from '../../assets/cacti/lopophoraWilliamsii/18_09_01.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/lopophoraWilliamsii/18_09_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/lopophoraWilliamsii/18_09_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/lopophoraWilliamsii/18_09_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/lopophoraWilliamsii/18_09_05.jpg';

  import batch_02_seedlings from '../../assets/cacti/lopophoraWilliamsii/19_03_01.jpg';
  import batch_02_seedlings_02 from '../../assets/cacti/lopophoraWilliamsii/19_03_02.jpg';
  import batch_02_seedlings_03 from '../../assets/cacti/lopophoraWilliamsii/19_03_03.jpg';
  import batch_02_seedlings_04 from '../../assets/cacti/lopophoraWilliamsii/19_03_04.jpg';
  import batch_02_seedlings_05 from '../../assets/cacti/lopophoraWilliamsii/19_03_05.jpg';

  import batch_03_seedlings from '../../assets/cacti/lopophoraWilliamsii/19_05_01.jpg';
  import batch_03_seedlings_02 from '../../assets/cacti/lopophoraWilliamsii/19_05_02.jpg';
  import batch_03_seedlings_03 from '../../assets/cacti/lopophoraWilliamsii/19_05_03.jpg';
  import batch_03_seedlings_04 from '../../assets/cacti/lopophoraWilliamsii/19_05_04.jpg';
  import batch_03_seedlings_05 from '../../assets/cacti/lopophoraWilliamsii/19_05_05.jpg';

  export default {
    head () {
      return {
        name: 'lopophoraWilliamsii',
        title: 'Lopophora williamsii',
        meta: [
          { hid: 'description', name: 'description', content: 'Lopophora grow log' }
        ]
      }
    },
    data() {
      return {
        image,
        charlie,
        charlie_3_5_above,
        charlie_3_5_side,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        batch_01_seedlings_04,
        batch_01_seedlings_05,
        batch_02_seedlings,
        batch_02_seedlings_02,
        batch_02_seedlings_03,
        batch_02_seedlings_04,
        batch_02_seedlings_05,
        batch_03_seedlings,
        batch_03_seedlings_02,
        batch_03_seedlings_03,
        batch_03_seedlings_04,
        batch_03_seedlings_05
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
