<template>
  <div id="app">
    <div class="container-fluid msBackground">
      <Header />
      <Jumbotron />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
}

.msBackground {
  min-height: 950px;
  background-image: url(./assets/img/avadabarbers-homepage-hero-bg.jpg);
  background-size: 100%;
  background-repeat: no-repeat;
}

</style>
