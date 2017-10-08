<template>
  <div id="app">
    <topbar></topbar>
  </div>
</template>

<script>

// import Hello from './components/Hello'
import TopBar from './components/TopBar'
import TileContainer from './components/TileContainer'
import SearchContainer from './components/SearchContainer'

export default {
  name: 'app',
  components: {
    topbar: TopBar,
    tilecontainer: TileContainer,
    searchcontainer: SearchContainer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
