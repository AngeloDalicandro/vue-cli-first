<template>
  <div id="app">

    <MyTitle />

    <MyJumbo />
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyJumbo from './components/MyJumbo.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyJumbo
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
