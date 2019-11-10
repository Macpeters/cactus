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
                I've moved these guys into 2 tiny clay pots - there are 10 remaining.  They do get 
                red super easily when directly under the florescent light.  I've been trying to keep them
                at a bit of a distance.  The odd shape the seedlings had has been topped with either a 
                globular or columnar cactusy looking growth.  I've begun to thing the initial growth that
                all these seedlings get (a long stem and maybe 2 wings) is meant to be burried once they grow bigger.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_04" alt="Carnigiea Gigantea seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Carnigiea Gigantea seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds: 04/2019</h3>
              <div>
                <p>
                  I planted 25 seeds, purchased from cactusstore.com.  16/25 have germinated and they're the biggest 
                seedlings I've got, even compared with those I planted last year.  They have an interesting shape 
                to them, as well.  I'm excited to see what these do, but also worried that they'll become gigantic 
                very quickly.  
                </p>
                <p>
                  June 23 - checking shows some yellow/orange colour - I've moved them around a bit, not sure if they want
                more light or less.  There are a few that look like they're really struggling, but most 
                appear to be thriving.  All 16 are still there.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Carnigiea Gigantea seedlings from 2019/07/23" />
          <img v-bind:src="batch_01_seedlings" alt="Carnigiea Gigantea seedlings from 2019/04/18" /> 
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/carnigieaGigantea/carnigieaGigantea.jpeg';
  import batch_01_seedlings from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings_04.jpg';

  export default {
    head () {
      return {
        name: 'carnegieaGigantea',
        title: 'Carnegiea gigantea',
        data() { return {} },
        meta: [
          { hid: 'description', name: 'description', content: "See what cacti I'm growing" }
        ]
      }
    },
    data() {
      return {
        image,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        batch_01_seedlings_04
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
