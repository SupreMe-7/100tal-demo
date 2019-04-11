<template>
  <swiper class="swiper" :options="swiperOption" ref="mySwiper">
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
    <swiper-slide width:1rem>
      <img src="../assets/swiper.png" alt>
    </swiper-slide>
  </swiper>
</template>

<script>
import "swiper/dist/css/swiper.css";

import { swiper, swiperSlide } from "vue-awesome-swiper";

export default {
  name: "carrousel",
  data() {
    return {
      swiperOption: {
        freeMode: true,
        autoplay: {
          delay: 0,
          stopOnLastSlide: false,
          disableOnInteraction: false
        },
        slidesPerView: 6,
        loop: true,
        speed: 1000
      }
    };
  },
  computed: {
    swiper() {
      return this.$refs.mySwiper.swiper;
    }
  },
  components: {
    swiper,
    swiperSlide
  }
};
</script>

<style>
.swiper {
  height: 1.25rem;
}
.swiper .s-slide {
  width: 1.2rem;
  height: 1.2rem;
}
.swiper img {
  width: 1.2rem;
  height: 1.2rem;
}
.swiper-container-free-mode > .swiper-wrapper {
  -webkit-transition-timing-function: linear;
  -moz-transition-timing-function: linear;
  -ms-transition-timing-function: linear;
  -o-transition-timing-function: linear;
  transition-timing-function: linear;
  margin: 0 auto;
}
</style>
