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
              <div>I planted 25 seeds from seedworld - it took a long time for them to arrive, and they were
                a mixture of species instead of a mixture of varieties, which is fine.  There were also only 75, when 
                I expected 100, which is less fine.  I'll order from a proper cactus seed retailer next time.
              </div>
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
  import image from '../../assets/cacti/astrophytumAstaria.jpeg';
  export default {
    head () {
      return {
        name: 'astrophytumAstaria',
        title: 'Astrophytum astaria'
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
