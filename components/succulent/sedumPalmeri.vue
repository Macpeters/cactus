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
          <h2>Batch 1</h2>
          <div>
            <h3>Seedlings: 11/2019</h3>
              <div>
                <p>
                  I have moved these into a wide, shallow clay pot, and all on their own they've taken over
                  the whole thing.  They still have room to grow, so I can leave them alone, but I'm really impressed
                  with how well they have been growing.
                </p>
                <p>
                  These guys are doing fantastic - I'm really excited to see how they progress.  I have had
                  to divide them into three separate containers - the biggest one is on its own and
                  will likely outgrow the small pot in a few months at this rate.  I haven't seen any of the bright red
                  I am expecting - but maybe they have to flower for that?
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01" alt="Sedum palmeri from 2020/08/21" />
          <img v-bind:src="batch_01_seedlings_05" alt="Sedum palmeri seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Sedum palmeri seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Sedum palmeri seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>
                <p>I planted 25 seeds from cactusstore.com.  It looks like 12 have germinated</p>
                <p>
                  These are odd looking seedlings - like rigid stems with a couple of tiny leaves on top.
                  All three sedum species I planted have these sorts of seedlings.  As of July, these look
                  very etoliated.  I'm not sure they can recover, in that case.  If this is how they're
                  suppose to grow, then maybe they'll survive.  I'd really like them to.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Sedum palmeri seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Sedum palmeri seedlings from 2019/05/19" />
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumPalmeri/sedumPalmeri.jpeg';
  import batch_01_seedlings from '../../assets/succulents/sedumPalmeri/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/succulents/sedumPalmeri/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/succulents/sedumPalmeri/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/succulents/sedumPalmeri/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/succulents/sedumPalmeri/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/succulents/sedumPalmeri/batch_01_plants_01.jpg';

  export default {
    head () {
      return {
        name: 'sedumPalmeri',
        title: 'Sedum palmeri'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        batch_01_seedlings_04,
        batch_01_seedlings_05,
        batch_01_plants_01
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
