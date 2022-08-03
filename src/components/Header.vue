<template>
  <div id="header" class="h-20 bg-white flex items-center justify-evenly px-20">
    <img src="../assets/logo.png" class="w-40">

    <div id="search__container" class="flex items-center justify-center flex-auto  w-64 px-20 gap-8 ">
      <div id="search__inner" class="bg-white flex flex-1 items-center px-3 border-solid border border-gray-300 rounded">
        <Icon icon="eva:search-outline" width="24" color="gray" />
        <input type="text" class="p-3 flex-1 outline-none" placeholder="Search products, brands and categories">
      </div>
      <button class="bg-orange-400 p-3 w-24 font-semibold text-white rounded">SEARCH</button>
    </div>

      <div id="user__section" class="w-80 flex justify-evenly">
        <div id="user__account">
          <p>Hi, Evans</p>
        </div>

        <div id="user__support">
          <p>Help</p>
        </div>

        <div id="user__cart">
          <p>Cart</p>
        </div>
      </div>
    
  </div>
</template>

<script>
import { Icon } from '@iconify/vue';
export default {
  name: "HeaderTag",
  components: {
    Icon
  }
};
</script>
