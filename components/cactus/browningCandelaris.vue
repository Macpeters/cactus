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
              <div>I planted 25 seeds from cactusstore.com.  As of May 19, nothing has germinated.</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                These guys took their sweet time, but there are 4 popping up now - it's May 27.  
                From the batch of seeds I got from cactusstore.com, all but 3 have germinated, 
                and these ones took a couple of weeks longer than anything else that's germinated.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="Browning candelaris seedlings from May 27" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/browningiaCandelaris/browningiaCandelaris.jpeg';
  import batch_01_seedlings from '../../assets/cacti/browningiaCandelaris/batch_01_seedlings.jpg';

  export default {
    head () {
      return {
        name: 'browningCandelaris',
        title: 'Browning candelaris'
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
