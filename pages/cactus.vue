<template>
  <div>
    <h1>Current Cactus List</h1>

      <ul>
         <span v-for="cactus in list" :key='cactus.slug'>
          <li><a href="#" @click='choose(cactus)'>{{cactus.latin_name}}</a></li>
        </span>
      </ul>

    <span v-if="!cactus.slug">Click to view details for any species</span>
    <span v-else> <cactusDetails :cactus=cactus />  </span>


    <span v-if="cactus.slug=='astrophytum_myriostigma'"><astrophytumMyriostigma /></span>
    <span v-if="cactus.slug=='carnegiea_gigantea'"><carnegieaGigantea /></span>
    <span v-if="cactus.slug=='lopophora_williamsii'"><lopophoraWilliamsii /></span>
    <span v-if="cactus.slug=='mammillaria_pacifica'"><mammillariaPacifica /></span>
    <span v-if="cactus.slug=='opuntia_engelmannii'"><opuntiaEngelmannii /></span>
    <span v-if="cactus.slug=='trichocereus_bridgisii'"><trichocereusBridgesii /></span>
    <span v-if="cactus.slug=='trichocereus_pachanoi'"><trichocereusPachanoi /></span>
    <span v-if="cactus.slug=='trichocereus_peruvianus'"><trichocereusPeruvianus /></span>


  </div>
</template>

<script>
  import list from '../assets/cactus.json';
  import cactusDetails from "../components/details.vue"
  import astrophytumMyriostigma from "../components/cactus/astrophytumMyriostigma.vue"
  import carnegieaGigantea from "../components/cactus/carnegieaGigantea.vue"
  import lopophoraWilliamsii from "../components/cactus/lopophoraWilliamsii.vue"
  import mammillariaPacifica from "../components/cactus/mammillariaPacifica.vue"
  import opuntiaEngelmannii from "../components/cactus/opuntiaEngelmannii.vue"
  import trichocereusBridgesii from "../components/cactus/trichocereusBridgesii.vue"
  import trichocereusPachanoi from "../components/cactus/trichocereusPachanoi.vue"
  import trichocereusPeruvianus from "../components/cactus/trichocereusPeruvianus.vue"

  export default {
    components: {
      list,
      cactusDetails,
      astrophytumMyriostigma,
      carnegieaGigantea,
      lopophoraWilliamsii,
      mammillariaPacifica,
      opuntiaEngelmannii,
      trichocereusBridgesii,
      trichocereusPachanoi,
      trichocereusPeruvianus
    },
    data() {
      return {
        cactus: {
          slug: null
        },
        list: list
      };
    },
    methods: {
      choose(cactus) {
        this.cactus = cactus;
        console.log(this.cactus.slug)
      }
    },
    head () {
      return {
        title: 'Cactus',
        data() { return {} },
        meta: [
          { hid: 'description', name: 'description', content: "See what cacti I'm growing" }
        ]
      }
    }
  }
</script>

<style>
  li {
    display: inline;
    padding: 5px;
    font-weight: 800;
  }

  th, td {
    padding: 5px;
  }

  h2, h3 {
    text-align: center;
    font-weight: bold
  }

  .container {
    width: 80%;
    padding: 5%;
  }

  article {
    padding: 5px;
    margin-top: 15px;
  }
</style>
