<template>
    <!-- <div class="bg-green-400 w-full h-full">
        
    </div> -->

    <swiper
    :slidesPerView="1"
    :spaceBetween="30"
    :loop="true"
    :pagination="{
      clickable: true,
    }"
    :navigation="true"
    :modules="modules"
    class="mySwiper w-full h-full"
    >
        <swiper-slide><img src="/images/img1.jpg" alt=""></swiper-slide>
        <swiper-slide>Hello</swiper-slide>
    </swiper>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/pagination";
import "swiper/css/navigation";
import "./style.css";
import { Pagination, Navigation } from "swiper";
export default {
    name: 'AdvertItem',
    components: {
        Swiper,
        SwiperSlide
    },
    setup() {
        return {
            modules: [Pagination, Navigation],
        };
    },
}
</script>