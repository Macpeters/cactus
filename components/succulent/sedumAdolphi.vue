<template>
  <div>
    <article class="main-notes">
       <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        I don't have great hope for this species - my outdoor climate is unsuitable, and apparently
        it doesn't like indoors.  I'm going to try it anyways, since I have the seeds.
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Batch 01 05/2019 - 6 remain</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                <p>
                  Of the three sedum species I planted, this one is lagging far behind.  It's growing, but
                  very slowly.  I wasn't expecting it to thrive indoors, so that's fine, I guess.  I do
                  feel bad for the little guys - I wouldn't try growing them again.  I'm actually surprised
                  by how well it's doing, given that it doesn't like indoors.  I'll stick it outside as
                  soon as it's warm enough - it might do much better out there.  There are 10 as of 2019/11
                </p>
                <p>
                  Well, outside hasn't done a damn thing for these guys.  I don't even know why they're
                  still alive.  It doesn't look like they want to be.  Only 6 remain.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01" alt="Sedum adophi from 2020/08/21" />
          <img v-bind:src="batch_01_seedlings_05" alt="Sedum adophi seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Sedum adophi seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Sedum adophi seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                <p>I planted 25 seeds from cactusstore.com  It looks like 9 have germinated</p>
                <p>
                   These are odd looking seedlings - like rigid stems with a couple of tiny leaves on top.
                  All three sedum species I planted have these sorts of seedlings.  Looks like maybe 12
                  are doing okay, with a handful of others that are... trying.  I never had much hope
                  for them to grow well indoors.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Sedum adophi seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Sedum adophi seedlings from 2019/05/19" />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/sedumAdolphi/sedumAdolphi.jpeg';
  import batch_01_seedlings from '../../assets/succulents/sedumAdolphi/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/succulents/sedumAdolphi/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/succulents/sedumAdolphi/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/succulents/sedumAdolphi/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/succulents/sedumAdolphi/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/succulents/sedumAdolphi/batch_01_plants_01.jpg';

  export default {
    head () {
      return {
        name: 'sedumAdolphi',
        title: 'Sedum adolphi'
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
