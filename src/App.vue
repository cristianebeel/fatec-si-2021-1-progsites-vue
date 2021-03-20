<template>
  <div id="app">
    <header id="nav">
      <router-link to="/">Principal</router-link> |
      <router-link to="/produtos">Produtos</router-link> |
      <router-link to="/sobre">Sobre</router-link>
    </header>
    <router-view/>
    <footer><p>&copy; Copyright 2021 Fatec Taquaritinga</p></footer>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Quicksand, Roboto, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #111;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #369;
    }
  }
}
</style>
