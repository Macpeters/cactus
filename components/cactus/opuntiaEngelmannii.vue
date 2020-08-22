<template>
  <div class="cactus-log">


    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        Opuntia don’t germinate easily unlike most cacti. Soaking the in lemon juice for 24 hrs
        before planting helps break down the hard outer shell so that the seeds can germanate
        more easily.  I was recommended soaking in water, but lemon juice would be more acidic.
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Rescued Prickly Pear</h2>
          <div>
            <h3>Cuttings</h3>
              <div>
                <p>
                  The long growth turned out to be simple etoliated plant growth.  It didn't look
                  like the plant as a whole would be well saved, but there were two decent pads, so
                  I've replanted both of those, and I'll see if either of them do well.  Some people
                  say they've planted a pad straight into dirt, others that you must leave the pad to
                  dry for a week.  I tried both ways.
                </p>
                <p>
                  Clearly the small cutting, which I planted
                  straight away, is growing, while the large cutting, which laid out to dry for a
                  week, is still not appearing to grow at all.  I don't know what's happening under
                  the soil, so as long as it seems alive, I'll leave it alone.  But I know which method
                  I like better, from what I can see so far.
                </p>
              </div>
          </div>
          <img v-bind:src="small_cutting_02" alt="Small cutting 2020/08/21"  />
          <img v-bind:src="large_cutting_02" alt="Large cutting 2020/08/21"  />
          <img v-bind:src="small_cutting_01" alt="Cutting planted straight away 2019/09/17"  />
          <img v-bind:src="large_cutting_01" alt="Cutting left to dry for a week 2019/09/17"  />
          <div>
            <h3>Purchased June/19</h3>
              <div>When I got this plant it was dripping with water, and drooping with sadness.  I transplanted
                it into dryer soil, and propped it up, and now there's fresh growth happening.  I'm not
                certain of the species - it's some kind of Opuntia.
              </div>
          </div>
          <img v-bind:src="adult_01" alt="Opuntia 20/07/2019"  />
          <img v-bind:src="adult_02" alt="Opuntia 20/07/2019"  />
        </article>

        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Seedlings: 11/2019</h3>
              <div>
                <p>
                  Well, the opuntia's starting to flatten out on top, so I guess the bright summer sun has done him a
                little good.  He's still taller and skinnier than I'd expect, but there isn't much I can
                do beyond real sunlight.  I'll just have to see how things go in the future.
                </p>
                <p>
                  The mystery - he could be e. Grusonii?  If he fell out of one of my seeds into that pot, it's possible.
                  If the seed store stuck him in by accident, who knows? Those are some solid spines on there, though.  The
                  geometry looks right for the species, but he doesn't look much like my seedling.  So he's still a mystery.
                  What are you, Not Opuntia?
                </p>
              </div>
          </div>
          <img v-bind:src="mystery_02" alt="Unknown seedling from 2020/08/21"  />
          <img v-bind:src="batch_01_plants_01" alt="Opuntia engelmannii from 2020/08/21"  />
          <div>
            <h3>Seedlings: 11/2019</h3>
              <div>
                Is this guy super etoliated?  I've moved him closer to the light, just in case. I'm not
                seeing the tell-tale pads of opuntia, but maybe it's still early.  That other mystery cactus
                is still there, not doing much.
              </div>
          </div>
          <img v-bind:src="mystery_01" alt="Unknown seedling from 2020/03/29"  />
          <img v-bind:src="batch_01_seedlings_05" alt="Opuntia engelmannii seedlings from 2020/03/29"  />
          <img v-bind:src="batch_01_seedlings_04" alt="Opuntia engelmannii seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="Opuntia engelmannii seedlings from 2019/09/17"  />
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
          <img v-bind:src="batch_01_seedlings_02" alt="Opuntia engelmannii seedlings from 2019/07/23"  />
          <img v-bind:src="batch_01_seedlings" alt="Opuntia engelmannii ? seedlings from 2019/04/189"  />
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
  import batch_01_seedlings_04 from '../../assets/cacti/opuntiaEngelmannii/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/opuntiaEngelmannii/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/opuntiaEngelmannii/batch_01_plants_01.jpg';

  import mystery_01 from '../../assets/cacti/opuntiaEngelmannii/mystery_01.jpg';
  import mystery_02 from '../../assets/cacti/opuntiaEngelmannii/mystery_02.jpg';
  import adult_01 from '../../assets/cacti/opuntiaEngelmannii/adult_01.jpg';
  import adult_02 from '../../assets/cacti/opuntiaEngelmannii/adult_02.jpg';
  import small_cutting_01 from '../../assets/cacti/opuntiaEngelmannii/small_cutting_01.jpg';
  import small_cutting_02 from '../../assets/cacti/opuntiaEngelmannii/small_cutting_02.jpg';
  import large_cutting_01 from '../../assets/cacti/opuntiaEngelmannii/large_cutting_01.jpg';
  import large_cutting_02 from '../../assets/cacti/opuntiaEngelmannii/large_cutting_02.jpg';

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
        batch_01_seedlings_04,
        batch_01_seedlings_05,
        batch_01_plants_01,
        mystery_01,
        mystery_02,
        adult_01,
        adult_02,
        small_cutting_01,
        large_cutting_01,
        small_cutting_02,
        large_cutting_02
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>

