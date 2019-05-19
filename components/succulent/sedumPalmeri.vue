<template>
  <div>
    <article class="main-notes">
       <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 25 seeds from cactusstore.com.  It looks like 12 have germinated</div>
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
     </div> 
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumPalmeri.jpeg';
  export default {
    head () {
      return {
        name: 'sedumPalmeri',
        title: 'Sedum palmeri'
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
