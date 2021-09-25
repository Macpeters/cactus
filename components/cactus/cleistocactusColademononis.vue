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
          <section>
            <h2>Plants</h2>
            <div>
              <h3>09/2021 - 4 remain</h3>
              <div>
                <p>
                  These guys weren't thriving outdoors - they drowned a little in the rain, and there
                  were some casualties.  While those remaining did grow, I'm not sure how happy they all
                  are.  I'll keep an eye out.  I hope they start to show the extreme fuzziness of the mature
                  plants soon - I'm excited to see them as they take on mature qualities.
                </p>
              </div>
              <img v-bind:src="batch_01_plants_01" alt="Echinocereus Colademononis 2021/09/12"  />
            </div>
          </section>
          <section>
            <h2>Seedlingts</h2>
            <div>
              <h3>11/2019 - 6 remain</h3>
              <div>
                <p>
                  I ordered some seeds from rareplant.me, and planted them in November, 2019.
                  There are still 6 as of August, 2020, and they seem lively enough.  I'm excited
                  to see them looking more like adults, with all that fur, and falling over the edge
                  of the pot.  So far they just look like any cactus seedling - kind of tall and
                  columnar.
                </p>
              </div>
              <img v-bind:src="batch_01_seedlings_02" alt="Echinocereus Colademononis 2020/08/21"  />
              <img v-bind:src="batch_01_seedlings_01" alt="Echinocereus Colademononis seedlings 2020/03/29"  />
            </div>
          </section>
      </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/cleistocactusColademonis/cleistocactusColademonis.jpg';
  import batch_01_seedlings_01 from '../../assets/cacti/cleistocactusColademonis/batch_01_seedlings_01.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/cleistocactusColademonis/batch_01_seedlings_02.jpg';
  import batch_01_plants_01 from '../../assets/cacti/cleistocactusColademonis/batch_01_plants_01.jpg';

  export default {
    head () {
      return {
        name: 'cleistocactus Colademononis',
        title: 'cleistocactus Colademononis'
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings_01,
        batch_01_seedlings_02,
        batch_01_plants_01
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
