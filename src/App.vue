<template>
  <topline />
  <feeds />
</template>

<script>
import { topline } from './components/topline/'
import feeds from './components/feeds.vue'

export default {
  name: 'App',
  components: {
    topline,
    feeds
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
