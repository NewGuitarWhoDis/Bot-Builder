<template>
  <Nav class="nav"/>
  <Tabs class="tabs"/>
  <Sidebar @drop-block="dropblock" class="sidebar"/>
  <Main />
</template>

<script>
import Nav from './components/nav'
import Sidebar from './components/sidebar'
import Tabs from './components/tabs'
import Main from './components/main'

export default {
  name: 'App',
  components: {
    Nav,
    Tabs,
    Sidebar,
    Main,
  },
  methods: {
    dropblock(String) {
      console.log(String)
      document.getElementById("main-content").innerHTML += "<" + String + " />";
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}
</style>
