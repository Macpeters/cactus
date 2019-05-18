<template>
  <div class="container">
    <div class="left-column">
      <ul>
         <span v-for="item in list" :key='item.slug'>
          <li><a href="#" @click='choose(item)'>{{item.latin_name}}</a></li>
        </span>
      </ul>
    </div>

    <div>
      <span v-if="!item.slug">Click to view details for any species</span>
      <span v-else> <cactusDetails :cactus=item />  </span>

      <span v-if="item.slug=='aloe_vera'"><aloeVera /></span>
    </div>

  </div>
</template>

<script>
  import list from '../assets/wishlist.json';
  import cactusDetails from "../components/details.vue"
  
  import aloeVera from "../components/succulent/aloeVera.vue"

  export default {
    components: {
      list,
      cactusDetails,
      aloeVera,
    },
    data() {
      return {
        item: {
          slug: null
        },
        list: list
      };
    },
    methods: {
      choose(item) {
        this.item = item;
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
