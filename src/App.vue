<template>
    <div class="w-full flex flex-col items-center flex flex-col">
        <div class="w-4/5">
            <HeaderTag />
        </div>
    </div>
</template>

<script>
import HeaderTag from './components/Header.vue'

export default {
    name: 'App',
    components: {
    HeaderTag
}
}
</script>
