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
            <div>I got this plant as an adult.  It has put out a few little pups, and I've kept
              them all together.  It's all trying to lean to one side, so I'm weighing the other 
              side down with rocks for stability.
            </div>
        </div>
        <img v-bind:src="aloe_01" alt="aloe vera as of 2019/11/10" />
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/aloeVera.jpg';
  import aloe_01 from '../../assets/succulents/aloeVera/aloeVera_01.jpg';

  export default {
    head () {
      return {
        name: 'aloeVera',
        title: 'Aloe vera'
      }
    },
    data() {
      return {
        image,
        aloe_01
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
