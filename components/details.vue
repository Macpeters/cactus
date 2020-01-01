<template>
  <div class='details'>
    <h2>{{ cactus.latin_name}}</h2>
    <h3>AKA {{cactus.aka}}</h3>
    
    <article class="summary">
      <p><strong>Description:</strong> {{cactus.description}}</p>
      <p><strong>Distribution:</strong> {{cactus.distribution}}</p>
      <p><strong>Flowers:</strong> {{cactus.flowers}}</p>
      <p><strong>Fruit:</strong> {{cactus.fruit}}</p>
      <p><strong>Spines:</strong> {{cactus.spines}}</p>
    </article>
     
    <table>
      <tr>
        <th>Growth Pattern</th>
        <th>Height</th>
        <th>Width</th>
        <th>Ribs</th>
        <th>Origin</th>
        <th>Zone</th>
      </tr>
      <tr>
        <td>{{cactus.growth_pattern}}</td>
        <td>{{cactus.height}}</td>
        <td>{{cactus.width}}</td>
        <td>{{cactus.ribs}}</td>
        <td>{{cactus.origin}}</td>
        <td></td>
      </tr>
    </table>
  </div>
</template>

<script>
  export default {
    props: ['cactus'],
    head () {
      return {
        name: 'details',
        title: 'details'
      }
    }}
</script>

<style scoped>
  .details {
    background-color: #f0e6c7;
    margin-left: 25%;
  }

  h2, h3 {
    padding: 5px;
  }

  .main-image {
    width: 400px;
  }

  .summary {
    width: 80%;
    padding: 5px;
    margin-left: 10px;
  }
</style>
