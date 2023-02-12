<script setup>
defineProps({
    title: String,
})
</script>
<template>
    <div class="flex flex-row gap-2 items-center">
        <div class="font-sans font-normal uppercase text-sm text-white">
            {{ title }}
        </div>
        <img class="max-w-[10px] max-h-[10px]" src="~/assets/img/button-icon.svg" alt="Button Icon">
    </div>
</template>