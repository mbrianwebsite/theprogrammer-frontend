<script setup>
defineProps({
    title: String,
    active: Boolean
})


</script>
<template>
    <div class="font-sans font-normal uppercase" :class="{ 'text-[#FFFFFF]': active, 'text-[#FFFFFFBA]': !active }">
        {{ title }}
    </div>
</template>