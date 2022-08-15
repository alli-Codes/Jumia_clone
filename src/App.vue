<template>
    <div class="bg-[#f5f5f5] w-full flex flex-col items-center">
        <HeaderTag />
        <div class="w-9/12 h-full">
            <BannerItem />
            <ProductContainerAds />
            <Product_Container />
        </div>
    </div>
</template>

<script>
import HeaderTag from './components/Header.vue'
import BannerItem from './components/Banner/Banner.vue'
import ProductContainerAds from './components/Product_Ads/ProductContainerAds.vue'
import Product_Container from './components/Products_Containers/Product_Container.vue';

export default {
    name: 'App',
    components: {
    HeaderTag,
    BannerItem,
    ProductContainerAds,
    Product_Container
}
}
</script>
