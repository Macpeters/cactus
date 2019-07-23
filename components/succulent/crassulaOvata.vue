<template>
  <div>
    <article class="main-notes">
       <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        Losing leaves, leaf spots = too little water.  Try propogating by leaf, or by 3-4 inch cuttings.
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Mature Plant</h2>
          <div>
              <div>I got this plant as an adult.  It's developed an odd shape, and I'm trying to get it
                to even out a bit, but we'll see what happens.  It is very top-heavy, and I'm using
                rocks to weigh the pot down.
              </div>
              <img v-bind:src="image_02"  />
              <img v-bind:src="image_03"  />
          </div>
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/crassulaOvata/crassulaOvata.jpg';
  import image_02 from '../../assets/succulents/crassulaOvata/crassulaOvata_02.jpg';
  import image_03 from '../../assets/succulents/crassulaOvata/crassulaOvata_03.jpg';

  export default {
    head () {
      return {
        name: 'crassulaOvata',
        title: 'Crassula ovata'
      }
    },
    data() {
      return {
        image,
        image_02,
        image_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
