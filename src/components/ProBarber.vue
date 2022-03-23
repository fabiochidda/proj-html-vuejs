<template>
  <div class="msBanner d-flex flex-column justify-content-center align-items-center ">
    <p class="m-0">AWARD WINNING</p>
    <h2>Pro Barbers</h2>
    <button class="bg-transparent px-4 py-2" type="button">MEET YOU NEW BARBER</button>
  </div>
</template>

<script>
export default {
    name: 'ProBarber',
}
</script>

<style scoped lang="scss">

.msBanner {
    padding: 0;
    height: 500px;
    background-image: url(../assets/img/avadabarbers-about-introbackground.jpg);
    background-size: 100%;
    background-repeat: no-repeat;
}

h2 {
  font-size: 70px;
  font-family: 'Abril Fatface', cursive;
  line-height: 130px;
}

button {
    font-size: 20px;
    color: burlywood;
    border: 2px solid burlywood;
}

p {
    font-weight: bold;
    color: burlywood;
}

</style>