<template>
    <div
        class="bg-white w-full h-full flex flex-col items-stretch cursor-pointer rounded hover:shadow-lg hover:scale-105">
        <div class="product-container h-64 w-full rounded">
            <img src="/images/img1.jpg" alt="" class=" w-full object-cover rounded-t">
        </div>

        <div class="description h-24 p-2 text-sm flex flex-col items-start rounded">
            <p class="w-full truncate">{{description}}</p>
            <p class="font-bold">{{ price }}</p>
            <p class="text-gray-400 text-xs line-through">{{ formerPrice }}</p>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        description: String,
        price: String,
        formerPrice: String
    }
}
</script>