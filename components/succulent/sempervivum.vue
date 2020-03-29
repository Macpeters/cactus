<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the genus</h2>
      <div>
          With no known side-effects, drinking juice of the leaf or eating the leaves directly
          can stop bad cases of diarrhea, and the juice is often applied to skin
          with the same purpose as aloe for burns, warts, insect bites.
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
        <h2>11/19 - 5 remain</h2>
        <div>
          <div>I ordered some seeds from rareplant.me, and planted them in November, 2019.
              We'll see what happens.  As of 2019/11/10 I see signs of growth already.
          </div>
          <img v-bind:src="batch_01_seedlings_01" alt="Sempervivum seedlings from 2020/03/29" />
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sempervivum/sempervivum.jpeg';
  import batch_01_seedlings_01 from '../../assets/succulents/sempervivum/batch_01_seedlings_01.jpg';

  export default {
    head () {
      return {
        name: 'sempervivum',
        title: 'Sempervivum'
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
