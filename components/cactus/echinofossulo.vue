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
        <h2>11/2019 - 5 remain</h2>
        <div>
          <div>I ordered some seeds from rareplant.me, and planted them in November, 2019.
          </div>
          <img v-bind:src="batch_01_seedlings_01" alt="Echinofossulo seedlings 2019/03/29"  />
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/Echinofossulo/Echinofossulo.jpeg';
  import batch_01_seedlings_01 from '../../assets/cacti/Echinofossulo/batch_01_seedlings_01.jpg';

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
        batch_01_seedlings_01
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
