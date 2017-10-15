<template>
  <div id="app">
    <topbar></topbar>
    <searchcontainer></searchcontainer>
    <tilecontainer></tilecontainer>
    <footercontainer></footercontainer>
  </div>
</template>

<script>

import TopBar from './components/TopBar'
import TileContainer from './components/TileContainer'
import SearchContainer from './components/SearchContainer'
import FooterContainer from './components/FooterContainer'

export default {
  name: 'app',
  components: {
    topbar: TopBar,
    tilecontainer: TileContainer,
    searchcontainer: SearchContainer,
    footercontainer: FooterContainer
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-family: 'Montserrat', sans-serif;
  background-color: #eff4fc;
}

body{
  font-size: 0.85rem;
}
</style>
