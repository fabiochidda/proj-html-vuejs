<template>
  <div class="container">
      <div class="row align-items-center">
          <div class="col-6">
              <div class="jumbo-title">
                  <h2>Barber Shop</h2>
              </div>
              <div class="jumbo-text">
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
  </div>
</template>

<script>
export default {
    name: 'MsJumbo'
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap');

h2 {
  font-size: 90px;
  font-family: 'Abril Fatface', cursive;
}

button {
    font-size: 20px;
    color: burlywood;
    border: 1px solid burlywood;
}
</style>