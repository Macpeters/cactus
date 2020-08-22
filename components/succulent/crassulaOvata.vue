<template>
  <div>
    <article class="main-notes">
       <img v-bind:src="image"  />
      <h2>Notes on the species</h2>
      <div>
        Losing leaves, leaf spots = too little water.  Try propogating by leaf, or by 3-4 inch cuttings.
      </div>
    </article>

     <div class="batch-logs">
      <div class="row">
        <article class="batch">
          <h2>Leaf/Stem Cuttings: 11/2019</h2>
          <div>
              <div>
                After a massive pruning of my main adult plant, I had all sorts of pieces, and decided to plant
                them and see how much of it stuck.  The leaves and stems sat dry for a week.  Leaves showing
                root growth get slightly burried, as shown, so that new growth can peak out.  Stems with root
                growth (and even without, after a while) were burried.  I have no idea what's going on underneath,
                but everything seems fresh still.  I've thrown out a few of the smaller leaves - larger leaves
                have had much better success putting out roots.
              </div>
              <img v-bind:src="leafCutting_02" alt="leaf cuttings of crassula ovata leaf removed 2020/08/21"  />
              <img v-bind:src="leafCutting_01" alt="leaf cuttings of crassula ovata with tiny new growth 2020/11/10"  />
              <img v-bind:src="stemCutting_01" alt="stem cuttings of crassula ovata 2010/11/10"  />
          </div>
        </article>

        <article class="batch">
          <h2>Mature Plant</h2>
          <div>
            <h3>Bonsai: 11/2019</h3>
              <div>
                I found out that jade plants make good bonsai, and since this fellow is still young and
                plyable, I decided to give it a go.  I'm using pipe cleaners to tie it down, since it's the
                wrong time of year to find plastic coated wire.  I gave it a solid pruning as well, keeping all
                the pieces I cut off for propogation.  My goal is three main trunks in a spiral, with a thick,
                consistent canopy of small foliage on top.
              </div>
              <img v-bind:src="bonsai_01_01" alt="crassula ovata pruned and tied into spiral 2019/11/10 - top view" />
              <img v-bind:src="bonsai_01_02" alt="crassula ovata pruned and tied into spiral 2019/11/10 - side view"  />
          </div>
          <div>
            <h3>Rescue: 11/2019</h3>
              <div>
                I got this plant as an adult.  It had developed an odd shape, but a summer outside
                with regular turning allowed it to flush out a lot.
              </div>
              <img v-bind:src="image_01" alt="crassula ovata as of March, 2019" />
              <img v-bind:src="image_02" alt="crassula ovata closeup of leaves"  />
              <img v-bind:src="image_03" alt="crassula ovata close up of branch"  />
          </div>
        </article>
      </div>
     </div>
  </div>
</template>

<script>
  import image from '../../assets/succulents/crassulaOvata/crassulaOvata.jpg';
  import image_01 from '../../assets/succulents/crassulaOvata/crassulaOvata_01.jpg';
  import image_02 from '../../assets/succulents/crassulaOvata/crassulaOvata_02.jpg';
  import image_03 from '../../assets/succulents/crassulaOvata/crassulaOvata_03.jpg';
  import leafCutting_01 from '../../assets/succulents/crassulaOvata/leaf_cutting_01_01.jpg';
  import leafCutting_02 from '../../assets/succulents/crassulaOvata/leaf_cutting_01_02.jpg';
  import stemCutting_01 from '../../assets/succulents/crassulaOvata/stem_cutting_01_01.jpg';
  import bonsai_01_01 from '../../assets/succulents/crassulaOvata/bonsai_01_01.jpg';
  import bonsai_01_02 from '../../assets/succulents/crassulaOvata/bonsai_01_02.jpg';

  export default {
    head () {
      return {
        name: 'crassulaOvata',
        title: 'Crassula ovata'
      }
    },
    data() {
      return {
        image,
        image_01,
        image_02,
        image_03,
        leafCutting_01,
        leafCutting_02,
        stemCutting_01,
        bonsai_01_01,
        bonsai_01_02
      };
    }
  }
</script>

<style lang="css" src="../logs.css" scoped></style>
