<template>
    <div class="w-full h-[25rem] bg-red-400 my-4">
        <SideBar />
    </div>
</template>

<script>
import SideBar from './Sidebar.vue'
    export default {
        name: 'BannerItem',
        components:{
            SideBar
        }
    }
</script>