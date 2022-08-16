<template>
    <div class="bg-white my-4 rounded shadow-md">
        <p class="py-3 px-4 font-semibold text-xl">Recommended for you</p>
        <ProductSlider :productData="productData" />
    </div>
</template>

<script>
import ProductSlider from '../Reusables/ProductSlider.vue'
import productData from './productData';

export default {
    name: 'Product-Container',
    components: {
        ProductSlider,
    },
    data() {
        return {
            productData
        }
    }
}
</script>