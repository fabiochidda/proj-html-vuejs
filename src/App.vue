<template>
  <div id="app">
    <div class="container-fluid msBackground">
      <Header />
      <Jumbotron />
    </div>
    <div class="container-fluid p-0">
      <ProBarber />
    </div>
    <div class="container-fluid">
      <Services />
    </div>
    <div class="container-fluid">
      <Products />
    </div>
    <div class="contianer-fluid">
      <FeaturedProduct />
    </div>
    <div class="container-fluid">
      <Reviews />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import ProBarber from './components/ProBarber.vue'
import Services from './components/Services.vue'
import Products from './components/Products.vue'
import FeaturedProduct from './components/FeaturedProduct.vue'
import Reviews from './components/Reviews.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    ProBarber,
    Services,
    Products,
    FeaturedProduct,
    Reviews,
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
