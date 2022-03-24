<template>
  <div id="app">
    <div class="container-fluid msBackground">
      <Header />
      <Jumbotron />
    </div>
    <div class="container-fluid p-0 msProBarber">
      <ProBarber />
      <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
    </div>
    <div class="container-fluid msServices">
      <Services />
      <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#121315;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
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
    <div class="container-fluid msBlogContainer">
      <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
      <BlogPosts />
    </div>
    <Footer />
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
import BlogPosts from './components/BlogPosts.vue'
import Footer from './components/Footer.vue'

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
    BlogPosts,
    Footer,
  }
}
</script>

<style lang="scss">
@import './assets/scss/colors.scss';

.msProBarber {
  position: relative;

  .fusion-big-triangle-candy {
    display: block;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 80px;
    fill: white;
  }
}

.msServices {
  position: relative;

  .fusion-big-triangle-candy {
    display: block;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 80px;
  }
}

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

.msBlogContainer {
  position: relative;
  background-color: $ebb;

  .fusion-big-triangle-candy {
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 80px;
    transform: rotateX(180deg);
  }
}

</style>
