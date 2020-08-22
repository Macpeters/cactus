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
        <article>
          <h2>Batch 01 04/2019 - 5 remain</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                  <p>
                    Only 6 remain in March 2020, and they haven't grown much at all. I'm not sure if these guys
                    are just super slow, or very unhappy with the life I've given them.  I've moved them a bit
                    further from the light - maybe they'll like that better.
                  </p>
                  <p>Now it's August, and there are 5 left.  They are tiny still, but some of them
                    look like proper little cactuses with bright orange spines, so they must be fairly
                    content.
                  </p>
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01" alt="Mammillaria pacifica from 2020/08/21"  />
          <img v-bind:src="batch_01_seedlings_05" alt="Mammillaria pacifica seedlings from 2020/03/29"  />
          <img v-bind:src="batch_01_seedlings_04" alt="Mammillaria pacifica seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="Mammillaria pacifica seedlings from 2019/09/17"  />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                I planted 25 seeds from cactusstore.com- 27 germinated (guess they gave me extra - I didn't actually count)
                It's still very early, but these are super tiny - barely visible.  As of July 23, they are still quite small -
                smaller than any other seedling I've got, and still just globs with no real distinguishing features.  18 Remain.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Mammillaria pacifica seedlings from 2019/07/23"  />
          <img v-bind:src="batch_01_seedlings" alt="Mammillaria pacifica seedlings from 2019/04/18"  />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/mammillariaPacifica/mammillariaPacifica.jpg';
  import batch_01_seedlings from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/mammillariaPacifica/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/mammillariaPacifica/batch_01_plants_01.jpg';

  export default {
    head () {
      return {
        name: 'mammillariaPacifica',
        title: 'Mammillaria pacifica'
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
