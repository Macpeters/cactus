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
        <article>
          <h2>Batch 1</h2>
          <div>
            <h3>Seedlings: 11/2019</h3>
              <div>
                  Only 6 remain at this time, and they haven't grown much at all. I'm not sure if these guys
                  are just super slow, or very unhappy with the life I've given them.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_04" alt="Mammillaria pacifica seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="Mammillaria pacifica seedlings from 2019/09/17"  />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>
                I planted 25 seeds from cactusstore.com- 27 appear to have germinated (guess they gave me extra - I didn't actually count) 
                It's still very early, but these are super tiny - barely visible.  As of July 23, they are still quite small -
                smaller than any other seedling I've got, and still just globs with no real distinguishing features.  18 Remain.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Mammillaria pacifica seedlings from 2019/07/23"  />
          <img v-bind:src="batch_01_seedlings" alt="Mammillaria pacifica seedlings from 2019/04/18"  />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/mammillariaPacifica/mammillariaPacifica.jpg';
  import batch_01_seedlings from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_04.jpg';
  
  export default {
    head () {
      return {
        name: 'mammillariaPacifica',
        title: 'Mammillaria pacifica'
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
