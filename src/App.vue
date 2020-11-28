<template>
  <div id="app">
    <common/>
    <router-view/>
  </div>
</template>

<script>
import Common from './components/common/Common'
export default {
  name: 'App',
  components: {
    Common
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
