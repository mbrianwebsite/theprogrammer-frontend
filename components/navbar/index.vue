<script setup>
const hamburger = ref(true)
</script>

<template>
    <div class="bg-[#3F423733] flex flex-row justify-between px-6 py-7 mt-6 
    sm:px-8
    ">
        <NavbarLogo />
        <NavbarMainmenu />
        <LinkButtonnav title="Sign Up" :mini="false" />
        <NavbarHamburger @click="$emit('drawerAction'); hamburger = !hamburger" :hamburger="hamburger" />
    </div>
</template>