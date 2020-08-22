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
          <h2>04/2019 - 9 remaining</h2>
          <div>
            <h3>Seedlings: 11/2019</h3>
              <div>
                <p>
                  I've moved these guys into 2 tiny clay pots - there are 10 remaining.  They do get
                  red super easily when directly under the florescent light.  I've been trying to keep them
                  at a bit of a distance.  The odd shape the seedlings had has been topped with either a
                  globular or columnar cactusy looking growth.  I've begun to think the initial growth that
                  all these seedlings get (a long stem and maybe wings) is meant to be burried once they grow bigger.
                </p>
                <p>
                  I don't even recognize these guys anymore.  They were such distinctive seedlings, but now that
                  the seedling stem is buried, they just look incredibly pointy.  Props to them for that remarkable
                  pointiness, though.  Are they more pointy than e. Grusonii?  Time will tell.
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01" alt="Carnigiea Gigantea from 2020/08/21" />
          <img v-bind:src="batch_01_seedlings_05" alt="Carnigiea Gigantea seedlings from 2020/03/29" />
          <img v-bind:src="batch_01_seedlings_04" alt="Carnigiea Gigantea seedlings from 2019/11/10" />
          <img v-bind:src="batch_01_seedlings_03" alt="Carnigiea Gigantea seedlings from 2019/09/17" />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                <p>
                  I planted 25 seeds, purchased from cactusstore.com.  16 germinated and they're the biggest
                seedlings I've seen, even compared with some I planted last year.  They have an interesting shape
                to them, as well.  I'm excited to see what these do, but also worried that they'll become gigantic
                very quickly. I'm seeing some yellow/orange colour - I've moved them around a bit, not sure if they want
                more light or less.
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
  import batch_01_seedlings_05 from '../../assets/cacti/carnigieaGigantea/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/carnigieaGigantea/batch_01_plants_01.jpg';

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
        batch_01_seedlings_04,
        batch_01_seedlings_05,
        batch_01_plants_01
      };
    }
  }
</script>

<style lang="css" src="../miniLog.css" scoped></style>
