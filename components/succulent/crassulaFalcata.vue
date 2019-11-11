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
                We'll see what happens.
            </div>
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/crassulaFalcata.jpeg';
  export default {
    head () {
      return {
        name: 'crassula Falcata',
        title: 'Crassula Falcata'
      }
    },
    data() {
      return {
        image
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
