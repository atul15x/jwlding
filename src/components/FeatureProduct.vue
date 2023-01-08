<template>

  <div class="section" >
    <div class="container">
      <div class="_tag ">
        <h1 class="is-size-2 has-text-centered">Mig & Tig Welding Torch</h1>
      </div>
    </div>
  </div>

      <div class="product my-6" style="background-color: #0E2B5C;padding: 50px">
        <swiper style="padding: 50px 50px;"
                :slidesPerView="4"
                :spaceBetween="30"
                :slidesPerGroup="4"
                :autoplay="{
              delay: 2500,
              disableOnInteraction: false,
            }"
                :loopFillGroupWithBlank="true"
                :pagination="{
      clickable: true,
    }" :breakpoints="{
      '0': {
        slidesPerView: 1,
        spaceBetween: 20,
      },
      '520': {
        slidesPerView: 2,
        spaceBetween: 40,
      },
      '768': {
        slidesPerView: 3,
        spaceBetween: 50,
      },
      '1000': {
        slidesPerView: 4,
        spaceBetween: 50,
      }
    }"
                :modules="modules"
                class="mySwiper"
        >
          <swiper-slide v-for="i in 10"><div class="card has-shadow">
            <div class="card-image">
              <figure class="image is-4by3">
                <img src="../assets/Product_image/1.jpg" alt="Placeholder image">
              </figure>
            </div>
            <div class="card-content">
              <div class="content">
                <p>Water Cooled Mig Welding Torch | Japanese 500A Mig welding Torch</p>
                <br>
                <a href="#" style="color: #D71903">More Info</a>
              </div>
            </div>
          </div></swiper-slide>
        </swiper>
      </div>




  <div class="section">
    <div class="container">
      <div class="_tag py-6">
        <h1 class="is-size-2 has-text-centered">Trafimet Type Welding &Cutting Torch</h1>
      </div>
    </div>
  </div>

  <div class="product my-6" style="background-color: #0E2B5C;padding: 50px">
    <swiper style="padding: 50px 50px;"
            :slidesPerView="4"
            :spaceBetween="30"
            :slidesPerGroup="4"
            :autoplay="{
              delay: 2500,
              disableOnInteraction: false,
            }"
            :loopFillGroupWithBlank="true"
            :pagination="{
      clickable: true,
    }" :breakpoints="{
      '0': {
        slidesPerView: 1,
        spaceBetween: 20,
      },
      '520': {
        slidesPerView: 2,
        spaceBetween: 40,
      },
      '768': {
        slidesPerView: 3,
        spaceBetween: 50,
      },
      '1000': {
        slidesPerView: 4,
        spaceBetween: 50,
      }
    }"
            :modules="modules"
            class="mySwiper"
    >
      <swiper-slide v-for="i in 6"><div class="card has-shadow">
        <div class="card-image">
          <figure class="image is-4by3">
            <img src="../assets/Product_image/2.jpg" alt="Placeholder image">
          </figure>
        </div>
        <div class="card-content">
          <div class="content">
            <p>Water Cooled Mig Welding Torch | Japanese 500A Mig welding Torch</p>
            <br>
            <a href="#" style="color: #D71903">More Info</a>
          </div>
        </div>
      </div></swiper-slide>
    </swiper>
  </div>

</template>


<style scoped>
@import "bulma/css/bulma.min.css";
.card:hover {
  opacity: 0.8;
  transform: scale(1.10);
  cursor: pointer;
}
</style>

<script>
// Import Swiper Vue.js components
import {  Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";
import "swiper/css/navigation";

// import required modules
import { Autoplay, Pagination, Navigation } from "swiper";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay,Pagination, Navigation],

    };
  },
};
</script>