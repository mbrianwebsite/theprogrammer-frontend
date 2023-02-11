<script setup>
defineProps({
    title: String
})
</script>

<template>
    <div class="flex flex-row items-center gap-2 px-6 py-4 bg-[#1C2012] min-w-fit min-h-fit  mx-auto">
        <div class="font-sans font-normal uppercase text-white text-sm">
            {{ title }}
        </div>
        <img class="max-w-[10px] max-h-[10px]" src="~/assets/img/button-icon.svg" alt="Button Icon">
    </div>
</template>