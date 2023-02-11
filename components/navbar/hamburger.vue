<script setup>
defineProps({
    hamburger: Boolean
})
</script>
<template>
    <div class="flex flex-col justify-between 
    md:hidden">
        <span v-if="hamburger" class="w-8 h-[2px] bg-white"></span>
        <span v-if="hamburger" class="w-8 h-[2px] bg-white"></span>
        <span v-if="hamburger" class="w-8 h-[2px] bg-white"></span>
        <div v-if="!hamburger" class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" fill="white" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="w-8 h-8">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
            </svg>
        </div>
    </div>
</template>