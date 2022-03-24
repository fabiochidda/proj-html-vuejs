<template>
    <div class="container">
      <div class="row flex-column pt-5">
          <div class="col-auto pt-3">
              <div class="msServicesTitle text-center pt-4 pb-5">
                  <p>TALES FROM THE BARBER SHOP</p>
                  <h2>Recent Blog Posts</h2>
              </div>
          </div>
      </div>
      <div class="row justify-content-center text-center pt-5">
          <div v-for="(el, i) in blogPosts" :key="i" class="col-3">
              <div class="msProductImage">
                  <figure>
                      <img :src="el.image" alt="">
                  </figure>
                  <h3 class="m-4">{{el.title}}</h3>
                  <p>{{el.text}}</p>
              </div>
          </div>
      </div>
      <div class="row text-center p-5">
          <div class="col-12 pb-5">
              <button class="bg-transparent px-4 py-2" type="button">READ MORE FROM OUR BLOG</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msBlogPosts',
    data() {
        return {
            blogPosts: [
                {
                    image: require(`../assets/img/avadabarbers-second-blog-320x202.jpg`),
                    title: 'Avada Barbers Now Open',
                    text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam itaque provident animi facere similique quam.',
                },
                {
                    image: require(`../assets/img/avadabarbers-choosing-blog-320x202.jpg`),
                    title: 'Choosing The Right Barber',
                    text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam itaque provident animi facere similique quam.',
                },
                {
                    image: require(`../assets/img/avadabarbers-ourservice-blog-320x202.jpg`),
                    title: 'Quick Service Guide',
                    text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam itaque provident animi facere similique quam.',
                },
            ]
        }
    }
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

figure {
    overflow: hidden;
}
</style>