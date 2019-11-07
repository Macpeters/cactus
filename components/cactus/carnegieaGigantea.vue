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
              <div>
                I planted 25 seeds, purchased from cactusstore.com
              </div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
                16/25 have germinated and they're the biggest seedlings I've got, even compared with those
                I planted last year.  They have an interesting shape to them, as well.  I'm excited
                to see what these do, but also worried that they'll become gigantic very quickly.  June 23 
                checkin shows some yellow/orange colour - I've moved them around a bit, not sure if they want
                more light or less.  There are a few that look like they're really struggling, but most 
                appear to be thriving.  All 16 are still there.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_03" alt="Carnigiea Gigantea seedlings from 17/09/2019" />
          <img v-bind:src="batch_01_seedlings_02" alt="Carnigiea Gigantea seedlings from 23/07/2019" />
          <img v-bind:src="batch_01_seedlings" alt="Carnigiea Gigantea seedlings from 18/04/2019" />  
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/carnigieaGigantea/carnigieaGigantea.jpeg';
  import batch_01_seedlings from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings_03.jpg';

  export default {
    head () {
      return {
        name: 'carnegieaGigantea',
        title: 'Carnegiea gigantea',
        data() { return {} },
        meta: [
          { hid: 'description', name: 'description', content: "See what cacti I'm growing" }
        ]
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
