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
        <h2>Batch 01 11/2019 - 6 remain</h2>
        <div>
          <div>
            <p>
              I ordered some seeds from rareplant.me, and planted them in November, 2019.
              There are still 6 as of August, 2020, and they seem lively enough.  I'm excited
              to see them looking more like adults, with all that fur, and falling over the edge
              of the pot.  So far they just look like any cactus seedling - kind of tall and
              columnar.
            </p>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Echinocereus Colademononis 2020/08/21"  />
          <img v-bind:src="batch_01_seedlings_01" alt="Echinocereus Colademononis seedlings 2020/03/29"  />
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/cleistocactusColademonis/cleistocactusColademonis.jpg';
  import batch_01_seedlings_01 from '../../assets/cacti/cleistocactusColademonis/batch_01_seedlings_01.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/cleistocactusColademonis/batch_01_seedlings_02.jpg';

  export default {
    head () {
      return {
        name: 'cleistocactus Colademononis',
        title: 'cleistocactus Colademononis'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings_01,
        batch_01_seedlings_02
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
