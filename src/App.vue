<script setup>

import Navbar from "@/components/Navbar.vue";
import Banner from "@/components/Banner.vue";
import FeatureProduct from "@/components/FeatureProduct.vue";
import AboutUs from "@/components/AboutUs.vue";
import WhyChooseUs from "@/components/WhyChooseUs.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <Navbar />
  <banner />
  <feature-product />
  <about-us />
  <WhyChooseUs />
  <Footer />
</template>

<style scoped>
@import "bulma/css/bulma.min.css";
</style>
