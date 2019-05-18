<template>
  <div>
    <img v-bind:src="image"  />

    <article class="main-notes">
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
              <div>I planted 25 seeds</div>
          </div>
          <div>
            <h3>Seedlings</h3>
              <div>
              </div>
          </div>
        </article>
      </div>
     </div>   
  </div>
</template>

<script>
  import image from '../../assets/cacti/echinocactusGrusonii.jpeg';
  export default {
    head () {
      return {
        name: 'echinocactusGrusonii',
        title: 'Echinocactus grusonii'
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
