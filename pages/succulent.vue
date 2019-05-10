<template>
  <div>
    <h1>Succulents</h1>
      <ul>
        <li>sedum adolphii</li>
        <li>sedum corynephyllum</li>
        <li>sedum palmers</li>
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
