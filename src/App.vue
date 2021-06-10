<template>
  <div id="app">
    <BoggleBoard></BoggleBoard>
  </div>
</template>

<script>
import BoggleBoard from './components/BoggleBoard.vue'

export default {
  name: 'App',
  components: {
    BoggleBoard
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
