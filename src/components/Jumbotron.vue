<template>
  <div class="container">
      <div class="row align-items-center">
          <div class="col-6">
              <div class="jumbo-title">
                  <h2>Barber Shop</h2>
              </div>
              <div class="jumbo-text py-4">
                  <p>The Pinnacle of Male Grooming</p>
              </div>
              <div class="jumbo-button">
                  <button class="bg-transparent px-4 py-2" type="button">LEARN MORE</button>
              </div>
          </div>
          <div class="col-6">
              <figure>
                  <img src="../assets/img/avadabarbers_hero_focalmirror-600x825.png" alt="">
              </figure>
          </div>
      </div>
      <div class="row flex-column g-3 msIcons">
          <div class="col-auto">
              <div class="jumbo-icon d-flex justify-content-center align-items-center flex-column">
                  <div class="icon-content text-center">
                    <i class="fa-brands fa-atlassian"></i>
                    <p class="m-0">Demo</p>
                  </div>
              </div>
          </div>
          <div class="col-auto">
              <div class="jumbo-icon d-flex justify-content-center align-items-center flex-column">
                  <div class="icon-content text-center">
                    <p class="m-0 msPrice">$ 39</p>
                    <p class="m-0">On Sale</p>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'MsJumbo'
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap');

.jumbo-title {
    display: contents;
}

h2 {
  font-size: 90px;
  font-family: 'Abril Fatface', cursive;
  line-height: 150px;
  position: relative;
}

h2::after {
    content: '';
    display: block;
    height: 5px;
    bottom: 0;
    left: 0;
    width: 40%;
    background-color: burlywood;
}

button {
    font-size: 20px;
    color: burlywood;
    border: 1px solid burlywood;
}

.msIcons {
    position: absolute;
    top: 150px;
    right: 10px;
}

.jumbo-icon {
    width: 70px;
    height: 70px;
    border-radius: 10px;
    background-color: white;

    .fa-atlassian{
        font-size: 25px;
        color: black;
    }

    p {
        color: black;
    }

    .msPrice {
        font-size: 20px;
        color: green;
    }
}




</style>