<template>
  <div>
    <img v-bind:src="image"  />

    <article>
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <article>
      <h2>Batch 1</h2>
      <div>
        <h3>Sowing the seeds: 04/2019</h3>
          <div>I planted 25 seeds.  It looks like 9 have germinated</div>
      </div>
      <div>
        <h3>Seedlings</h3>
          <div>
            These are odd looking seedlings - like rigid stems with a couple of tiny leaves on top.  
            All three sedum species I planted have these sorts of seedlings.
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumAdolphi.jpeg';
  export default {
    head () {
      return {
        name: 'sedumAdolphi',
        title: 'Sedum adolphi'
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
