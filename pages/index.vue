<script setup>

useHead({
    title: "The Programmer"
})

const openDrawer = ref(false)

</script>

<template>
    <div class="overflow-clip">
        <div class="mx-auto 
        xl:max-w-[1240px]">
            <Navbar @drawer-action="openDrawer = !openDrawer" />
            <NavbarDrawermenu v-if="openDrawer" />
            <Hero />
            <Supporting />
            <Section2 />
            <Section3 />
            <Section4 />
            <Section5 />
            <Section6 />
            <Section7 />
        </div>
        <Footer />
    </div>
</template>