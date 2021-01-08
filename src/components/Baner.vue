<template>
    <!-- Carousel -->
      <div id="carouselExampleControls" class="carousel slide mt-5" data-ride="carousel">
        <div class="carousel-inner">
          <div class="container">
            <carousel class="active" :items="1" :nav="false">

              <div class="row pt-5 justify-content-center">
                <div class="col-9 col-sm-4 col-md-6 col-lg-5">
                  <h1 class="mb-4">Spesial Eid Lebaran</h1>
                  <p class="mb-4">Jadikan hari pertama lebaranmu meriah dan memorable</p>
                  <a href="" class="btn btn-warning text-white">Get It Now</a>
                </div>
                <div class="col-3 col-sm-6 col-md-4 col-lg-4 d-none d-sm-block offset-1">
                  <img class="img-fluid" src="img/slideshow/1.png">
                </div>
              </div>
              <div class="row pt-5 justify-content-center">
                <div class="col-9 col-sm-4 col-md-6 col-lg-5">
                  <h1 class="mb-4">Spesial Eid Lebaran</h1>
                  <p class="mb-4">Jadikan hari pertama lebaranmu meriah dan memorable</p>
                  <a href="" class="btn btn-warning text-white">Get It Now</a>
                </div>
                <div class="col-3 col-sm-6 col-md-4 col-lg-4 d-none d-sm-block offset-1">
                  <img class="img-fluid" src="img/slideshow/1.png">
                </div>
              </div>
            </carousel>
          </div>
        </div>
      </div>
    <!-- Akhir Carousel -->
</template>

<style scoped>
.owl-carousel .owl-item img {
  display: block;
  width: 70%;
  border-radius: 10px;
  
}

</style>

<script>
import carousel from 'vue-owl-carousel';

export default {
    name: "Baner",
    components: {
        carousel
    }
}
</script>