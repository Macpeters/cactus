<template>
  <div>
    <h1>Wish List</h1>
      <ul>
        <li>Echinocereus rigidissimus (red spines)</li>
        <li>Lithrops (succulent - living stones)</li>
        <li>Cleistocactus Strausii (wooly torch)</li>
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
