<template>
  <div class="container">
    <h2>{{ cactus.latin_name}}</h2>
    <h3>AKA {{cactus.aka}}</h3>
    
    <article>
      <p><strong>Description:</strong> {{cactus.description}}</p>
      <p><strong>Distribution:</strong> {{cactus.distribution}}</p>
      <p><strong>Flowers:</strong> {{cactus.flowers}}</p>
      <p><strong>Fruit:</strong> {{cactus.fruit}}</p>
      <p><strong>Spines:</strong> {{cactus.spines}}</p>
      <img :src="cactus.image" />
    </article>
    
    <table>
      <tr>
        <th>Growth Pattern</th>
        <th>Height</th>
        <th>Width</th>
        <th>Ribs</th>
        <th>Origin</th>
      </tr>
      <tr>
        <td>{{cactus.growth_pattern}}</td>
        <td>{{cactus.height}}</td>
        <td>{{cactus.width}}</td>
        <td>{{cactus.ribs}}</td>
        <td>{{cactus.origin}}</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: `Cactus - ${this.$route.params.username}`,
      meta: [
        { hid: 'description', name: 'description', content: `Discover our team member ${this.$route.params.username}` }
      ]
    }
  },
  async asyncData({ app, params, error }) {
    let list = await app.$axios.$get('/api/cactus.json')
    let cactus = list.find((cactus) => cactus.slug == params.cactus)
    if(params.cactus && !cactus) {
      return error({statusCode: 404, message: 'no cactus'})
    }
    return { cactus }
  }
}
</script>

<style>
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

  img {
    width: 100px;
    height: auto;
  }
</style>