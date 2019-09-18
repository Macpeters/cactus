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
          <h2>Batch 2</h2>
          <div>
            <h3>Sowing the seeds: 05/2019</h3>
              <div>I planted 25 seeds.  Actually, I ordered 100 A. astaria from Seed World 
                on Amazon (they were super cheap), they took forever to show up, and then it 
                was 25 each of A. astaria, A.myriostigma, and A. capricorn.  I do hope they
                actually grow, because that would give me an extra species, and an extra chance
                to see if the first batch A. myriostigma matches the second.  All 3 species in the
                order had large-ish seeds (compared to most of the other cacti I've sown), and
                they were all mostly sherical.
              </div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                  These were looking pretty orange for a few days - I moved them further from the
                  light.  The orange has largely faded.  I wouldn't mind if these turn out to have
                  some colour, but I would like to avoid having to graft until I have a bit more XP
                  with cactusing.  Even after switching to 12 hour flor lighting, they still seem 
                  taller and floppier than seems right.  Maybe I just don't know astrophytum well 
                  enough to say, though.
              </div>
          </div>
           <img v-bind:src="batch_02_seedlings"  alt="Astrophytum myriostigma seedlings from 23/05/2019" />
           <img v-bind:src="batch_02_seedlings_02"  alt="Astrophytum myriostigma seedlings from 23/07/2019" />
           <img v-bind:src="batch_02_seedlings_03"  alt="Astrophytum myriostigma seedlings from 17/09/2019" />
        </article>

        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 10 seeds - all 10 germinated</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                  These are tall columnar looking seedlings.  I was expecting short, squat, little blobs like the lopophoras.  I
                  have a strong suspicion I didn't get the seeds I ordered from Magiccactus.com.  They were labeled correctly 
                  on the package.  Only time will tell what these baby cacti will become, but I'll call them Astrophytum myriostigma 
                  until I have a better idea of what they actually are.  I don't love that they're growing
                  sideways, but I don't want to expose them to anything yet, so as long as they're growing, I'll 
                  leave them.  I noticed a few were shrivelled.  I'm actually down to just the one, it seems.  I 
                  transplanted it into a clay pot so it's easier to see and water.
              </div>
          </div>
           <img v-bind:src="batch_01_seedlings"  alt="Astrophytum myriostigma seedlings from 23/05/2019"/>
           <img v-bind:src="batch_01_seedlings_02"  alt="Astrophytum myriostigma seedlings from 23/07/2019" />
           <img v-bind:src="batch_01_seedlings_03"  alt="Astrophytum myriostigma seedlings from 17/09/2019" />
        </article>
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
        batch_02_seedlings_03
      };
    },
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
