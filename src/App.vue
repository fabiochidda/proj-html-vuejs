<template>
  <div id="app">
    <div class="container-fluid msBackground">
      <Header />
      <Jumbotron />
    </div>
    <div class="container-fluid p-0">
      <ProBarber />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import ProBarber from './components/ProBarber.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    ProBarber,
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

.container-fluid {
  position: relative;
}

.msBackground {
  min-height: 950px;
  background-image: url(./assets/img/avadabarbers-homepage-hero-bg.jpg);
  background-size: 100%;
  background-repeat: no-repeat;
}

ul li {
  list-style: none;
}
</style>
