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
              <div>I got this plant as an adult.  It had developed an odd shape, but a summer outside
                with regular turning allowed it to flush out a lot. 
              </div>
              <img v-bind:src="image_01" alt="crassula ovata as of March, 2019" />
              <img v-bind:src="image_02" alt="crassula ovata closeup of leaves"  />
              <img v-bind:src="image_03" alt="crassula ovata close up of branch"  />
          </div>
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/crassulaOvata/crassulaOvata.jpg';
  import image_01 from '../../assets/succulents/crassulaOvata/crassulaOvata_01.jpg';
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
        image_01,
        image_02,
        image_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
