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

      <span v-if="succulent.slug=='armatocereus_rauhii'"><armatocereusRauhii /></span>
    </div>

  </div>
</template>

<script>
  import list from '../assets/succulent.json';
  import cactusDetails from "../components/details.vue"
  
  import armatocereusRauhii from "../components/cactus/armatocereusRauhii.vue"

  export default {
    components: {
      list,
      cactusDetails,
      armatocereusRauhii
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

  th, td {
    padding: 5px;
  }

</style>
