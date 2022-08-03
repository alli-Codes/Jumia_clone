<template>
    <div class="w-full h-[25rem] my-4 flex gap-2">
        <SideBar />
        <AdvertItem />
    </div>
</template>

<script>
import SideBar from './Sidebar.vue'
import AdvertItem from './Advert.vue'
    export default {
        name: 'BannerItem',
        components:{
            SideBar,
            AdvertItem
        }
    }
</script>