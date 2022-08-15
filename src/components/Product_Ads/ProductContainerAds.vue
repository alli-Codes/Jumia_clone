<template>
    <div class="h-40 w-full bg-white rounded shadow-md">
        <swiper
            :slidesPerView="8"
            :spaceBetween="30"
            :navigation="true"
            :modules="modules"
            class="mySwiper product__swiper p-4"
        >

        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        <swiper-slide class="bg-transparent"><ProductItemAd /></swiper-slide>
        </swiper>
    </div>
</template>

<script>
import ProductItemAd from './ProductItemAd.vue'
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/pagination";
import "swiper/css/navigation";
// import "./product.css";
import { Pagination, Navigation } from "swiper";

export default {
    name: 'ProductContainerAds',
    components: {
        ProductItemAd,
        Swiper,
        SwiperSlide,
    },
    setup() {
    return {
      modules: [Pagination, Navigation],
    };
  },
}
</script>