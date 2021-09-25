<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
       Some cultivars have red colouring - anywhere from subtle hints to entirely devoid of
       chlorophyl.  Plants without chlorophyl (entirely red/orange) will need to be grafted to
       to another cactus, such as Opuntia engelmannii
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
                Several were lost during my move in April, but the remaining plants seems strong.
                One pot spent the summer outside, and grew quite a lot larger, while the other stayed
                inside under flourescent lighting.  It's clear what a difference full sunlight makes.
              </p>
            </div>
          </section>
          <img v-bind:src="batch_02_plants_02"  alt="Astrophytum myriostigma from 2021/09/12" />

          <section>
            <h2>Seedlings</h2>
            <h3>Seedlings: 11/2019 - 10 remain</h3>
            <div>
                <p>
                  These were looking pretty orange for a few days - I moved them further from the
                  light.  The orange has largely faded.  I wouldn't mind if these turn out to have
                  some colour, but I would like to avoid having to graft until I have a bit more XP
                  with cactusing.  Even after switching to 12 hour flor lighting, they still seem
                  taller and floppier than seems right.  Maybe I just don't know astrophytum well
                  enough to say, though.
                </p>
                <p>
                  After a summer of growth, they're a bit bigger, but not remarkably.  Maybe these are
                  slow growers.  The seedling stem is now buried, so maybe I'm comparing above ground
                  growth to mostly below ground growth.  At any rate, these are the most columny
                  astrophytum, as expected.
                </p>
            </div>
          </section>
          <img v-bind:src="batch_02_plants_01"  alt="Astrophytum myriostigma from 2020/08/21" />
          <img v-bind:src="batch_02_seedlings_05"  alt="Astrophytum myriostigma seedlings from 2020/03/29" />
          <img v-bind:src="batch_02_seedlings_04"  alt="Astrophytum myriostigma seedlings from 2019/11/10" />
          <img v-bind:src="batch_02_seedlings_03"  alt="Astrophytum myriostigma seedlings from 2019/09/17" />
          <section>
            <h3>Sowing the seeds: 05/2019</h3>
            <div>I planted 25 seeds.  Actually, I ordered 100 A. astaria from Seed World
              on Amazon (they were super cheap), they took forever to show up, and then it
              was 25 each of A. astaria, A.myriostigma, and A. capricorn.  I do hope they
              actually grow, because that would give me an extra species, and an extra chance
              to see if the first batch A. myriostigma matches the second.  All 3 species in the
              order had large-ish seeds (compared to most of the other cacti I've sown), and
              they were all mostly sherical.
            </div>
          </section>
          <img v-bind:src="batch_02_seedlings_02"  alt="Astrophytum myriostigma seedlings from 2019/07/23" />
          <img v-bind:src="batch_02_seedlings"  alt="Astrophytum myriostigma seedlings from 2019/05/23" />
        </article>

        <!-- <article class="batch">
          <h2>Batch 1 - none remain</h2>
          <div>
            <h3>Seedlings: 11/2019</h3>
              <div>
                  I lost the one seedling I had left &#128546; I think in future I'll have to be more careful about
                  clearing soil from the edges of the container.  All my astrophytum seedlings grew tall and
                  thin - it's possible they like more light at that age than most cactus seedlings.  I'll try
                  again with another batch and see if I have better luck.   This one is dead.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_03"  alt="Astrophytum myriostigma seedlings from 17/09/2019" />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 10 seeds - all 10 germinated
                  These are tall columnar looking seedlings.  I was expecting short, squat, little blobs like the lopophoras.  I
                  have a strong suspicion I didn't get the seeds I ordered from Magiccactus.com.  They were labeled correctly
                  on the package.  Only time will tell what these baby cacti will become, but I'll call them Astrophytum myriostigma
                  until I have a better idea of what they actually are.  I don't love that they're growing
                  sideways, but I don't want to expose them to anything yet, so as long as they're growing, I'll
                  leave them.  I noticed a few were shrivelled.  I'm actually down to just the one, it seems.  I
                  transplanted it into a clay pot so it's easier to see and water.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02"  alt="Astrophytum myriostigma seedlings from 23/07/2019" />
          <img v-bind:src="batch_01_seedlings"  alt="Astrophytum myriostigma seedlings from 23/05/2019"/>
        </article> -->
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/astrophytumMyriostigma/astrophytumMyriostigma.jpeg';
  import batch_01_seedlings from '../../assets/cacti/astrophytumMyriostigma/batch_01_seedlings.jpg';
  import batch_02_seedlings from '../../assets/cacti/astrophytumMyriostigma/batch_02_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/astrophytumMyriostigma/batch_01_seedlings_02.jpg';
  import batch_02_seedlings_02 from '../../assets/cacti/astrophytumMyriostigma/batch_02_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/astrophytumMyriostigma/batch_01_seedlings_03.jpg';
  import batch_02_seedlings_03 from '../../assets/cacti/astrophytumMyriostigma/batch_02_seedlings_03.jpg';
  import batch_02_seedlings_04 from '../../assets/cacti/astrophytumMyriostigma/batch_02_seedlings_04.jpg';
  import batch_02_seedlings_05 from '../../assets/cacti/astrophytumMyriostigma/batch_02_seedlings_05.jpg';
  import batch_02_plants_01 from '../../assets/cacti/astrophytumMyriostigma/batch_02_plants_01.jpg';
  import batch_02_plants_02 from '../../assets/cacti/astrophytumMyriostigma/batch_02_plants_02.jpg';

  export default {
    head () {
      return {
        name: 'astrophytumMyriostigma',
        title: 'Astrophytum myriostigma'
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
        batch_02_seedlings_03,
        batch_02_seedlings_04,
        batch_02_seedlings_05,
        batch_02_plants_01,
        batch_02_plants_02
      };
    },
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
