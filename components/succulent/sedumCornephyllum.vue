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
              <div>I planted 25 seeds from cactusstore.com.  It looks like 5 have germinated</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                These are odd looking seedlings - like rigid stems with a couple of tiny leaves on top.  
                All three sedum species I planted have these sorts of seedlings.  As of July, they are
                definitely looking more like tiny succulents.  These are thriving the most, from the sedum 
                species I planted in May.  Looks like 19?  Hard to count these guys.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings" alt="Sedum cornephyllum seedlings from 19/05/2019" />
          <img v-bind:src="batch_01_seedlings_02" alt="Sedum cornephyllum seedlings from 23/07/2019" />
          <img v-bind:src="batch_01_seedlings_03" alt="Sedum cornephyllum seedlings from 17/09/2019" />
        </article>
      </div>
     </div>    
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumCornephyllum/sedumCornephyllum.jpg';
  import batch_01_seedlings from '../../assets/succulents/sedumCornephyllum/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/succulents/sedumCornephyllum/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/succulents/sedumCornephyllum/batch_01_seedlings_03.jpg';

  export default {
    head () {
      return {
        name: 'sedumCornyphylum',
        title: 'Sedum cornyphylum'
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
