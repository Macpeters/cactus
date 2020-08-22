<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        Lithops, more than any other plant species I'm growing, requires special care and
        attention.  While they'll get more water as seedlings, there are only 2 small periods
        every year when they get any water at all, and they should be in a substrate that is
        80% non-organic (gravel, pumice).  Shown below is a simplified watering schedule:
      </div>
      <div>
        <p><b>Spring:</b> when old leaves are completely absorbed by new leaves, soak thoroughly</p>
        <p><b>Summer:</b> water sparingly.  Protect from hot noon sun.  When growing, flowering: give water.</p>
        <p><b>Fall:</b> stop watering when split is showing</p>
        <p><b>Winter: </b>new leaves are feeding off old leaves - no water at all</p>
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
        <h2>Batch 01 11/2019 - 1 remains</h2>
        <div>
          <div>
            <p>
              I ordered some seeds from rareplant.me, and planted them in November, 2019.
              We'll see what happens.  The seeds were very tiny.
            </p>
            <p>
              As of 2019/11/10 I see signs of growth already.  I have had to repot these guys
              after learning about the different substrate needs.  Hopefully it wasn't too soon.
              I'm not sure if the blue gravel is too big for the little fellas.  I sprinkled a little
              more organic material on top just to give the roots something to hold on to.  I won't be surprised
              if I fail at lithops the first time around, and have to start again.
            </p>
            <p>In 08/2020, there is only a single lithops left.  I haven't seen it split yet</p>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Lithops seedlings from 2020/08/21" />
          <img v-bind:src="batch_01_seedlings_01" alt="Lithops seedlings from 2020/03/29" />
        </div>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/lithops/lithops.jpeg';
  import batch_01_seedlings_01 from '../../assets/succulents/lithops/batch_01_seedlings_01.jpg';
  import batch_01_seedlings_02 from '../../assets/succulents/lithops/batch_01_seedlings_02.jpg';

  export default {
    head () {
      return {
        name: 'lithops',
        title: 'Lithops'
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
