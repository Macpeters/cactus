<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        Used by the indegenous people of the andes for their alkaloid content and sold in markets.There are different 'kinds'
        depending on the number of ribs. Cacti with seve ribs are the least potent and most common.
        Cacti with four ribs are rare , considered the more potent and belived to have special power because each rib
        corresponds with one of the “four winds" (4 cardinal directions), and its use dates back to 3000+ years ago.  All
        my trich seeds are from Magiccactus.com, currently
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <section>
            <h2>Plants</h2>
            <h3>09/2021 - 18 remain</h3>
            <div>
              <p>
                I may soon have to remove the larger ones from the one most crowded pot - perhaps
                that will encourage the smaller ones to try growing a little.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_02_plants_02" alt="Trichocereus pachanoi from 2021/09/12" />

          <section>
            <h3>05/2019 - 18 remain</h3>
            <div>
              <p>
                I'm not sure why these are growing slower than the other trichocereus species,
                and it seems fewer have survived as well.  I may need to try another batch of these in
                the future.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_plants_01" alt="Trichocereus pachanoi from 2020/08/21" />


          <section>
            <h2>Seedlings</h2>
            <h3>03/2020</h3>
            <div>
              <p>
                These are looking sturdy.  I have to now be more careful about how often I water - I've lost
                a couple 2 rot.  They can no longer get the same care I gave to them when they were seedlings,
                so it's time to start treating them like tiny but mature plants.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_02_seedlings_05" alt="Trichocereus pachanoi seedlings from 2020/03/29" />
          <img v-bind:src="batch_02_seedlings_04" alt="Trichocereus pachanoi seedlings from 2019/11/10" />
          <img v-bind:src="batch_02_seedlings_03" alt="Trichocereus pachanoi seedlings from 2019/09/17" />

          <section>
            <h3>Sowing the seeds</h3>
            <div>
              <p>
                I planted 30 seeds in batches of 10 and 20. 19 Seelings germinated from this batch, still incubated and looking bigger and stronger than their slightly
              older siblings.  As of July 23, 18 still live, out of incubation</p>
            </div>
          </section>
          <img v-bind:src="batch_02_seedlings_02" alt="Trichocereus pachanoi seedlings from 2019/07/23" />
          <img v-bind:src="batch_02_seedlings" alt="Trichocereus pachanoi seedlings from 2019/04/18" />
        </article>

        <article class="batch">
          <section>
            <h2>Plants</h2>
            <h3>09/2021 - 5 remain</h3>
            <div>
              <p>
                These guys are definitely looking a bit crowded.  I'll have to break them up into
                separate pots. I'm glad they've grown, though.  The summer did them good.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_01_plants_02" alt="Trichocereus pachanoi from 2021/09/12" />

          <section>
            <h2>Seedlings</h2>
            <h3>03/18 - 5 remain</h3>
            <div>
              <p>
                All the T Pachanois seem smaller - shorter and stalkier, than the other Trichocereus
                  species I've got.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_01_seedlings_05" alt="Trichocereus pachanoi seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Trichocereus pachanoi seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Trichocereus pachanoi seedlings from 2019/09/17" />

          <section>
            <h3>Sowing the seeds</h3>
            <div>
                <p>I planted 20 seeds, 9 germinated</p>
                <p>
                  This first batch was in the unfortunate group of freshly sown seeds that I knocked over.  I was surprised
                  to see anything germitate.  Their little spines are adorable.  I did take them out of incubation long before
                  I would have liked - I was concerned about fungus, and the baggies I used weren't sealed well around the
                  2 inch clay pots - I forgot how quickly those guys can leach out moisture.  Clay is good for hardened cacti,
                  but I won't use it again for seedlings without a fully sealed container.
                </p>
                <p>As of July 23, 8 still live.</p>
              </div>
          </section>
          <img v-bind:src="batch_01_seedlings_02" alt="Trichocereus pachanoi seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Trichocereus pachanoi seedlings from 2019/04/18" />
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusPachanoi/trichocereusPachanoi.jpg';
  import batch_01_seedlings from '../../assets/cacti/trichocereusPachanoi/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/trichocereusPachanoi/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/trichocereusPachanoi/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/trichocereusPachanoi/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/trichocereusPachanoi/batch_01_seedlings_05.jpg';


  import batch_02_seedlings from '../../assets/cacti/trichocereusPachanoi/batch_02_seedlings.jpg';
  import batch_02_seedlings_02 from '../../assets/cacti/trichocereusPachanoi/batch_02_seedlings_02.jpg';
  import batch_02_seedlings_03 from '../../assets/cacti/trichocereusPachanoi/batch_02_seedlings_03.jpg';
  import batch_02_seedlings_04 from '../../assets/cacti/trichocereusPachanoi/batch_02_seedlings_04.jpg';
  import batch_02_seedlings_05 from '../../assets/cacti/trichocereusPachanoi/batch_02_seedlings_05.jpg';

  import batch_plants_01 from '../../assets/cacti/trichocereusPachanoi/batch_plants_01.jpg';

  import batch_01_plants_02 from '../../assets/cacti/trichocereusPachanoi/batch_01_plants_02.jpg';
  import batch_02_plants_02 from '../../assets/cacti/trichocereusPachanoi/batch_02_plants_02.jpg';

  export default {
    head () {
      return {
        name: 'trichocereusPachanoi',
        title: 'Trichocereus pachanoi'
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
        batch_02_seedlings,
        batch_02_seedlings_02,
        batch_02_seedlings_03,
        batch_02_seedlings_04,
        batch_02_seedlings_05,
        batch_plants_01,
        batch_01_plants_02,
        batch_02_plants_02
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
