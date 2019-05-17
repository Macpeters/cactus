<template>
  <div>
    <h2 class="subtitle">
      <ul class="nav-bar">
        <li class="nav-item"><a href="/">Home</a></li>
        <li class="nav-item"><a href="/cactus">Cacti</a></li>
        <li class="nav-item"><a href="/succulent">Succulents</a></li>
        <li class="nav-item"><a href="/wishList">Wishlist</a></li>
      </ul>
    </h2>
    <nuxt />
  </div>
</template>

<style>
  html {
    font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
      Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-size: 16px;
    word-spacing: 1px;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
  }

  *,
  *:before,
  *:after {
    box-sizing: border-box;
    margin: 0;
  }

  .subtitle {
    font-weight: 300;
    color: #c0c8d7;
    word-spacing: 5px;
    padding-bottom: 15px;
    text-align: center;
    background-color: rgb(32, 86, 23);
  }

  .nav-item {
    display: inline;
  }

  .nav-item a {
    color: #c0c8d7;
    text-decoration: none;
    font-weight: bolder;
    -webkit-transition: color 2s; /* Safari */
    transition: color 2s;
  }
  .nav-item a:hover {
    color: #8eb2f5;
  }

</style>
