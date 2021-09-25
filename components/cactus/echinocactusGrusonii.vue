<template>
  <div>
    <article class="main-notes">
      <img v-bind:src="spike_02"  />
      <h2>Notes on the species</h2>
      <div>
        <p>
          Long lived, slow growing.  Plants have to be at least 14 inches across before
          they'll flower.  Sometimes they are self-fertile, but you'd get more seeds
          cross-pollinating with another plant.
        </p>
        <p>
          Keep dry in winter.  Feed high potassium fertilizer in summer. Propogate by seed.  Watch for mealybug, scale, and
          spider mite.  Once mature, repot every 2-3 years.  Not concerned about humidity.
        </p>
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <section>
            <h2>Spike</h2>
            <h3>Adult</h3>
              <div>
                <p>
                  I got this cactus from Canadian Tire, because they were actually labelled with their
                  species, and I had a few seedlings of this species, so I wanted to see an adult.  I
                  went back later to see what else they had, and everything remaining was unlabelled.  Ho hum.
                  So I have Spike, at any rate, who was going to be a work plant, until Covid.  I brought him
                  home and I've had to upgrade him a few times already.  He's growing faster than I would expect.
                  Those spines, too. They're already sticking out past the perimeter of the pot, so he's a hassle
                  to pick up. But what a cactus.  Those spines are incredible.
                </p>
              </div>
          </section>
          <img v-bind:src="spike_03" alt="echinocactus Grusonii seedlings from 2021/09/12"  />
          <img v-bind:src="spike_02" alt="echinocactus Grusonii seedlings from 2019/07/23"  />
          <img v-bind:src="spike_01" alt="echinocactus Grusonii seedlings from 2019/04/18"  />
        </article>

        <article class="batch">
          <section>
            <h2>Plants</h2>
            <div>
              <h3>09/2021 - 1 remains</h3>
              <div>
                <p>
                  This fellow has been thriving under the summer sun.  This is a strong, happy
                  cactus.
                </p>
              </div>
              <img v-bind:src="batch_01_plants_02" alt="echinocactus Grusonii from 2021/09/12"  />
            </div>
          </section>
          <section>
            <h2>Seedlings</h2>
            <div>
              <h3>04/2019 - 1 remains</h3>
                <div>
                  <p>
                    These aren't the happiest bunch of cacti I have tried to grow.  The one lonely surviver
                    looks like he'll make it though.
                  </p>
                  <p>
                    Nearing the end of summer, my lonely friend is still going strong.
                  </p>
                </div>
            </div>
            <img v-bind:src="batch_01_plants_01" alt="echinocactus Grusonii from 2020/08/21"  />
            <img v-bind:src="batch_01_seedlings_05" alt="echinocactus Grusonii seedlings from 2020/03/29"  />
            <img v-bind:src="batch_01_seedlings_04" alt="echinocactus Grusonii seedlings from 2019/11/10"  />
            <img v-bind:src="batch_01_seedlings_03" alt="echinocactus Grusonii seedlings from 2019/09/17"  />

            <div>
              <h3>Sowing the seeds</h3>
                <div>I planted 25 seeds from cactusstore.com.  4 seem to have germinated, although a couple
                  seem a little upside down. It looks like there are 10 of them, but most seem etoliated,
                  and the rest look stunted. I'm not sure I can reach in and pull the hat off that one at
                  the back without disturbing  others, so I'll leave it for now.  I don't have much faith
                  in the futures of these sad looking cacti.
                </div>
            </div>
            <img v-bind:src="batch_01_seedlings_02" alt="echinocactus Grusonii seedlings from 2019/07/23"  />
            <img v-bind:src="batch_01_seedlings" alt="echinocactus Grusonii seedlings from 2019/04/18"  />
          </section>
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import spike_01 from '../../assets/cacti/echinocactusGrusonii/spike_01.jpg';
  import spike_02 from '../../assets/cacti/echinocactusGrusonii/spike_02.jpg';
  import spike_03 from '../../assets/cacti/echinocactusGrusonii/spike_03.jpg';
  import batch_01_seedlings from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings.jpg';
  import batch_01_seedlings_02 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_02.jpg';
  import batch_01_seedlings_03 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_03.jpg';
  import batch_01_seedlings_04 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_04.jpg';
  import batch_01_seedlings_05 from '../../assets/cacti/echinocactusGrusonii/batch_01_seedlings_05.jpg';
  import batch_01_plants_01 from '../../assets/cacti/echinocactusGrusonii/batch_01_plants_01.jpg';
  import batch_01_plants_02 from '../../assets/cacti/echinocactusGrusonii/batch_01_plants_02.jpg';

  export default {
    head () {
      return {
        name: 'echinocactusGrusonii',
        title: 'Echinocactus grusonii'
      }
    },
    data() {
      return {
        spike_01,
        spike_02,
        spike_03,
        batch_01_seedlings,
        batch_01_seedlings_02,
        batch_01_seedlings_03,
        batch_01_seedlings_04,
        batch_01_seedlings_05,
        batch_01_plants_01,
        batch_01_plants_02
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
