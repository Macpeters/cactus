<template>
  <div class="container">
    <div class="left-column">
      <ul>
         <span v-for="cactus in list" :key='cactus.slug'>
          <li>
            <a href="#" @click='choose(cactus)'>
              <p class="latin-name">{{cactus.latin_name}}</p>
              <p class="latin-name-short">{{cactus.latin_name_short}}</p>
            </a>
          </li>
        </span>
      </ul>
    </div>

    <div>
      <span v-if="!cactus.slug">Click to view details for any species</span>
      <span v-else> <cactusDetails :cactus=cactus />  </span>

      <span v-if="cactus.slug=='astrophytum_astaria'"><astrophytumAstaria /></span>
      <span v-if="cactus.slug=='astrophytum_capricorne'"><astrophytumCapricorne /></span>
      <span v-if="cactus.slug=='astrophytum_myriostigma'"><astrophytumMyriostigma /></span>
      <!-- <span v-if="cactus.slug=='browning_candelaris'"><browningCandelaris /></span> -->
      <span v-if="cactus.slug=='carnegiea_gigantea'"><carnegieaGigantea /></span>
      <span v-if="cactus.slug=='cleistocactus_colademononis'"><cleistocactusColademononis /></span>
      <span v-if="cactus.slug=='cleistocactus_smaragdiflorus'"><cleistocactusSmaragdiflorus /></span>
      <span v-if="cactus.slug=='echinocactus_grusonii'"><echinocactusGrusonii /></span>
      <span v-if="cactus.slug=='echinocereus_coccineus'"><echinocereusCoccineus /></span>
      <span v-if="cactus.slug=='echinocereus_poselgeri'"><echinocereusPoselgeri /></span>
      <span v-if="cactus.slug=='echinofossulo'"><Echinofossulo /></span>
      <span v-if="cactus.slug=='lopophora_williamsii'"><lopophoraWilliamsii /></span>
      <span v-if="cactus.slug=='mammillaria_pacifica'"><mammillariaPacifica /></span>
      <span v-if="cactus.slug=='opuntia_engelmannii'"><opuntiaEngelmannii /></span>
      <span v-if="cactus.slug=='schlumbergera_buckleyi'"><schlumbergaBuckleyi /></span>
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
  import astrophytumAstaria from "../components/cactus/astrophytumAstaria.vue"
  import astrophytumCapricorne from "../components/cactus/astrophytumCapricorne.vue"
  import astrophytumMyriostigma from "../components/cactus/astrophytumMyriostigma.vue"
  // import browningCandelaris from "../components/cactus/archived/browningCandelaris.vue"
  import carnegieaGigantea from "../components/cactus/carnegieaGigantea.vue"
  import cleistocactusColademononis from "../components/cactus/cleistocactusColademononis.vue"
  import cleistocactusSmaragdiflorus from "../components/cactus/cleistocactusSmaragdiflorus.vue"
  import echinocactusGrusonii from "../components/cactus/echinocactusGrusonii.vue"
  import echinocereusCoccineus from "../components/cactus/echinocereusCoccineus.vue"
  import echinocereusPoselgeri from "../components/cactus/echinocereusPoselgeri.vue"
  import Echinofossulo from "../components/cactus/echinofossulo.vue"
  import lopophoraWilliamsii from "../components/cactus/lopophoraWilliamsii.vue"
  import mammillariaPacifica from "../components/cactus/mammillariaPacifica.vue"
  import opuntiaEngelmannii from "../components/cactus/opuntiaEngelmannii.vue"
  import schlumbergaBuckleyi from "../components/cactus/schlumbergaBuckleyi.vue"
  import schlumbergaTruncata from "../components/cactus/schlumbergaTruncata.vue"
  import trichocereusBridgesii from "../components/cactus/trichocereusBridgesii.vue"
  import trichocereusPachanoi from "../components/cactus/trichocereusPachanoi.vue"
  import trichocereusPeruvianus from "../components/cactus/trichocereusPeruvianus.vue"


  export default {
    components: {
      list,
      cactusDetails,
      astrophytumAstaria,
      astrophytumCapricorne,
      astrophytumMyriostigma,
      // browningCandelaris,
      carnegieaGigantea,
      cleistocactusColademononis,
      cleistocactusSmaragdiflorus,
      echinocactusGrusonii,
      echinocereusCoccineus,
      echinocereusPoselgeri,
      Echinofossulo,
      lopophoraWilliamsii,
      mammillariaPacifica,
      opuntiaEngelmannii,
      schlumbergaBuckleyi,
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

<style lang="css" src="./listViews.css" scoped></style>
