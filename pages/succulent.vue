<template>
  <div class="container">
    <div class="left-column">
      <ul>
         <span v-for="succulent in list" :key='succulent.slug'>
          <li><a href="#" @click='choose(succulent)'>{{succulent.latin_name}}</a></li>
        </span>
      </ul>
    </div>

    <div>
      <span v-if="!succulent.slug">Click to view details for any species</span>
      <span v-else> <cactusDetails :cactus=succulent />  </span>

      <span v-if="succulent.slug=='aloe_vera'"><aloeVera /></span>
      <span v-if="succulent.slug=='crassula_ovata'"><crassulaOvata /></span>
      <span v-if="succulent.slug=='sedum_adolphi'"><sedumAdolphi /></span>
      <span v-if="succulent.slug=='sedum_corynephyllum'"><sedumCornephyllum /></span>
      <span v-if="succulent.slug=='sedum_palmeri'"><sedumPalmeri /></span>
    </div>

  </div>
</template>

<script>
  import list from '../assets/succulent.json';
  import cactusDetails from "../components/details.vue"
  
  import aloeVera from "../components/succulent/aloeVera.vue"
  import crassulaOvata from "../components/succulent/crassulaOvata.vue"
  import sedumAdolphi from "../components/succulent/sedumAdolphi.vue"
  import sedumCornephyllum from "../components/succulent/sedumCornephyllum.vue"
  import sedumPalmeri from "../components/succulent/sedumPalmeri.vue"

  export default {
    components: {
      list,
      cactusDetails,
      aloeVera,
      crassulaOvata,
      sedumAdolphi,
      sedumCornephyllum,
      sedumPalmeri
    },
    data() {
      return {
        succulent: {
          slug: null
        },
        list: list
      };
    },
    methods: {
      choose(succulent) {
        this.succulent = succulent;
      }
    },
    head () {
      return {
        title: 'Succulents',
        data() { return {} },
        meta: [
          { hid: 'description', name: 'description', content: "See what succulents I'm growing" }
        ]
      }
    }
  }
</script>

<style lang="css" src="./listViews.css" scoped></style>
