<template>
  <div id="header" class="h-20 bg-white flex items-center justify-evenly px-20">
    <h1 class=" bg-red-400 w-40">LOGO</h1>

    <div id="search__container" class="flex items-center justify-center flex-auto w-64 px-20 gap-8 ">
      <input type="text" class="p-3 flex-1 border-solid border border-gray-300 rounded">
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
export default {
  name: "HeaderTag",
};
</script>
