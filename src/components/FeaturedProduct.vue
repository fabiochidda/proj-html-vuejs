<template>
  <div class="container">
      <div class="row justify-content-center msContainer pb-5">
          <div class="col-auto p-0">
              <div class="msFeaturedProductBG d-flex justify-content-center align-items-center">
                  <figure>
                      <img src="../assets/img/shaving_butter-400x400.png" alt="">
                  </figure>
              </div>
          </div>
          <div class="col-6 p-0">
              <div class="msFeaturedProductInfo">
                  <div class="msFeaturedProductTitle pb-3">
                      <p>THIS MONTHS FEATURED PRODUCT</p>
                      <h2>Shaving Butter</h2>
                  </div>
                  <div class="msFeaturedProductDescription">
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, rerum animi debitis dolorum eveniet atque esse et perspiciatis magnam repellendus iste expedita blanditiis optio! Id omnis, vero tenetur fugiat doloremque, perferendis amet neque optio in vitae nam, porro autem? Impedit.</p>
                  </div>
                  <div class="msFeaturedProductButton">
                      <button class="bg-transparent px-4 py-2" type="button">BUY NOW</button>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msFeaturedProduct',
}
</script>

<style scoped lang="scss">
.container {
    position: relative;
}

.msContainer {
    position: absolute;
    top: -30px;
}

.msFeaturedProductBG {
    height: 400px;
    width: 400px;
    background-image: url(../assets/img/avadabarbers-cta-background.jpg);
    background-size: 100%;
    background-repeat: no-repeat;
    border-top: 5px solid burlywood;
}

.msFeaturedProductInfo {
    height: 100%;
    padding: 50px;
    background-color: black;
    border-top: 5px solid burlywood;
}

.msFeaturedProductTitle {

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

button {
    font-size: 20px;
    color: burlywood;
    border: 2px solid burlywood;
}

</style>