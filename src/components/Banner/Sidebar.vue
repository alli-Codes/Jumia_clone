<template>
    <div class="bg-white h-full w-[22rem] rounded p-2 text-xs flex flex-col justify-between shadow-md">
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="carbon:apple" width="20" /><p>Supermarket</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="icon-park-solid:lipstick" width="20" /><p>Health & Beauty</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="fluent:home-20-regular" width="20" /><p>Home & Office</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="fluent:phone-20-regular" width="20" /><p>Phones & Tablets</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="ph:monitor-light" width="20" /><p>Computing</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="ic:round-live-tv" width="20" /><p>Electronics</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="la:tshirt" width="20" /><p>Fashion</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="lucide:baby" width="20" /><p>Baby Products</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="carbon:game-console" width="20" /><p>Gaming</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="carbon:apple" width="20" /><p>Sporting</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="ph:car" width="20" /><p>Automobile</p></a>
            <a href="" class="flex items-center gap-1 cursor-pointer hover:text-[#f68b1e]"><Icon icon="heroicons-outline:dots-circle-horizontal" width="20" /><p>Other categories</p></a>
    </div>
</template>

<script>
import { Icon } from '@iconify/vue';

    export default {
        name: 'SideBar',
        components: {
            Icon
        }
    }
</script>