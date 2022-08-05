<template>
    <div class="w-full h-[25rem] my-4 flex gap-4">
        <SideBar />
        <AdvertItem />
        <SideAdvert />
    </div>
</template>

<script>
import SideBar from './Sidebar.vue'
import AdvertItem from './Advert.vue'
import SideAdvert from './SideAdvert'
    export default {
        name: 'BannerItem',
        components:{
            SideBar,
            AdvertItem,
            SideAdvert
        }
    }
</script>