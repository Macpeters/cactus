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
                A couple of months later, and this does not look like a happy group of cacti.  Of 
                those remaining, almost all are falling over, or shrivelled.  I'm not sure if any 
                will survive.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="Browning candelaris seedlings from 27/05/2019" />
          <img v-bind:src="batch_01_seedlings_02" alt="Browning candelaris seedlings from 23/07/2019" />
          <img v-bind:src="batch_01_seedlings_03" alt="Browning candelaris seedlings from 17/09/2019" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/browningiaCandelaris/browningiaCandelaris.jpeg';
  import batch_01_seedlings from '../../assets/cacti/browningiaCandelaris/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/browningiaCandelaris/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/browningiaCandelaris/batch_01_seedlings_03.jpg';

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
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
