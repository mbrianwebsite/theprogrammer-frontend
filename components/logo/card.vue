<script setup>
import logoBackground from '~/assets/img/section6-img.svg'
defineProps({
    logo: String
})
</script>
<template>
    <div class="flex flex-row bg-cover mx-auto min-w-[100px] min-h-fit content-center
    sm:min-w-[125px]
    md:min-w-[150px]
    lg:min-w-[200px]
    xl:min-w-[248px]" :style="{ backgroundImage: `url(${logoBackground})` }">
        <div class="mx-auto px-4 py-2
        sm:px-6 sm:py-4
        md:px-8 md:py-6
        lg:px-10 lg:py-8
        xl:px-12 xl:py-10">
            <img :src="logo" alt="">
        </div>
    </div>
</template>