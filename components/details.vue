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
    props: ['cactus'],
    head () {
      return {
        name: 'details',
        title: 'details'
      }
    }}
</script>

<style>
</style>
