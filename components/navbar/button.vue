<script setup>
defineProps({
    title: String,
    mini: Boolean
})
</script>
<template>
    <div
        :class="{ 'hidden md:flex md:flex-row md:items-center md:gap-2': !mini, 'flex flex-row gap-2 items-center md:hidden': mini }">
        <div class="font-sans font-normal uppercase text-white">
            {{ title }}
        </div>
        <img class="max-w-[10px] max-h-[10px]" src="~/assets/img/button-icon.svg" alt="Button Icon">
    </div>
</template>