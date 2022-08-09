<template>
    <!-- <div class="bg-green-400 w-full h-full">
        
    </div> -->

    <swiper
    :slidesPerView="1"
    :spaceBetween="30"
    :effect="'fade'"
    :autoplay="{
      delay: 3500,
      disableOnInteraction: false,
    }"
    :loop="true"
    :pagination="{
      clickable: true,
    }"
    :navigation="true"
    :modules="modules"
    class="mySwiper w-full h-full rounded"
    >
        <swiper-slide><img src="/images/img1.jpg" alt=""></swiper-slide>
        <swiper-slide><img src="/images/img2.jpg" alt=""></swiper-slide>
        <swiper-slide><img src="/images/img3.jpg" alt=""></swiper-slide>
        <swiper-slide><img src="/images/img4.jpg" alt=""></swiper-slide>
    </swiper>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/effect-fade";
import "swiper/css/pagination";
import "swiper/css/navigation";
import "./style.css";
import { Autoplay, EffectFade, Pagination, Navigation } from "swiper";
export default {
    name: 'AdvertItem',
    components: {
        Swiper,
        SwiperSlide
    },
    setup() {
        return {
            modules: [Autoplay, EffectFade, Pagination, Navigation],
        };
    },
}
</script>