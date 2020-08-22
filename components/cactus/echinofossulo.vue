<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        There is a lot of variation in this genus, from wavy ribs, to fuzzy brain shapes,
        to coiled worm-like formations.  I'm not sure what species I've got here.
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
        <h2>11/2019 - 5 remain</h2>
        <div>
          <div>
            <p>
              I ordered some seeds from rareplant.me, and planted them in November, 2019.
              Now in August I can see some seedlings, and they sure look like little cacti,
              but they don't look anything like the picture I found, so I'm not sure if
              they are what they were labeled as.  Time will tell.
            </p>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Echinofossulo seedlings 2020/08/21"  />
          <img v-bind:src="batch_01_seedlings_01" alt="Echinofossulo seedlings 2020/03/29"  />
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/Echinofossulo/Echinofossulo.jpeg';
  import batch_01_seedlings_01 from '../../assets/cacti/Echinofossulo/batch_01_seedlings_01.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/Echinofossulo/batch_01_seedlings_02.jpg';

  export default {
    head () {
      return {
        name: 'Echinofossulo',
        title: 'Echinofossulo'
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
