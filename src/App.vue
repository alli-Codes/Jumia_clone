<template>
    <div class="bg-[#f5f5f5] w-full flex flex-col items-center flex flex-col">
        <HeaderTag />
        <div class="w-9/12">
            <BannerItem />
        </div>
    </div>
</template>

<script>
import HeaderTag from './components/Header.vue'
import BannerItem from './components/Banner/Banner.vue'

export default {
    name: 'App',
    components: {
        HeaderTag,
        BannerItem,
        }
}
</script>
