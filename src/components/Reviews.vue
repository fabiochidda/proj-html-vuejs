<template>
    <div class="container">
      <div class="row flex-column">
          <div class="col-auto pt-3">
              <div class="msReviewsTitle text-center pt-4 pb-5">
                  <p>WHAT PEOPLE SAY</p>
                  <h2>Reviews</h2>
              </div>
          </div>
      </div>
      <div class="row justify-content-center text-center p-5">
          <div class="col-3">
              <div class="msReviewsImage">
                  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Et repellendus amet tempora incidunt, nemo obcaecati minima recusandae nisi vero ex rerum repudiandae facilis voluptatum commodi delectus perferendis nulla quas provident quis corporis non repellat. Veritatis!</p>
                  <div class="msProfileImage">
                      <figure>
                          <img src="../assets/img/avadabarbers-trimcut-gallery6-200x200.jpg" alt="">
                      </figure>
                  </div>
                  <p>John Doe</p>
              </div>
          </div>
          <div class="col-3">
              <div class="msReviewsImage">
                  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Et repellendus amet tempora incidunt, nemo obcaecati minima recusandae nisi vero ex rerum repudiandae facilis voluptatum commodi delectus perferendis nulla quas provident quis corporis non repellat. Veritatis!</p>
                  <div class="msProfileImage">
                      <figure>
                          <img src="../assets/img/avadabarbers-trimcut-gallery7-200x201.jpg" alt="">
                      </figure>
                  </div>
                  <p>Pete Jones</p>                  
              </div>
          </div>
          <div class="col-3">
              <div class="msReviewsImage">
                  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Et repellendus amet tempora incidunt, nemo obcaecati minima recusandae nisi vero ex rerum repudiandae facilis voluptatum commodi delectus perferendis nulla quas provident quis corporis non repellat. Veritatis!</p>
                  <div class="msProfileImage">
                      <figure>
                          <img src="../assets/img/avadabarbers-trimcut-gallery3-200x201.jpg" alt="">
                      </figure>
                  </div>
                  <p>Mark Wilson</p>                  
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'msReviews',
}
</script>

<style scoped lang="scss">

.msReviewsTitle {
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

.msReviewsImage {
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

.msProfileImage img{
    border-radius: 9999px;
}

</style>