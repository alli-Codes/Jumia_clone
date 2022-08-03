<template>
    <div class="w-full flex flex-col items-center flex flex-col">
        <div class="w-4/5">
            <HeaderTag />
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
