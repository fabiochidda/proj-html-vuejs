<template>
  <div class="row msProductsContainer justify-content-center">
      <div class="col-12">
          <div class="msProductsTitle text-center pt-4">
              <p>WE HAVE YOU COVERED</p>
              <h2>Avada Grooming Products</h2>
          </div>
      </div>
      <div class="col-3 msProduct text-center">
          <figure>
              <img src="../assets/img/brush_dark-400x400.png" alt="">
          </figure>
          <h3>Brush</h3>
          <p>$15.00</p>
      </div>
      <div class="col-3 msProduct text-center">
          <figure>
              <img src="../assets/img/scissors-400x400.png" alt="">
          </figure>
          <h3>Scissors</h3>
          <p>$85.00</p>
      </div>
      <div class="col-3 msProduct text-center">
          <figure>
              <img src="../assets/img/hot_oil_dark-400x400.png" alt="">
          </figure>
          <h3>Hot Oil</h3>
          <p>$15.00</p>
      </div>
      <div class="col-3 msProduct text-center">
          <figure>
              <img src="../assets/img/straight_razor_dark-400x400.png" alt="">
          </figure>
          <h3>Straight Razor</h3>
          <p>$30.00</p>
      </div>
      <div class="col-12 text-center">
          <button class="bg-transparent px-4 py-2" type="button">SHOP OUR PRODUCT RANGE</button>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msProducts',
}
</script>

<style scoped lang="scss">

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
        color: burlywood;
        margin: 0;
    }

    h2 {
        font-size: 60px;
        font-family: 'Abril Fatface', cursive;
        color: grey;
    }
}

.msProduct {
    h3 {
        font-family: 'Abril Fatface', cursive;
        color: burlywood;
    }

    p {
        color: burlywood;
        margin: 0;
    }
}

button {
    font-size: 20px;
    color: burlywood;
    border: 2px solid burlywood;
}
</style>