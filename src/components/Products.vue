<template>
  <div class="row msProductsContainer justify-content-center">
      <div class="col-12">
          <div class="msProductsTitle text-center pt-4">
              <p>WE HAVE YOU COVERED</p>
              <h2>Avada Grooming Products</h2>
          </div>
      </div>
      <div v-for="(el, i) in products" :key="i" class="col-3 msProduct text-center">
          <figure>
              <img :src="el.image" alt="">
          </figure>
          <h3>{{el.name}}</h3>
          <p>{{el.price}}</p>
      </div>
      <div class="col-12 text-center">
          <button class="bg-transparent px-4 py-2" type="button">SHOP OUR PRODUCT RANGE</button>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msProducts',
    data() {
        return {
            products: [
                {
                    image: require(`../assets/img/brush_dark-400x400.png`),
                    name: 'Brush',
                    price: '$15.00',
                },
                {
                    image: require(`../assets/img/scissors-400x400.png`),
                    name: 'Scissors',
                    price: '$85.00',
                },
                {
                    image: require(`../assets/img/hot_oil_dark-400x400.png`),
                    name: 'Hot Oil',
                    price: '$15.00',
                },
                {
                    image: require(`../assets/img/straight_razor_dark-400x400.png`),
                    name: 'Straight Razor',
                    price: '$30.00',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import '../assets/scss/colors.scss';

.msProductsContainer {
    height: 900px;
    padding: 0;
    background-image: url(../assets/img/avadabarbers-reviewsbackground.jpg);
    background-size: 100%;
    background-repeat: no-repeat;
}

.msProductsTitle {
    p {
        font-weight: bold;
        color: $driftwood;
        margin: 0;
    }

    h2 {
        font-size: 60px;
        font-family: 'Abril Fatface', cursive;
        color: $silver-chalice;
    }
}

.msProduct {
    h3 {
        font-family: 'Abril Fatface', cursive;
        color: $driftwood;
    }

    p {
        color: $driftwood;
        margin: 0;
    }
}

button {
    font-size: 20px;
    color: $driftwood;
    border: 2px solid $driftwood;

    &:hover {
        opacity: 0.7;
    }
}
</style>