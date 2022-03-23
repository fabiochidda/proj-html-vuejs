<template>
  <div class="container">
      <div class="row flex-column">
          <div class="col-auto pt-3">
              <div class="msServicesTitle text-center pt-4 pb-5">
                  <p>MENS GROOMING</p>
                  <h2>Services</h2>
              </div>
          </div>
      </div>
      <div class="row justify-content-center text-center pt-5">
          <div class="col-3">
              <div class="msProductImage">
                  <figure>
                      <img src="../assets/img/avadabarbers-trimcut-icon-before.png" alt="">
                  </figure>
                  <h3 class="m-4">Trim and Cut</h3>
                  <p>Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.</p>
              </div>
          </div>
          <div class="col-3">
              <div class="msProductImage">
                  <figure>
                      <img src="../assets/img/avadabarbers-washndry-icon.png" alt="">
                  </figure>
                  <h3 class="m-4">Wash and Dry</h3>
                  <p>Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashion.</p>                  
              </div>
          </div>
          <div class="col-3">
              <div class="msProductImage">
                  <figure>
                      <img src="../assets/img/avadabarbers-beardtrim-icon.png" alt="">
                  </figure>
                  <h3 class="m-4">Beard Tidy</h3>
                  <p>Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.</p>                  
              </div>
          </div>
      </div>
      <div class="row text-center p-5">
          <div class="col-12 p-5">
              <button class="bg-transparent px-4 py-2" type="button">READ ABOUT OUR SERVICES</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msServices',
}
</script>

<style scoped lang="scss">

.msServicesTitle {
    p {
        font-weight: bold;
        color: burlywood;
        margin: 0;
    }

    h2 {
        font-size: 70px;
        font-family: 'Abril Fatface', cursive;
        color: grey;
    }
}

.msProductImage {
    img {
        height: 110px;
    }

    h3 {
        color: burlywood;
        font-family: 'Abril Fatface', cursive;
    }

    p {
        color: black;
    }
}

button {
    font-size: 20px;
    color: burlywood;
    border: 2px solid burlywood;
}



</style>