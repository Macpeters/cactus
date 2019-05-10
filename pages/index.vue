<template>
  <section class="container">
    <div>
      <h1 class="title">
        cactus
      </h1>
      <h2 class="subtitle">
        <ul>
          <li><a href="/cactus">Cactus</a></li>
          <li><a href="/succulent">Succulent</a></li>
          <li><a href="/wishList">Wish List</a></li>
        </ul>
      </h2>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  padding: 20px;
  text-align: left;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
  text-align: center;
}

.subtitle {
  font-weight: 300;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  text-align: center;
}



li {
  display: inline;
}

a {
  text-decoration: none;
}

article {
  padding: 10px;
}
</style>
