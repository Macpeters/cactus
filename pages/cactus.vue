<template>
  <div class="container">
    <div class="left-column">
      <ul>
         <span v-for="cactus in list" :key='cactus.slug'>
          <li><a href="#" @click='choose(cactus)'>{{cactus.latin_name}}</a></li>
        </span>
      </ul>
    </div>

    <div>
      <span v-if="!cactus.slug">Click to view details for any species</span>
      <span v-else> <cactusDetails :cactus=cactus />  </span>

      <span v-if="cactus.slug=='armatocereus_rauhii'"><armatocereusRauhii /></span>
      <span v-if="cactus.slug=='astrophytumn_astaria'"><astrophytumAstaria /></span>
      <span v-if="cactus.slug=='astrophytum_myriostigma'"><astrophytumMyriostigma /></span>
      <span v-if="cactus.slug=='brasilicactus_haselbergii'"><brasilicactusHaselbergii /></span>
      <span v-if="cactus.slug=='browning_candelaris'"><browningCandelaris /></span>
      <span v-if="cactus.slug=='carnegiea_gigantea'"><carnegieaGigantea /></span>
      <span v-if="cactus.slug=='cleistocactus_smaragdiflorus'"><cleistocactusSmaragdiflorus /></span>
      <span v-if="cactus.slug=='echinocactus_grusonii'"><echinocactusGrusonii /></span>
      <span v-if="cactus.slug=='echinocereus_coccineus'"><echinocereusCoccineus /></span>
      <span v-if="cactus.slug=='gymnocalycium_pflanzii'"><gymnocalyciumPflanzii /></span>
      <span v-if="cactus.slug=='lopophora_williamsii'"><lopophoraWilliamsii /></span>
      <span v-if="cactus.slug=='mammillaria_pacifica'"><mammillariaPacifica /></span>
      <span v-if="cactus.slug=='opuntia_engelmannii'"><opuntiaEngelmannii /></span>
      <span v-if="cactus.slug=='schlumbergera_truncata'"><schlumbergaTruncata /></span>
      <span v-if="cactus.slug=='trichocereus_bridgisii'"><trichocereusBridgesii /></span>
      <span v-if="cactus.slug=='trichocereus_pachanoi'"><trichocereusPachanoi /></span>
      <span v-if="cactus.slug=='trichocereus_peruvianus'"><trichocereusPeruvianus /></span>
    </div>

  </div>
</template>

<script>
  import list from '../assets/cactus.json';
  import cactusDetails from "../components/details.vue"
  
  import armatocereusRauhii from "../components/cactus/armatocereusRauhii.vue"
  import astrophytumAstaria from "../components/cactus/astrophytumAstaria.vue"
  import astrophytumMyriostigma from "../components/cactus/astrophytumMyriostigma.vue"
  import brasilicactusHaselbergii from "../components/cactus/brasilicactusHaselbergii.vue"
  import browningCandelaris from "../components/cactus/browningCandelaris.vue"
  import carnegieaGigantea from "../components/cactus/carnegieaGigantea.vue"
  import cleistocactusSmaragdiflorus from "../components/cactus/cleistocactusSmaragdiflorus.vue"
  import echinocactusGrusonii from "../components/cactus/echinocactusGrusonii.vue"
  import echinocereusCoccineus from "../components/cactus/echinocereusCoccineus.vue"
  import gymnocalyciumPflanzii from "../components/cactus/gymnocalyciumPflanzii.vue"
  import lopophoraWilliamsii from "../components/cactus/lopophoraWilliamsii.vue"
  import mammillariaPacifica from "../components/cactus/mammillariaPacifica.vue"
  import opuntiaEngelmannii from "../components/cactus/opuntiaEngelmannii.vue"
  import schlumbergaTruncata from "../components/cactus/schlumbergaTruncata.vue"
  import trichocereusBridgesii from "../components/cactus/trichocereusBridgesii.vue"
  import trichocereusPachanoi from "../components/cactus/trichocereusPachanoi.vue"
  import trichocereusPeruvianus from "../components/cactus/trichocereusPeruvianus.vue"

  export default {
    components: {
      list,
      cactusDetails,
      armatocereusRauhii,
      astrophytumAstaria,
      astrophytumMyriostigma,
      brasilicactusHaselbergii,
      browningCandelaris,
      carnegieaGigantea,
      cleistocactusSmaragdiflorus,
      echinocactusGrusonii,
      echinocereusCoccineus,
      gymnocalyciumPflanzii,
      lopophoraWilliamsii,
      mammillariaPacifica,
      opuntiaEngelmannii,
      schlumbergaTruncata,
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
  .left-column {
    float: left;
    width: 25%;
    padding: 5px;
    font-weight: bold;
    background-color: #c8e6c8;
  }
  .right-column {
    float: left;
    width: 75%;
    padding: 5px;
  }

  li {
    list-style: none;
    padding: 3px;
  }

  a {
    text-decoration: none;
  }

  /* table {
    padding: 5px;
    background-color: #f0e6c7;
  } */

  th, td {
    padding: 5px;
  }

  /* h2, h3 {
    text-align: center;
    font-weight: bold
  } */

  /* .container {
    width: 80%;
    padding: 5%;
  } */

  /* article {
    padding: 5px;
    margin-top: 15px;
  } */
</style>
