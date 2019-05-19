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
          <h2>Mature Plant</h2>
          <div>
              <div>I got this plant as an adult.  It's developed an odd shape, and I'm trying to get it
                to even out a bit, but we'll see what happens.  It is very top-heavy, and I'm using
                rocks to weigh the pot down.
              </div>
          </div>
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/crassulaOvata.jpg';
  export default {
    head () {
      return {
        name: 'crassulaOvata',
        title: 'Crassula ovata'
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
