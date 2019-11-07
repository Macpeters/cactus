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
  import image from '../../assets/succulents/lithops.jpeg';
  export default {
    head () {
      return {
        name: 'lithops',
        title: 'Lithops'
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
