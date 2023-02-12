<script setup>

useHead({
    title: "The Programmer"
})

const openDrawer = ref(false)

</script>

<template>
    <div class="mx-auto 
    xl:max-w-[1240px] ">
        <Navbar @drawer-action="openDrawer = !openDrawer" />
        <NavbarDrawermenu v-if="openDrawer" />
        <Hero />
        <Supporting />
        <Section2 />
    </div>
</template>