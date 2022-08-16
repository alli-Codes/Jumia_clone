<template>
    <div class="bg-white my-4 rounded shadow-md">
        <header class="bg-[red] text-white text-sm flex justify-between items-center py-3 px-4 rounded-t">
            <p class="font-semibold text-xl">Flash Sales</p>
            <p class="text-xl">Time Left:<time class="font-bold" datetime=""> 00h : 57m : 39s</time></p>
            <a href="#" class="flex items-center font-semibold">SEE ALL
                <Icon icon="charm:chevron-right" class="ml-2" width="15" />
            </a>
        </header>
        <ProductSlider />
    </div>
</template>

<script>
import ProductSlider from '../Reusables/ProductSlider.vue'
import { Icon } from '@iconify/vue';

export default {
    name: 'FlashSales',
    components: {
        ProductSlider,
        Icon
    },
}
</script>