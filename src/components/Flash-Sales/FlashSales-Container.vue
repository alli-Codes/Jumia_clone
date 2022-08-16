<template>
    <div>
        <header>
            <p>Flash Sales</p>
        </header>
        <ProductSlider />
    </div>
</template>

<script>
import ProductSlider from '../Reusables/ProductSlider.vue'
export default {
    name: 'Flash-Sales',
    components: {
        ProductSlider
    }
}
</script>