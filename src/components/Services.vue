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
          <div v-for="(el, i) in services" :key="i" class="col-3">
              <div class="msProductImage">
                  <figure>
                      <img :src="el.image" alt="">
                  </figure>
                  <h3 class="m-4">{{el.title}}</h3>
                  <p>{{el.description}}</p>
              </div>
          </div>
      </div>
      <div class="row text-center pb-5">
          <div class="col-12 p-5">
              <button class="bg-transparent px-4 py-2" type="button">READ ABOUT OUR SERVICES</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msServices',
    data() {
        return {
            services: [
                {
                    image: require(`../assets/img/avadabarbers-trimcut-icon-before.png`),
                    title: 'Trim & Cut',
                    description: 'Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.',
                },
                {
                    image: require(`../assets/img/avadabarbers-beardtrim-icon.png`),
                    title: 'Wash & Dry',
                    description: 'Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashion.',
                },
                {
                    image: require(`../assets/img/avadabarbers-trimcut-icon-before.png`),
                    title: 'Beard Tidy',
                    description: 'Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import '../assets/scss/colors.scss';

.container {
    height: 800px;
}

.msServicesTitle {
    p {
        font-weight: bold;
        color: $driftwood;
        margin: 0;
    }

    h2 {
        font-size: 70px;
        font-family: 'Abril Fatface', cursive;
        color: $silver-chalice;
    }
}

.msProductImage {
    img {
        height: 110px;
    }

    h3 {
        color: $driftwood;
        font-family: 'Abril Fatface', cursive;
    }

    p {
        color: $emperor;
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