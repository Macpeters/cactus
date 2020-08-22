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
        <h2>11/2019 - 3 remain</h2>
        <div>
            <div>
              <p>
                I ordered some seeds from rareplant.me, and planted them in November, 2019.
                There were a bunch more, but I neglected them a bit, and many died of thirst,
                because they were too small still to handle it.
              </p>
              <p>
                These guys have enjoyed a summer outside and I've managed to keep the 3 remainders
                alive.  They are an odd looking cactus, for sure.  So tall and thin.  In any other
                species I would assume etoliation, but that's what these guys look like, plus they've
                had a lot of real sunlight.
              </p>
            </div>
            <img v-bind:src="batch_01_seedlings_02" alt="Echinocereus poselgeri seedlings 2020/08/21"  />
            <img v-bind:src="batch_01_seedlings_01" alt="Echinocereus poselgeri seedlings 2020/03/29"  />
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/echinocereusPoselgeri/echinocereusPoselgeri.jpeg';
  import batch_01_seedlings_01 from '../../assets/cacti/echinocereusPoselgeri/batch_01_seedlings_01.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/echinocereusPoselgeri/batch_01_seedlings_02.jpg';

  export default {
    head () {
      return {
        name: 'Echinocereus poselgeri',
        title: 'Echinocereus Poselgeri'
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
