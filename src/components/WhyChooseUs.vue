<template>
  <section class="section" style="background-color: #0E2B5C;color: white">
    <div class="container">
        <div class="columns">
          <div class="column">
            <img src="../assets/whyChooseUs.jpg">
          </div>
          <div class="column">
            <h1 class="is-size-3" style="color: #D71903">WHY CHOOSE US</h1>
            <br><br>
            <p>
              As a producer, We have our own independent production line, producing all kinds of welding torch, also we are the foundry manufacturer of many large international companies. So the quality of the product is beyond doubt.
            </p>
            <br>
            <p>
              Market, we don't want to have too much agent in an area. It will reduce your competition.
            </p>
            <br>
            <p>
              Price, Our price depends on a market price. We can offer you the right agent price for you. Let you have more competition.
            </p>
            <br>
            <p>
              Manufacturing, We can directly offer all technical support. We can have a video call for you, all problems will be solve on time.
            </p>
            <br>
            <button class="button is-danger is-outlined">
              MAKE AN APOINMENT
            </button>
          </div>
        </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <h1 class="is-size-5 ">  <span class="is-size-3" style="color: #D71903"> Our Company </span> is a company that integrates production and sales.
        Firstly, as a producer, We have our own independent production line, producing all kinds of welding torch, also we are the foundry manufacturer of many large international companies. So the quality of the product is beyond doubt.
        Secondly, as a seller, Our products have appeared in many countries,such as America, Japan, Brazil, Spanish, Turkey, Russia, Mexico, Germany etc. We're glad to hear that you're on the market for kinds of welding torch. I hope we can have a long-term cooperation.</h1>
    </div>

    <div class="" style="margin-top: 50px">
      <swiper style="padding: 50px 0px"
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
        <swiper-slide><img src="../assets/slider/1.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/slider/2.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/slider/3.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/slider/4.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/slider/5.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/slider/6.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/slider/7.jpg"></swiper-slide>
      </swiper>
    </div>
  </section>
</template>

<style scoped>
@import "bulma/css/bulma.min.css";

p{
  font-size: 20px;
}

.swiper {
  width: 100%;
  height: 100%;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;

  /* Center slide text vertically */
  display: -webkit-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  -webkit-align-items: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.swiper-slide img:hover {
  opacity: 0.8;
  transform: scale(1.10);
  cursor: pointer;
}

swiper
{
  padding: 50px;
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