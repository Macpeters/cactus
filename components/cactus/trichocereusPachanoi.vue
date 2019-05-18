<template>
  <div>
     <img v-bind:src="image"  />

    <article class="main-notes">
      <h2>Notes on the species</h2>
      <div>
        Used by the indegenous people of the andes for their alkaloid content and sold in markets.There are different 'kinds'
        depending on the number of ribs. Cacti with seve ribs are the least potent and most common.
        Cacti with four ribs are rare , considered the more potent and belived to have special power because each rib
        corresponds with one of the “four winds" (4 cardinal directions), and its use dates back to 3000+ years ago.
      </div>
    </article>

    <article>
      <h2>Batch 2</h2>
      <div>
        <h3>Sowing the seeds: 04/2019</h3>
          <div>I planted 30 seeds in batches of 10 and 20. </div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            19 Seelings survive from this batch, still incubated and looking bigger and stronger than their slightly
            older siblings.
          </div>
      </div>
    </article>


    <article>
      <h2>Batch 1</h2>
      <div>
        <h3>Sowing the seeds: 03/2019</h3>
          <div>I planted 20 seeds, 9 still live</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
              This first batch was in the unfortunate group of freshly sown seeds that I knocked over.  I was surprised
              to see anything germitate.  Their little spines are adorable.  I did take them out of incubation long before
              I would have liked - I was concerned about fungus, and the baggies I used weren't sealed well around the
              2 inch clay pots - I forgot how quickly those guys can leach out moisture.  Clay is good for hardened cacti,
              but I won't use it again for seedlings without a fully sealed container.
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/cacti/trichocereusPachanoi.jpg';

  export default {
    head () {
      return {
        name: 'trichocereusPachanoi',
        title: 'Trichocereus pachanoi'
      }
    },
    data() {
      return {
        image
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
