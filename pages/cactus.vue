<template>
  <div>
    <h1>Current Cactus List</h1>
      <ul>
        <li><a href="/cactus/armatocereus_rauhii">armatocereus rauhii</a></li>
        <li><a href="/cactus/astrophytumn_astaria">astrophytumn astaria</a></li>
        <li><a href="/cactus/astrophytum_myriostigma">astrophytum myriostigma</a></li>
        <li><a href="/cactus/brasilicactus_haselbergii">brasilicactus haselbergii</a></li>
        <li><a href="/cactus/browning_candelaris">browning candelaris</a></li>
        <li><a href="/cactus/carnegiea_gigantea">carnegiea gigantea</a></li>
        <li><a href="/cactus/cleistocactus_smaragdiflorus">cleistocactus smaragdiflorus</a></li>
        <li><a href="/cactus/echinocactus_grusonii">echinocactus grusonii</a></li>
        <li><a href="/cactus/echinocereus_coccineus">echinocereus coccineus</a></li>
        <li><a href="/cactus/gymnocalycium_pflanzii">gymnocalycium pflanzii</a></li>
        <li><a href="/cactus/lopophora_williamsii">lopophora williamsii</a></li>
        <li><a href="/cactus/mammillaria_pacifica">mammillaria pacifica</a></li>
        <li><a href="/cactus/opuntia_engelmannii">opuntia engelmannii</a></li>
        <li><a href="/cactus/trichocereus_bridgidsii">trichocereus bridgidsii</a></li>
        <li><a href="/cactus/trichocereus_pachanoi">trichocereus pachanoi</a></li>
        <li><a href="/cactus/trichocereus_peruvianus">trichocereus peruvianus</a></li>
      </ul>
    <nuxt-child v-if="$route.params.cactus"/>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Team',
      meta: [
        { hid: 'description', name: 'description', content: 'Discover our team' }
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
