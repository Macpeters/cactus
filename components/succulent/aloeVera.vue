<template>
  <div>
    <img v-bind:src="image"  />

    <article>
      <h2>Notes on the species</h2>
      <div>
      </div>
    </article>

    <article>
      <h2>Mature Plant</h2>
      <div>
          <div>I got this plant as an adult.  It has put out a few little pups, and I've kept
            them all together.  It's all trying to lean to one side, so I'm weighing the other 
            side down with rocks for stability.
          </div>
      </div>
    </article>
  </div>
</template>

<script>
  import image from '../../assets/succulents/aloeVera.jpg';
  export default {
    head () {
      return {
        name: 'aloeVera',
        title: 'Aloe vera'
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
