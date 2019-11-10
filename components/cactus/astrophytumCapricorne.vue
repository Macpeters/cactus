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
                There are still a good 25 of these remaining - I'm pretty happy with the success rate of
                these guys.  They're starting to thicken up a bit, which is also goood.  All the astrophytum
                began super tall and thin, and I'm happy to see them beginning to look like I expect them to
                at maturity. 
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_04" alt="Astrophytum capricorne seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Astrophytum capricorne seedlings from 2019/09/17" />
          
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>I planted 25 seeds from seedworld.  I'm counting close to 30 seedlings - there must have been more than 25 seeds in the
                pack.  Some of them still have seed hats.  There are still plenty kicking, and 
                they look lively enough.  
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Astrophytum capricorne seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Astrophytum capricorne seedlings from 2019/05/23" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/astrophytumCapricorne/astrophytumCapricorne.jpeg';
  import batch_01_seedlings from '../../assets/cacti/astrophytumCapricorne/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/astrophytumCapricorne/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/astrophytumCapricorne/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/astrophytumCapricorne/batch_01_seedlings_04.jpg';

  export default {
    head () {
      return {
        name: 'astrophytumCapricorne',
        title: 'Astrophytum capricorne'
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
