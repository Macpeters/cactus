<template>
  <div>
    <h1>Current Cactus List</h1>
      <ul>
        <li><a href="/cactus/armatocereus_rauhii">Armatocereus rauhii</a></li>
        <li><a href="/cactus/astrophytumn_astaria">Astrophytumn astaria</a></li>
        <li><a href="/cactus/astrophytum_myriostigma">Astrophytum myriostigma</a></li>
        <li><a href="/cactus/brasilicactus_haselbergii">Brasilicactus haselbergii</a></li>
        <li><a href="/cactus/browning_candelaris">Browning candelaris</a></li>
        <li><a href="/cactus/carnegiea_gigantea">Carnegiea gigantea</a></li>
        <li><a href="/cactus/cleistocactus_smaragdiflorus">Cleistocactus smaragdiflorus</a></li>
        <li><a href="/cactus/echinocactus_grusonii">Echinocactus grusonii</a></li>
        <li><a href="/cactus/echinocereus_coccineus">Echinocereus coccineus</a></li>
        <li><a href="/cactus/gymnocalycium_pflanzii">Gymnocalycium pflanzii</a></li>
        <li><a href="/cactus/lopophora_williamsii">Lopophora williamsii</a></li>
        <li><a href="/cactus/mammillaria_pacifica">Mammillaria pacifica</a></li>
        <li><a href="/cactus/opuntia_engelmannii">Opuntia engelmannii</a></li>
        <li><a href="/cactus/trichocereus_bridgisii">Trichocereus bridgesii</a></li>
        <li><a href="/cactus/trichocereus_pachanoi">Trichocereus pachanoi</a></li>
        <li><a href="/cactus/trichocereus_peruvianus">Trichocereus peruvianus</a></li>
      </ul>
      
    <nuxt-child v-if="$route.params.cactus"/>

    <span v-if="!$route.params.cactus">Click to view details for any species</span>
    
    <span v-if="$route.params.cactus=='lopophora_williamsii'"><lopophoraWilliamsii /></span>
    <span v-if="$route.params.cactus=='trichocereus_bridgisii'"><trichocereusBridgesii /></span>
  </div>
</template>

<script>
  import lopophoraWilliamsii from "../components/cactus/lopophoraWilliamsii.vue"
  import trichocereusBridgesii from "../components/cactus/trichocereusBridgesii.vue"

  export default {
    components: { 
      lopophoraWilliamsii,
      trichocereusBridgesii
    },
    head () {
      return {
        title: 'Cactus', 
        data() { return {} },
        meta: [
          { hid: 'description', name: 'description', content: "See what cacti I'm growing" }
        ]
      }
    }}
</script>

<style>
  li {
    display: inline;
    padding: 5px;
    font-weight: 800;
  }
</style>
