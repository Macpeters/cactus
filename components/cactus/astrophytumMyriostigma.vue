<template>
  <div>
    <img v-bind:src="image"  />


    <article>
      <h2>Notes on the species</h2>
      <div>
       These seeds had the best germ rate at 100%
      </div>
    </article>

    <article>
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
          </div>
      </div>
    </article>

    <article>
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
              until I have a better idea of what they actually are.
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/astrophytumMyriostigma.jpeg';

  export default {
    head () {
      return {
        name: 'astrophytumMyriostigma',
        title: 'Astrophytum myriostigma'
      }
    },
    data() {
      return {
        image
      };
    },
  }
</script>

<style lang="css" src="./logs.css" scoped></style>
