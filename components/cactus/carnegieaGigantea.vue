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
                to see what these do, but also worried that they'll become gigantic very quickly.
              </div>
          </div>
           <img v-bind:src="batch_01_seedlings" alt="Carnigiea Gigantea seedlings from 18/04/2019" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/carnigieaGigantea/carnigieaGigantea.jpeg';
  import batch_01_seedlings from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings.jpg';

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
        batch_01_seedlings
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
