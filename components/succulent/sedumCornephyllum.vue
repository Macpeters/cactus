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
            <h3>Seedlings: 11/2019</h3>
              <div>
                These guys are doing pretty well - they still don't look like the sample pic, but time 
                will tell
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_04" alt="Sedum cornephyllum seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Sedum cornephyllum seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>
                <p>I planted 25 seeds from cactusstore.com.  It looks like 5 have germinated</p>
                <p>
                  These are odd looking seedlings - like rigid stems with a couple of tiny leaves on top.  
                  All three sedum species I planted have these sorts of seedlings.  As of July, they are
                  definitely looking more like tiny succulents.  These are thriving the most, from the sedum 
                  species I planted in May.  Looks like 19?  Hard to count these guys.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Sedum cornephyllum seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Sedum cornephyllum seedlings from 2019/05/19" />
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
  import batch_01_seedlings_04 from '../../assets/succulents/sedumCornephyllum/batch_01_seedlings_04.jpg';

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
        batch_01_seedlings_03,
        batch_01_seedlings_04
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
