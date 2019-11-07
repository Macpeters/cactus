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
                All three sedum species I planted have these sorts of seedlings.  Looks like maybe 12
                are doing okay, with a handful of others that are... trying.  I never had much hope 
                for them to grow well indoors.  
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_03" alt="Sedum adophi seedlings from 17/09/2019" />
          <img v-bind:src="batch_01_seedlings_02" alt="Sedum adophi seedlings from 23/07/2019" />
          <img v-bind:src="batch_01_seedlings" alt="Sedum adophi seedlings from 19/05/2019" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumAdolphi/sedumAdolphi.jpeg';
  import batch_01_seedlings from '../../assets/succulents/sedumAdolphi/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/succulents/sedumAdolphi/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/succulents/sedumAdolphi/batch_01_seedlings_03.jpg';

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
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
