<template>
  <div>
    <img v-bind:src="image"  />


    <article>
      <h2>Notes on the species</h2>
      <div>
       These seeds had the best germ rate I've seen so far at 100%
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
