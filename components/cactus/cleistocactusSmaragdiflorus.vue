<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        <p>
          Cleistocactus means "closed" or "hidden".  The flowers are narrow and barely open.  Genus is found in Argentina,
          Bolivia, Ecuador, and Peru.  The flowers of Cleistocactus are hummingbird pollinated.  These species also
          have a cephalium, which is where flowering occurs.  It is a specialized area with bristly, wolly, or woody growth.
        </p>
        <p>
          Water this like a succulent.  It is recommended outdoors, but will grow indoors.
          Keep dry in winter.  Repot in the spring.
          One of the hardiest wolly columnar cacti from Bolivia.  Frost resistant.  Doesn't care for extremely high temperatures
          in summer.  Propogated by seed or cutting.
        </p>
      </div>
    </article>

    <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>04/2019 - 15 remain</h2>
          <div>
            <h3>Seedlings</h3>
              <div>
                <p>
                  I love how these guys are thriving.  Is this  an easier cactus to grow?  Does it
                  just love the conditions I'm providing?  I've planted a second cleistocactus species -
                  so I'll see if the genus in general is this prolific.
                </p>
                <p>
                  The summer is nearly over, and I've only had a single loss since March.  These guys
                  are strong and hardy, and I'm super happy at how well they've done.  The next step will be
                  to
                </p>
              </div>
          </div>
          <img v-bind:src="batch_01_plants_01" alt="Cleistocactus smaragdiflorus from 2020/08/21"  />
          <img v-bind:src="batch_01_seedlings_05" alt="Cleistocactus smaragdiflorus seedlings from 2020/03/29"  />
          <img v-bind:src="batch_01_seedlings_04" alt="Cleistocactus smaragdiflorus seedlings from 2019/11/10"  />
          <img v-bind:src="batch_01_seedlings_03" alt="Cleistocactus smaragdiflorus seedlings from 2019/09/17"  />
          <div>
            <h3>Sowing the seeds</h3>
              <div>
                I planted 25 seeds from cactusstore.com, 18 germinated.
                I'm really glad these guys are doing so well - it looks like there are 18 of them,
                all perky, with little spikes growing.  There's a little red at the base of a few,
                which I want to keep an eye on.  I've moved them around a bit - they seem senstive
                to the light still.
              </div>
          </div>
          <img v-bind:src="batch_01_seedlings_02" alt="Cleistocactus smaragdiflorus seedlings from 2019/07/23"  />
          <img v-bind:src="batch_01_seedlings" alt="Cleistocactus smaragdiflorus seedlings from 2019/04/18"  />
        </article>
      </div>
    </div>
  </div>
</template>

<script>
  import image from '../../assets/cacti/cleistocactusSmaragdiflorus/cleistocactusSmaragdiflorus.jpeg';
  import batch_01_seedlings from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/cleistocactusSmaragdiflorus/batch_01_plants_01.jpg';

  export default {
    head () {
      return {
        name: 'cleistocactusSmaragdiflorus',
        title: 'Cleistocactus smaragdiflorus'
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
