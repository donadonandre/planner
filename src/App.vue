<template>
  <MainMenu />
  <router-view/>
</template>

<script>
import MainMenu from './components/MainMenu.vue'

export default {
  components: {
    MainMenu
  }
}
</script>

<style>
body {
  background-color: #f2f2f2;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 600px;
  margin: 0 auto;
  color: #555;
}
</style>
