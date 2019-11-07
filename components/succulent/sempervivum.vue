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
        <h2>Seeds</h2>
        <div>
            <div>I ordered some seeds from rareplant.me, and planted them in November, 2019.  
                We'll see what happens.  The seeds were very tiny.
            </div>
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sempervivum.jpeg';
  export default {
    head () {
      return {
        name: 'sempervivum',
        title: 'Sempervivum'
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
