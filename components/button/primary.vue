<script setup>
defineProps({
    title: String
})
</script>

<template>
    <div class="flex flex-row items-center gap-2 px-6 py-4 bg-[#84EC8E] min-w-fit h-fit  mx-auto">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
            <path
                d="M6.3 2.841A1.5 1.5 0 004 4.11V15.89a1.5 1.5 0 002.3 1.269l9.344-5.89a1.5 1.5 0 000-2.538L6.3 2.84z" />
        </svg>

        <div class="font-sans font-normal uppercase text-black text-sm">
            {{ title }}
        </div>
    </div>
</template>