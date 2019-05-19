<template>
  <div>
    <article class="main-notes">
       <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        I don't have great hope for this species - my outdoor climate is unsuitable, and apparently
        it doesn't like indoors.  I'm going to try it anyways, since I have the seeds.
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Batch 1</h2>
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 25 seeds from cactusstore.com  It looks like 9 have germinated</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                These are odd looking seedlings - like rigid stems with a couple of tiny leaves on top.  
                All three sedum species I planted have these sorts of seedlings.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="Sedum adophi seedlings from May 19, 2019" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumAdolphi/sedumAdolphi.jpeg';
  import batch_01_seedlings from '../../assets/succulents/sedumAdolphi/batch_01_seedlings.jpg';

  export default {
    head () {
      return {
        name: 'sedumAdolphi',
        title: 'Sedum adolphi'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
